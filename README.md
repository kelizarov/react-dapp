# Sample contract for practicing Solidity

This is sample project to practice the development of smart-contracts on Ethereum. Original guide https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13

# How to run

1. Install dependencies:
```
npm install
```

2. Run the node
```
npx hardhat node
```

3. Compile contracts
```
npx hardhat compile
```

4. Deploy contracts
```
npx hardhat run scripts/deploy.js --network localhost
```

5. Create `.env` file in project root with contracts' ids

6. Run server
```
npm start
```

The server should be accessible at http://localhost:3000

You will need MetaMask web extension to be able to interact with contracts with your dev wallets.
