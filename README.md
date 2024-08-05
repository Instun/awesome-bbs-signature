# awesome-bbs-signature
A curated list of awesome bbs signature specifications, libraries, softwares and resources

## Abstract
BBS is a digital signature scheme categorized as a form of short group signature that supports several unique properties. Notably, the scheme supports signing multiple messages whilst producing a single output digital signature. Through this capability, the possessor of a signature is able to generate proofs that selectively disclose subsets of the originally signed set of messages, whilst preserving the verifiable authenticity and integrity of the messages. Furthermore, these proofs are said to be zero-knowledge in nature as they do not reveal the underlying signature; instead, what they reveal is a proof of knowledge of the undisclosed signature.
## Specifications

Specifications related to BBS Signature.

- The BBS Signature Scheme
    - [latest specification](https://identity.foundation/bbs-signature/draft-irtf-cfrg-bbs-signatures.html)
    - [draft-irtf-cfrg-bbs-signatures-06](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bbs-signatures/06/)
    - [draft-irtf-cfrg-bbs-signatures-05](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bbs-signatures/05/)
    - [draft-irtf-cfrg-bbs-signatures-04](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bbs-signatures/04/)
    - [draft-irtf-cfrg-bbs-signatures-03](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bbs-signatures/03/)
    - [draft-irtf-cfrg-bbs-signatures-02](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bbs-signatures/02/)
    - [draft-irtf-cfrg-bbs-signatures-01](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bbs-signatures/01/)
    - [draft-irtf-cfrg-bbs-signatures-00](https://datatracker.ietf.org/doc/draft-irtf-cfrg-bbs-signatures/00/)
    - [Source for this draft and an issue tracker](https://github.com/decentralized-identity/bbs-signature)
- W3C BBS Cryptosuite
    - [BBS Cryptosuite v2023 BBS Cryptosuite v2023](https://www.w3.org/TR/vc-di-bbs/)

## Libraries

### Libraries that are implemented according to draft 6
- [digitalbazaar/bbs-signatures](https://github.com/digitalbazaar/bbs-signatures) - A JavaScript BBS Signatures Implementation.
- [fibjs/fibjs](https://github.com/fibjs/fibjs/tree/dev/fibjs/src/crypto/bbs) - c++ implementation of BBS signature.
- [mattrglobal/pairing_crypto](https://github.com/mattrglobal/pairing_crypto) - A library for pairing based cryptography in Rust.
- [microsoft/bbs-node-reference](https://github.com/microsoft/bbs-node-reference) - TypeScript/node reference implementation of BBS signature.
- [roblesjoel/P2_BBS_Signature](https://github.com/roblesjoel/P2_BBS_Signature) - P2 project about BBS Signatures in java.

### Libraries implemented according to earlier specifications
- [trinsic-id/bbs](https://github.com/trinsic-id/bbs) - Reference implementation of BBS Signatures in Rust(draft-irtf-cfrg-bbs-signatures-03).
- [dyne/Zenroom](https://github.com/dyne/Zenroom/blob/3d9c2c31babfdb9e5e8f5171125639f0afa849bd/src/lua/crypto_bbs.lua) - lua reference implementation of BBS signature (draft-irtf-cfrg-bbs-signatures-02).
- [hyperledger/aries-framework-go](https://github.com/hyperledger/aries-framework-go/tree/main/component/kmscrypto/crypto/primitive/bbs12381g2pub) - Hyperledger Aries Framework Go provides packages (draft-irtf-cfrg-bbs-signatures-00).
- [hyperledger-archives/ursa](https://github.com/hyperledger-archives/ursa) - Hyperledger Ursa (a shared cryptographic library) has moved to end-of-life status.

### Wrapped library
- [mattrglobal/bbs-signatures](https://github.com/mattrglobal/bbs-signatures) - An implementation of BBS+ signatures for node and browser environments (based on Hyperledger Ursa project via wasm).
- [mattrglobal/ffi-bbs-signatures](https://github.com/mattrglobal/ffi-bbs-signatures) - An FFI wrapper around the implementation of BBS+ signatures in Ursa (based on Hyperledger Ursa project).
- [mattrglobal/node-bbs-signatures](https://github.com/mattrglobal/node-bbs-signatures) - An implementation of BBS+ signatures using rust and typescript for node.js (based on Hyperledger Ursa project).

## Resources

Resources related to BBS Signature.
