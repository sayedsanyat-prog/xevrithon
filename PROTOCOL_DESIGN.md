XEVRITHON — Protocol Design

1. Purpose

This document defines the protocol design areas that must be specified before implementing the XEVRITHON blockchain.

The protocol must be deterministic: independent nodes must apply the same rules and reach the same validation results.

2. Core Protocol Goals

- Operate as an independent blockchain.
- Support peer-to-peer transactions.
- Enforce a maximum supply of 17,000,000 coins.
- Allow independent nodes to validate blocks and transactions.
- Provide transparent and verifiable consensus rules.
- Protect users through established cryptographic methods.

3. Transaction Design

The planned transaction model is UTXO (Unspent Transaction Output).

The detailed design must define:

- Transaction structure
- Inputs and outputs
- Digital signatures
- Transaction identifiers
- Fees
- Validation rules
- Prevention of double spending

4. Block Design

The block specification must define:

- Block header format
- Previous block hash
- Transaction commitment
- Timestamp rules
- Proof-of-Work field
- Block validation rules
- Maximum block size or weight

5. Consensus Design

The current planned consensus direction is Proof of Work (PoW).

The final design must specify:

- Mining algorithm
- Block target and difficulty
- Difficulty adjustment
- Chain selection rules
- Block reward
- Transaction fee handling
- Invalid block rejection

6. Supply and Rewards

Maximum supply: 17,000,000 coins.

The following details remain undecided:

- Initial block reward
- Reward schedule
- Halving or alternative reward mechanism
- Smallest coin unit
- Treatment of transaction fees

The supply rules must prevent creation of coins beyond the maximum supply.

7. Network Design

The peer-to-peer protocol must specify:

- Node discovery
- Peer communication
- Message formats
- Block and transaction propagation
- Network identification
- Protection against malicious messages

8. Cryptographic Design

The protocol must select established cryptographic algorithms for:

- Block and transaction hashing
- Digital signatures
- Key generation
- Address creation

All selections require technical research and security review.

9. Open Design Questions

No unresolved parameter in this document should be treated as a finalized consensus rule.

Each major protocol decision must be documented in DECISIONS.md before implementation.

10. Current Status

This is an initial protocol design document.

The protocol is not finalized, implemented, or independently audited.

---

Document Status: Initial
Project: XEVRITHON
Last Updated: 2026-11-23