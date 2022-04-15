# Project submission for BlockChain Module

M.Sc. Cloud Computing Semester one project demonstrating the understanding of blockchain concepts
 
## Project Title

Ethereum ERC20 Token Distribution

## Project Description

Code is implemented to distribute ERC20 token by invoking the contract deployed in the ethereum. For this project tokes are distributed to Accounts mentioned in accountstodistribute.txt file.

## Technologies used


NodeJS 16.14.0  
Solidity  
Javascript  

## How to Run?

1) Use any programming editor either Sublime Text or Microsoft Visual Studio Code.  
2) Clone the repository using following git command

```bash
git clone https://github.com/x21146331/x21146331_ERC20XTKToken.git
```
3) Configure the .env file addresses as per the following directions.  
   INFURA_TOKEN ([Infura](https://infura.io/))- Supply the api end point for the ethereum test network.
  
    CONTRACT_ADDRESS([Remix](https://remix.ethereum.org/))- Supply the contract id which is generated from deploying in ethereum.

    OWNER_ADDRESS- Supply metamask test network account address.  
 
    SUPER_SECRET_PRIVATE_KEY- Supply from the metamask account.

4) Execute the following command to install all the dependencies through nope package manager(npm).

```bash
npm install
```
5) Include the destination wallet addresses in accountstodistribute.txt file.

5) Invoke the distribute.js for by running the following command.


```bash
node ./distribute.js
```
