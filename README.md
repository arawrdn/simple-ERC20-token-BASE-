Step-by-Step Guide to Deploy on Remix

Open Remix: https://remix.ethereum.org

Create a new file: MyToken.sol → paste the code above

Compile:

Solidity Compiler → version 0.8.30

Click Compile

Deploy:

Go to Deploy & Run Transactions

Environment → Injected Web3 (connect Base wallet)

Constructor parameter → initialSupply (e.g., 1000000000000000000000000 for 1M tokens)

Click Deploy

Verify on BaseScan:

Copy the deployed contract address

Open BaseScan → Verify & Publish

Paste the source code

Compiler → 0.8.30

Set license → MIT

Submit
