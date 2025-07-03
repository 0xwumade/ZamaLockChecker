# ZamaLockChecker

📦 Clone & Install
```
bash
Copy
Edit
git clone https://github.com/0xwumade/zama.git
cd zama
npm install
```
🔨 Deploy a New Contract
This repo already contains a sample Lock.sol. You can deploy to Sepolia using:

bash
Copy
Edit
```
npx hardhat run scripts/deploy.js --network sepolia
```
🧪 Run Locally
Serve the frontend locally:

bash
Copy
Edit
```
npx live-server docs/
```
or just open docs/index.html in your browser.

⚒️ Stack
Smart Contract: Solidity Lock.sol

Hardhat for testing & deployment

Ethers.js for blockchain interaction

Infura Sepolia endpoint

Hosted on GitHub Pages

📄 Notes
This DApp works only with Lock contracts deployed on Sepolia testnet that implement unlockTime().

Make sure your Infura Project ID is valid in the script.

This is a testnet-only project. Do not send mainnet ETH to testnet contracts.

👤 Author
🧑‍💻 Built by 0xwumade

If you find this useful, feel free to ⭐️ the repo and contribute!

📌 Next Steps (optional)
✅ Add wallet connection (Metamask)
✅ Add Withdraw button (if you’re the owner)
✅ Make it mobile-friendly
