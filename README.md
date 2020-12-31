Running on port 8545 on Ganache
Digital bank where you can earn interest for deposting crypto currency. 
Languages used Ethereum, Solidity, Web3.js & Truffle and React.
Additional configuration added in truffle-config.js by changing where the smart contracts go so they can be exposed to the client side of this app.

People will hold Mock Dai tokens and deposit them into the digital bank and will earn dapp tokens as interest.

DaiToken.sol is the ERC 20 contract for Mock Dai
DappToken.sol is the ERC 20 contract for the fictious crypto currency dapp.

Assuming an investor holds mock dai and puts it into the token farm, they stake it and if they stake it on some sort of regular interval they earn the dapp tokens for doing that. 

Used Mocha and Chai to write better tests throughout project
Tests used in TokenFarm.test.js is to describe TokenFarm.

How to test it
Used lite-server to run it locally. Command is npm run dev
To run the react application Command is nmp start
Truffle test,migrate and compile where used and will work. 
You can run this command for the tokens to be deployed by the owner to issue rewards => truffle exec scripts/issue-token.js

