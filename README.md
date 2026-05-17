## 👋 Hi, I'm Juyeon

I am a **Blockchain Backend / Security Engineer** with a strong interest in
**cryptography, smart contract security, and blockchain system reliability**.

My work focuses on understanding how blockchain systems fail in practice
— from cryptographic misuse to transaction ordering and asset settlement —
and designing systems and experiments that make those failure modes explicit.

---

### 🏗️ Escrow Settlement Smart Contract Lab
An **education-only Ethereum smart contract** for studying
secure settlement architecture and mitigation patterns.

📁 **escrow-settlement-contract-lab**
- Commit–reveal pattern to mitigate front-running
- Pull-based settlement (CEI)
- Reentrancy protection, access control, pausability
- Solidity `^0.8.x` checked arithmetic (SafeMath replacement)
- Hardhat tests demonstrating the full lifecycle

This project focuses on **secure contract structure**, not application deployment.

---

### 📊 NFT Frontrunning Detection (Ethereum)
An on-chain analysis pipeline for detecting **NFT frontrunning attacks**
based on Ethereum transaction ordering.

📁 **nft-frontrunning-detection**
- NFT transfer data collection
- OpenSea list-and-buy focused detection heuristic
- Failed transaction analysis (reverted victim tx)
- Explicit attacker–victim ordering constraints

---

### 📈 NFT Price Prediction Model (PPM)
A **multimodal NFT price-level prediction pipeline**
used for analysis and robustness evaluation.

📁 **nft-price-prediction**
- Text + image encoders (BERT, ViT)
- Attention-based feature fusion
- Collection-level signals (floor / average price)
- Designed for analytical use, not automated trading

---

## 🧠 Technical Interests
- Blockchain security & MEV
- Cryptographic protocol design
- Smart contract architecture & audits
- Transaction ordering & mempool analysis
- Secure system design for high-value assets

---

## ⚠️ Disclaimer
All repositories are provided for **educational and research purposes only**.
They intentionally include simplified or vulnerable constructions
and must not be used in production environments.

---

📫 Feel free to explore the repositories or reach out for discussion on
blockchain security and system design.
