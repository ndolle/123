
| Blockchain | Primary Signature Scheme | Quantum Vulnerability | Mitigation Status |
| --- | --- | --- | --- |
| **Bitcoin (BTC)** | ECDSA (ECC) | **High:** ~25%-35% of coins are in "exposed" addresses (P2PK/reused). | Discussions on "soft fork" for PQC address types. |
| **Ethereum (ETH)** | ECDSA / BLS | **High:** Signatures and KZG commitments are vulnerable. | Researching STARK-based and Lattice-based account abstraction. |
| **Litecoin (LTC)** | ECDSA | **High:** Vulnerable to Shor's algorithm. | No active PQC implementation in mainnet. |
| **Zcash (ZEC)** | ECDSA / zk-SNARKs | **High:** Current Zero-knowledge Proofs may be vulnerable. | Exploring quantum-resistant zk-STARKs. |
| **Monero (XMR)** | Ring Signatures (ECC) | **High:** Privacy-signatures based on ECC are breakable. | Theoretical research into post-quantum ring signatures. |
| **Hedera (HBAR)** | Ed25519 | **Medium:** Standard ECC signature is vulnerable. | Actively waiting for NIST standardization to implement FALCON. |
| **HBAR** *(duplicate row in original)* | Ed25519 | **Medium:** Standard ECC signature is vulnerable. | Actively waiting for NIST standardization to implement FALCON. |
| **IOTA** | Ed25519 (previously W-OTS) | **Medium:** Transitioned away from hash-based to lighter ECC. | Long-term goal to return to PQC-compliant signatures. |
| **Solana (SOL)** | Ed25519 | **High:** ECC-based high-throughput signatures are vulnerable. | Exploring PQC signature verification on testnets. |
| **QRL** | XMSS | **Low:** Native quantum-resistant signature scheme. | Uses IETF-standardized hash-based signatures. |
| **Abelian** | Lattice-based | **Low:** Built natively for the post-quantum era. | Uses Module-LWE and Module-SIS primitives. |

Would you like me to consolidate the duplicate Hedera (HBAR) row, or perhaps convert this data into a CSV format so you can easily paste it into Excel or Google Sheets?
