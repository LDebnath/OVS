

# OVS

OVS is an online voting platform backed by blockchain.


#### Languages used :
1. For Smart Contract: Solidity
2. Frontend: JavaScript, HTML, CSS
3. Development Tools: Truffle, Ganache


#### Importing an account from ganache to metamask

1. Open ganache and select show keys on any account. The show keys button is the key icon.
2. Copy the private key and click done.
3. Open the metamask menu which can be accessed by clicking the profile picture and select import account.
4. Paste the private key copied from ganache and click import.

#### For deploying the project

`cd E-Voting_System_Blockchain`

`npm i`

`truffle compile`

`truffle migrate`or`truffle migrate --reset` for subsequent runs

`npm start`

The project will open in the browser and metamask will ask you to select an account. Select the account we had imported earlier.
