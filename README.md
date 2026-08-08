# Quantus Improvement Proposals (QIPs)

This repository contains the Quantus Improvement Proposals (QIPs) - design documents that specify upgrades and changes to the Quantus Network. QIPs document how our chain has deviated from the original Substrate solochain template and serve as the formal process for proposing new features and improvements.

## What are QIPs?

QIPs are design documents providing information to the Quantus community or describing new features for the Quantus Network. Each QIP should provide a concise technical specification and rationale for the proposed feature.

## Current QIPs

- **QIP-0001**: QIP Purpose and Guidelines - Defines the QIP process and formatting standards
- **QIP-0002**: Hierarchical Deterministic Wallets For Lattice Keys - Post-quantum HD wallet implementation
- **QIP-0003**: RSA-Shortcut Proof of Work - Deprecated hybrid classical/quantum mining algorithm (superseded by QIP-0013)
- **QIP-0004**: Post-Quantum Cryptography Integration in libp2p Networking Stack - PQC support for networking layer
- **QIP-0005**: Wormhole Addresses - Scalable Post-Quantum ZK-Signatures
- **QIP-0006**: ML-DSA for Extrinsic Signatures - Lattice signatures for Substrate extrinsics
- **QIP-0007**: ZK-Tree - Poseidon Merkle tree for wormhole deposits
- **QIP-0008**: Checkphrase - Human-readable address checksum (PBKDF2)
- **QIP-0009**: Time-Scheduled Transactions - Timestamp-aware scheduler pallet
- **QIP-0010**: Reversible Transactions - Delayed, cancellable transfers
- **QIP-0011**: High-Security Accounts - Mandatory delays with guardian cancel/recovery
- **QIP-0012**: Quantum-Secure Bridge - Hyperlane-based design (not implemented yet)
- **QIP-0013**: Poseidon2 Proof of Work - Current consensus PoW algorithm

## Contributing

To propose a new QIP, please follow the guidelines outlined in [QIP-0001](qip-0001.md). All QIPs should be submitted as pull requests for community review and discussion.
