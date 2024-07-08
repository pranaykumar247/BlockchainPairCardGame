
# BlockchainPairGame

This is a basic blockchain game developed using tools like Solidity, Ether.js, Hardhat, and Truffle. The game utilizes the Ethereum blockchain and the ERC-721 standard for NFTs.

## Contents

1. [Installation](#installation)
2. [Guidance for Running the Code](#guidance-for-running-the-code)

### Installation

1. **Clone the repo:**
   ```bash
   git clone https://github.com/pranaykumar247/BlockchainPairGame.git
   ```

2. **Install Node.js:**
   [Download Node.js](https://nodejs.org/en/download/)

3. **Install Truffle:**
   ```bash
   npm install -g truffle@5.1.39
   ```

4. **Install Ganache CLI:**
   [Download Ganache](https://trufflesuite.com/ganache/)

5. **Install MetaMask extension:**
   [Download MetaMask](https://metamask.io/download.html)

### Guidance for Running the Code

1. **Install all the dependencies:**
   ```bash
   npm install
   ```

2. **Run the development server:**
   ```bash
   npm run start
   ```

   If you encounter the following error:
   ```
   Error: error:0308010C:digital envelope routines::unsupported
   ```

   Follow these steps to resolve it:

   1. **Set the environment variable for SSL:**
      ```bash
      $env:NODE_OPTIONS="--openssl-legacy-provider"
      ```

   2. **Run the development server again:**
      ```bash
      npm start
      ```
