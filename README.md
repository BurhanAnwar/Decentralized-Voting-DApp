# 🗳️ Decentralized Voting DApp

This repository contains a full-stack decentralized application (DApp) built using **Solidity**, **Truffle**, and a **JavaScript-based frontend**. The project demonstrates a simple blockchain-based voting system deployed on the Ethereum Virtual Machine (EVM).

---

## 📁 Project Structure

```
.
├── burhan-app/        # Smart contracts & Truffle configuration
│   ├── contracts/     # Solidity smart contracts (Voting.sol)
│   ├── migrations/    # Deployment scripts
│   ├── build/         # Compiled contract artifacts
│   └── test/          # Truffle tests
│
├── frontend/          # Frontend interface for the DApp
│   ├── index.html     # UI for interacting with smart contracts
│   ├── app.js         # Web3.js logic for smart contract interaction
│   └── package.json   # Dependencies and scripts
```

---

## 🚀 Features

- ✅ Deploy and interact with a `Voting` smart contract
- ✅ Add proposals
- ✅ Allow users to vote via the frontend UI
- ✅ Reflect real-time contract state changes on the frontend
- ✅ Uses Web3.js to connect to the Ethereum network

---

## 🔧 Installation

### Prerequisites

- Node.js & npm
- Truffle: `npm install -g truffle`
- Ganache (for local blockchain testing)

---

### Backend (Smart Contracts)

```bash
cd burhan-app
npm install          # If needed
truffle compile
truffle migrate
```

> Ensure Ganache is running on your machine if you're deploying locally.

---

### Frontend

```bash
cd frontend
npm install
# Then open index.html in your browser (use Live Server if needed)
```

---

## 📜 Smart Contract: `Voting.sol`

This contract implements a basic voting system with the following logic:
- Register proposals
- Enable users to vote
- Ensure a user can only vote once
- Calculate and display the winning proposal

---

## 🧪 Testing

```bash
cd burhan-app
truffle test
```

---

## 📦 Tech Stack

- **Solidity** – Smart contract language
- **Truffle** – Development framework for Ethereum
- **Ganache** – Local blockchain for development
- **Web3.js** – Ethereum JavaScript API for frontend interaction
- **HTML/CSS/JavaScript** – UI for interacting with the blockchain

---

## 🛡️ License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## 👨‍💻 Author

Muhammad Burhan ud Din  
