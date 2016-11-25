# sol-practice
Solidity Practice

# Steps

1 - Download truffle: npm install truffle
2 - Start Truffle: truffle init (creates truffle folder)
3 - Compile Smart Contracts: truffle compile

# Make sure to have testrpc of geth testnet running in the background
The easiest way is to download TestRPC

1 - Download TestRPC: npm install testrpc
2 - In a new terminal window (same folder) run command: testrpc
Your test blockchain should now run in the background

# Migrate and Query

1 - In the migrations folder, remember to add new contracts to the deploy_contracts.js file
2 - Migrate Contracts: truffle migrate (truffle migrate --reset if you have made any changes to the smart contracts)
3 - Run command: truffle console
This brings you to the truffle javascript console where you can interact with your contracts
