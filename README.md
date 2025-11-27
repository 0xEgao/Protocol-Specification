# Coinswap Protocol Documentation
This repository contains the complete documentation for the **Coinswap Protocol**, an atomic swap protocol that enables trustless atomic swaps through a decentralized, Sybil-resistant marketplace using Bitcoin-seeded fidelity bonds. This documentation provides an in-depth overview of the protocol's architecture, functionality, and other important details.

## Documentation layout

### Version 1 docs

All documentation for the first version of the protocol is located in the [v1](v1) directory.Reading v1 is recommended to understand the historical context and design motivations that influenced later revisions.

The v1 docs are organized as follows:

0. [Introduction](v1/0_introduction.md): An overview of the Coinswap Protocol, its history, and core features.
1. [Architecture](v1/1_architecture.md): An explanation of the protocol’s architecture, participants, and transaction types.
2. [Messages](v1/2_messages.md): A detailed description all messages exchanged during a swap.
3. [Protocol Flow](v1/3_protocol-flow.md): A Step-by-Step description of a Coinswap.
4. [Fidelity](v1/4_fidelity.md): Explanation of fidelity bonds and their role in the protocol.
5. [Fees](v1/5_fees.md): Overview of how fees are structured and accounted for within Coinswap transactions.
6. [Security](v1/6_security.md): A discussion of the security considerations in the Coinswap Protocol.
7. [privacy](v1/7_privacy.md): A discussion on how coinswap provides privacy.

### Version 2 docs

All documentation for the second version of the protocol is located in the [v2](v2) directory.The refinement of protocol and adoption of Taproot and MuSig2 for improved privacy and efficiency.

The v2 docs are organized as follows:

1. [Architecture](v2/1_architecture.md): Updated architecture, participants, and transaction types for the Taproot–MuSig2-based design.
2. [Messages](v2/2_messages.md): A detailed specification of all messages exchanged during a swap, including fields and semantics.
3. [Protocol Flow](v2/3_protocol-flow.md): Step-By-Step description of a Taproot–MuSig2 Coinswap.
