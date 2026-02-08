# Simple Multi-Signature Wallet

This repository contains a streamlined Multi-Signature (MultiSig) wallet. It is designed for groups or DAO members who want to manage shared funds securely by requiring a minimum number of confirmations (M of N) before any transaction can be sent.

### Features
* **Threshold Governance:** Set a specific number of required signatures for transaction execution.
* **Transaction Queue:** Propose transactions for owners to review and confirm.
* **Security:** Prevents single points of failure by distributing control across multiple private keys.

### How it Works
1. **Submit:** Any owner can submit a transaction proposal.
2. **Confirm:** Other owners review and confirm the transaction.
3. **Execute:** Once the required threshold of confirmations is met, any owner can trigger the execution.
