1. Setup MetaMask for Base Mainnet

Add the Base network manually if it's not already there:

Network Name: Base Mainnet

RPC URL: https://mainnet.base.org

Chain ID: 8453

Currency Symbol: ETH

Block Explorer: https://basescan.org

2. Open Remix

Go to https://remix.ethereum.org

3. Create Your Solidity File

1. In the File Explorer, click "contracts" > "+" and name it MyBaseToken.sol


2. Paste the code

   4. Compile the Contract

1. Click the Solidity Compiler tab.


2. Select version 0.8.20


3. Click Compile MyBaseToken.sol
4. 5. Deploy Using MetaMask

1. Click the Deploy & Run Transactions tab.


2. Under Environment, select Injected Provider - MetaMask

MetaMask will ask for permission to connect.



3. Choose your contract (MyBaseToken)


4. Enter the constructor argument (e.g. 1000000000000000000000000 for 1M tokens with 18 decimals)


5. Click Deploy


6. Confirm the transaction in MetaMask



1. Go to: https://basescan.org


2. Search your contract address.


3. Click "Verify and Publish".


4. Fill out:

Compiler version (must match exactly)

Optimization settings

Flattened Solidity code (you can flatten with npx hardhat flatten)

Constructor arguments (ABI-encoded if needed)# Base-deployment-
Let's learn how to deploy on base network 
