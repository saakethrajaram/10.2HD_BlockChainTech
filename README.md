````markdown
# SIT728 Full-Stack Decentralized Application (DApp)

## About My Project

This repository contains my High Distinction-level project for **SIT728 – Blockchain Technologies and Real-World Applications**. I built a **full-stack decentralized application (DApp)** using Ethereum, Hardhat, and ReactJS.  

My DApp demonstrates advanced blockchain concepts, including **smart contract deployment, fund management, and secure interactions**, all running on a local blockchain network. Throughout this project, I challenged myself to combine what I’ve learned in class with my own research to create something both technically solid and user-friendly.

---

## What I Built

- **Smart Contract (`Lock.sol`)**
  - I designed it so users can deposit and withdraw Ether safely.
  - Withdrawals are locked until a specific unlock time.
  - I emit events on withdrawals so users can track activity on-chain.

- **Front-End (ReactJS)**
  - I implemented a **Connect Wallet** feature to interact with MetaMask.
  - Users can see the contract balance and their connected account.
  - I created simple forms for depositing and withdrawing funds directly from the browser.

- **Blockchain Integration**
  - I deployed and tested my smart contract on a **local Hardhat network**.
  - I used **ethers.js** for all interactions between my front-end and the blockchain.
  - I also made sure my contract is secure, scanning it for vulnerabilities and testing edge cases.

---

## How to Run My Project

1. **Clone my repository:**
   ```bash
   git clone https://github.com/saakethrajaram/10.2HD_BlockChainTech.git
   cd 10.2HD_BlockChainTech/contract
````

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start a local blockchain:**

   ```bash
   npx hardhat node
   ```

4. **Compile and deploy my smart contract:**

   ```bash
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network localhost
   ```

5. **Start the front-end:**

   ```bash
   cd ../frontend
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) to use the DApp.

---

## How My DApp Works

1. I connect my MetaMask wallet to the DApp.
2. I can see the current balance of the smart contract and my connected account.
3. I can deposit Ether into the contract by entering an amount and clicking **Deposit Funds**.
4. Once the unlock time has passed, I can withdraw funds safely.
5. All transactions and events are tracked and displayed in the UI for transparency.

---

## Technical Details

* **Blockchain Layer:** Ethereum (local Hardhat network)
* **Smart Contract Language:** Solidity (`0.8.24`)
* **Front-End:** ReactJS with `ethers.js` for blockchain interaction
* **Wallet Integration:** MetaMask
* **Security Measures:** I scanned my smart contract for vulnerabilities and ensured the front-end handles user transactions safely.

---

## Project Structure

```
10.2HD_BlockChainTech/
├─ contract/            # Hardhat project
│  ├─ Lock.sol          # Smart contract
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

## What I Learned

Through building this DApp, I gained hands-on experience with:

* Deploying and interacting with **Ethereum smart contracts**.
* Developing a **full-stack DApp** with blockchain, front-end, and wallet integration.
* Implementing **secure transaction handling** and time-locked withdrawal logic.
* Testing and debugging both smart contracts and front-end interactions.
* Writing clear documentation so others can replicate and understand my work.

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
