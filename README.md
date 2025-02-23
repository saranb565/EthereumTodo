# Ethereum Blockchain To-Do App

## 📌 Introduction
This project is a decentralized To-Do application built on the Ethereum blockchain. It allows users to securely create, manage, and complete tasks in a tamper-proof manner using smart contracts.

## 🚀 Features
- 📝 **Add, Update, and Delete Tasks** securely on the blockchain.
- 🔐 **Decentralized Storage** using Ethereum smart contracts.
- 💡 **Metamask Integration** for secure transactions.
- 📜 **Smart Contract Development** with Solidity.
- 🎯 **Frontend** built with React & Web3.js.

## 🏗️ Tech Stack
- **Smart Contract**: Solidity
- **Blockchain Framework**: Truffle Suite
- **Frontend**: React.js, Web3.js
- **Backend**: Node.js
- **Storage**: Ethereum Blockchain

## 📂 Project Structure
```
ethereum-todo-app/
│-- contracts/        # Smart contracts (Solidity)
│-- migrations/       # Deployment scripts
│-- src/              # React frontend
│-- test/             # Smart contract tests
│-- truffle-config.js # Truffle configuration
```

## ⚙️ Setup & Installation
### 1️⃣ Clone the Repository
```sh
git clone <repo-url>
cd ethereum-todo-app
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Start Ganache (Local Blockchain)
1. Open Ganache GUI.
2. Create a new workspace or use a Quickstart Ethereum workspace.
3. Note the RPC server URL (e.g., `http://127.0.0.1:7545`).

### 4️⃣ Deploy Smart Contract
```sh
truffle migrate --reset --network development
```

### 5️⃣ Run the App
```sh
npm start
```

## 🛠️ Usage
1. Connect Metamask to your local blockchain.
2. Create and manage tasks via the frontend.
3. View updates reflected on the Ethereum blockchain.

## 🔗 Future Improvements
- 📌 Integrate IPFS for decentralized storage.
- 📌 Add user authentication using Web3.
- 📌 Deploy to a public Ethereum testnet.

## 🤝 Contributing
Feel free to fork and submit PRs. Contributions are welcome!

## 📜 License
This project is licensed under the MIT License.



