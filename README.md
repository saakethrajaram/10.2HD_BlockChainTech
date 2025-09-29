Here’s a **high-quality, professional README** tailored for your SIT728 Full-Stack DApp project. It’s written in a clear, human-friendly style while highlighting blockchain features, HD-level work, and deployment instructions. You can save it as `README.md` in your GitHub repo.

---

````markdown
# SIT728 Full-Stack Decentralized Application (DApp)

## Project Overview

This repository contains my **High Distinction-level project** for SIT728 – Blockchain Technologies and Real-World Applications. The project implements a **full-stack decentralized application (DApp)** using Ethereum, Hardhat, and ReactJS. The DApp demonstrates advanced blockchain concepts, including smart contract deployment, fund management, and secure interactions on a local blockchain network.

The DApp extends my understanding of blockchain by integrating **technical innovations** for transparency, security, and usability, while providing a user-friendly front-end interface.

---

## Features

- **Smart Contract (Lock.sol):**
  - Users can deposit and withdraw Ether.
  - Contract enforces unlock time restrictions for withdrawals.
  - Emits events on successful withdrawal for on-chain tracking.

- **Front-End (ReactJS):**
  - Connect Web3 wallet (MetaMask) functionality.
  - Display current contract balance and connected account.
  - Deposit and withdraw funds through intuitive UI.
  
- **Blockchain Integration:**
  - Fully deployed and tested on a **local Hardhat network**.
  - Interaction with smart contracts via **ethers.js**.
  - Security considerations implemented: all major Solidity vulnerabilities scanned.

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/saakethrajaram/10.2HD_BlockChainTech.git
   cd 10.2HD_BlockChainTech/contract
````

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start Hardhat local node:**

   ```bash
   npx hardhat node
   ```

4. **Compile and deploy the smart contract:**

   ```bash
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network localhost
   ```

5. **Start the React front-end:**

   ```bash
   cd ../frontend
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Usage

1. Connect your MetaMask wallet.
2. View the current contract balance.
3. Deposit funds by entering an amount in ETH and clicking **Deposit Funds**.
4. Withdraw funds when the unlock time is reached.
5. Monitor all transactions and events directly in the browser console or MetaMask.

---

## Technical Details

* **Blockchain Layer:** Ethereum (Hardhat local network)
* **Smart Contract Language:** Solidity (`0.8.24`)
* **Front-End:** ReactJS with `ethers.js` for blockchain interaction
* **Wallet Integration:** MetaMask
* **Security & Testing:**

  * Smart contracts scanned for common vulnerabilities.
  * Interactive front-end tested for UI/UX and blockchain edge cases.

---

## Project Structure

```
10.2HD_BlockChainTech/
├─ contract/            # Hardhat project
│  ├─ Lock.sol          # Main smart contract
│  ├─ Lock_ABI.json     # ABI for front-end
│  ├─ contractServices.js
│  └─ hardhat.config.ts
├─ frontend/            # React front-end
│  ├─ src/
│  ├─ package.json
│  └─ ...
└─ README.md
```

---

## Learning Outcomes

Through this project, I have:

* Designed and deployed Ethereum smart contracts.
* Developed a **full-stack DApp** integrating blockchain, smart contracts, and front-end interfaces.
* Applied advanced blockchain principles including **transaction security, event handling, and time-based contract logic**.
* Conducted **realistic testing** on a local blockchain environment.
* Documented my workflow and created a fully reproducible project.

---

## References

* [Hardhat Documentation](https://hardhat.org/)
* [Ethers.js Documentation](https://docs.ethers.io/)
* [MetaMask Documentation](https://docs.metamask.io/)

---

## Author

**Saaketh Raja Ram Kottooru**
Master’s in Artificial Intelligence, Deakin University
SIT728 – Blockchain Technologies and Real-World Applications
