# Loyalty_Points

This demostrates usage of Ethereum's "Smart Contracts" for Loyalty Point programs (supermarkets, airline companies etc.)


This code consists of 2 files, contract.sol and index.html.
These have to be imported in Ethereum's Mix IDE (v.1.0.3)
After creating a new project and importing the 2 files, you have to execute this command in JS console
web3.eth.defaultAccount = web3.eth.accounts[0] 	
(else it creates a bug), see also https://forum.ethereum.org/discussion/3530/web3-js-line-3748-uncaught-invalid-address )
Then click on "add transaction" and "create contract".

Within the IDE's web browser, you can enter a new or existing customer card number and add or subtract loyalty points.
For each loyalty point change, an Ethereum blockchain smart contract transaction is generated (visible on the right window pane).
The blockchain tracks any changes to the customer's points using smart contracts. Effectively it serves as a public decentralized database.


Useful links:
https://www.ethereum.org/cli
https://solidity.readthedocs.org/en/latest/index.html
http://www.ethdocs.org/en/latest/index.html
https://github.com/ethereum/wiki/wiki/Mix:-The-DApp-IDE



