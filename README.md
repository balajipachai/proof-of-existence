# Proof of Existence

This project is a basic illustration of proof of existence on Ethereum Blockchain using Solidity smart contracts and IPFS. You can store any document on IPFS and the document's hash returned by IPFS is stored in blockchain.
This system can be used for storing academic results, identity documents, participation certificates of events etc with the security of blockchain.

## Getting Started

1. Clone the repository

   ```
   git clone https://github.com/balajipachai/proof-of-existence.git
   ```

2. Run the development console.

   ```
   ganache - cli
   ```

3. Compile and migrate the smart contracts.

   ```
   npm run compile
   npm run migrate
   ```

4. Run the React app. Smart contract changes must be manually recompiled and migrated.

   ```
   npm run start
   ```

5. Truffle can run tests written in Solidity or JavaScript against your smart contracts. Note the command varies slightly if you're in or outside of the development console.

   ```javascript
   npm run test:contracts
   ```

6. Jest is included for testing React components. Compile your contracts before running Jest, or you may receive some file not found errors.

   ```
   npm run test
   ```

7. To build the application for production, use the build script. A production build will be in the `app/build` folder.
   ```
   npm run build
   ```

This repo is created by referring https://github.com/truffle-box/drizzle-box
