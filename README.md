# 🧾 Decentralized Donation & Relief Tracker

A blockchain-powered platform designed to bring **transparency, traceability, and trust** to the donation and disaster relief process. Built with **Ethereum**, **Solidity**, and **React**, this platform ensures that every rupee donated is trackable and used with accountability.

---

## 📌 Problem Statement

In many developing countries like Nepal, disaster relief and donation systems are plagued with issues such as:
- Mismanagement of funds
- Lack of transparency
- No real-time tracking of where donations go
- Donor distrust due to corruption

---

## ✅ Solution

This platform leverages **blockchain** and **smart contracts** to:
- Enable anyone to **donate to verified campaigns**
- Ensure **funds are held in escrow** and released only after milestone verification
- Store **proof of work (images, receipts)** on **IPFS**
- Provide a **public ledger** of all donations and fund movements

---

## 🎯 Key Features

- ✅ Create and manage verified donation campaigns
- 💰 Donate with full transparency (via MetaMask)
- 🔐 Funds are locked in a smart contract until verified
- 📷 Upload and view milestone proofs (stored on IPFS)
- 📊 Public tracking of fund flows and usage
- 🧾 Donor recognition via wallet address (optional NFTs)

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Smart Contracts | Solidity, Hardhat |
| Blockchain | Ethereum (Sepolia Testnet) |
| Frontend | React.js |
| Web3 Connection | Ethers.js |
| Wallet | MetaMask |
| Media Storage | IPFS (via Web3.Storage or Pinata) |
| Hosting | Vercel / Netlify |
| Optional DB | MongoDB (for metadata/off-chain tracking) |

---

## 🚀 Getting Started

### Prerequisites

- Node.js & npm
- MetaMask wallet
- Hardhat (for smart contract development)
- React.js setup

### Installation

```bash
# Clone the repo
git clone [https://github.com/bidur7745/D-Donation-Relief-Tracker]
cd donation-tracker

# Install dependencies
npm install
