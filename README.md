# adel-token-contract
AdelToken is an ERC-20 token built on the Polygon (Amoy) network. This project uses Hardhat for smart contract development, testing, and deployment, and integrates with MetaMask as the primary wallet for interacting with the token.

Features
- ERC-20 compliant token
- Built on Polygon Amoy testnet
- Hardhat for compilation, deployment, and testing
- MetaMask wallet integration
- Ready for future dApp development

Tech Stack
- Blockchain: Polygon (Amoy testnet)
- Smart Contract Framework: Hardhat
- Wallet Integration: MetaMask
- Token Standard: ERC-20


Installation & Setup
1. Clone the repo
  git clone https://github.com/your-username/adel-token-contract.git
  cd adel-token-contract

3. Install dependencies
  npm install

4. Compile smart contracts
  npx hardhat compile

6. Deploy to Polygon Amoy
   Make sure you have a .env file with your PRIVATE_KEY and RPC_URL for Polygon Amoy.
     npx hardhat run scripts/deploy.ts --network amoy


Usage
Import the deployed contract address into MetaMask as a custom token.
You’ll be able to send, receive, and manage AdelToken directly from your wallet.
Use Hardhat tasks or scripts to interact with the smart contract (mint, transfer, etc.).
