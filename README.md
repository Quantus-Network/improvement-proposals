# Quantus Improvement Proposals (QIPs)

This repository contains the Quantus Improvement Proposals (QIPs) - design documents that specify upgrades and changes to the Quantus Network. QIPs document how our chain has deviated from the original Substrate solochain template and serve as the formal process for proposing new features and improvements.

## What are QIPs?

QIPs are design documents providing information to the Quantus community or describing new features for the Quantus Network. Each QIP should provide a concise technical specification and rationale for the proposed feature.

## Current QIPs

- [**QIP-0001**](qip-0001.md): QIP Purpose and Guidelines - Defines the QIP process and formatting standards
- [**QIP-0002**](qip-0002.md): Hierarchical Deterministic Wallets For Lattice Keys - Post-quantum HD wallet implementation
- [**QIP-0003**](qip-0003.md): RSA-Shortcut Proof of Work - Superseded by QIP-0013
- [**QIP-0004**](qip-0004.md): PQC in litep2p Networking Stack - Dilithium identity + ML-KEM Noise
- [**QIP-0005**](qip-0005.md): Wormhole Addresses - Scalable Post-Quantum ZK-Signatures
- [**QIP-0006**](qip-0006.md): ML-DSA for Extrinsic Signatures - Lattice signatures for Substrate extrinsics
- [**QIP-0007**](qip-0007.md): ZK-Tree - 4-ary Poseidon Merkle tree for balance credits
- [**QIP-0008**](qip-0008.md): Checkphrase - Human-readable address checksum (PBKDF2)
- [**QIP-0009**](qip-0009.md): Time-Scheduled Transactions - Timestamp-aware scheduler pallet
- [**QIP-0010**](qip-0010.md): Reversible Transactions - Delayed, cancellable transfers
- [**QIP-0011**](qip-0011.md): High-Security Accounts - Mandatory delays with guardian cancel/recovery
- [**QIP-0012**](qip-0012.md): Quantum-Secure Bridge - Hyperlane-based design (not implemented yet)
- [**QIP-0013**](qip-0013.md): Poseidon2 Proof of Work - Current consensus PoW algorithm (replaces QIP-0003)

## Contributing

To propose a new QIP, please follow the guidelines outlined in [QIP-0001](qip-0001.md). All QIPs should be submitted as pull requests for community review and discussion.
