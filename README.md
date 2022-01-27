# Chainlist - Your classifieds on Ethereum

Chainlist is a sample Ethereum Dapp linked to the course available on Udemy: https://www.udemy.com/getting-started-with-ethereum-solidity-development

This repository gives the latest configuration (january 2022) and sources files to run the contracts and the tests on Windows 10

# latest configuration
Ganache v2.5.4
Truffle v5.4.30 (core: 5.4.30)
Solidity v0.5.16 (solc-js)

Node v16.13.2
npm 8.3.2

Web3.js v1.5.3


Windows 10

Don't forget to install hdwalet-provider under the project directory npm install @truffle/hdwallet-provider
(npm audit fix --force if any problem)

Geth 1.10.15-stable, if you want to run a local node


**Make sure you don't run tests on Ethereum's main net otherwise you will use real ether with no chance to get them back**

Pascal DUVAL - 01/2022
thanks to Sebastien Arbogast, the author of the udemy course

# bugs remaining with truffle compilation, test and migration allright 
[{
	"resource": "...chainlist-truffle5/contracts/ChainList.sol",
	"severity": 8,
	"message": "Invalid type for argument in function call. Invalid implicit conversion from address to address payable requested.",
	"startLineNumber": 57,
}]

[{
	"resource": "......chainlist-truffle5/contracts/Ownable.sol",
	"message": "Type address is not implicitly convertible to expected type address payable.",
	"startLineNumber": 17,
}]


