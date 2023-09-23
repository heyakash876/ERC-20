# ERC20 Token
A smart contract that  allows only the owner of the contract to mint tokens and any user is able to burn and transfer token.

## Description

This project is a smart contract which is  written in Solidity. The contract has the following functions :-


* A constructor that specifies the name, symbol, decimal places and initial supply of the tokens.

* A mapping of addresses to balances.

* A mint function that takes an integer parameter of amount. This function then increases the total supply by that number and increases the balance  by the input amount . This function can be used by the owner only as for which I have used require keyword.

* A burn function  will destroy tokens. It has conditionals to make sure the balance of account is greater than or equal to the amount to be burned. It can be used by both the owner and any other users.

* A transfer function which lets user to transfer tokens from one address to another.
  
* It also contains a approve function that will approve a specified user to burn a specified amount.

## Getting Started

### Functionalities

with the 'mintTokens' function you can enter the amount of tokens to be minted.

With the  'burnToken' function you can enter the number of tokens you want to remove from your balance.

with the 'transferTokens' function you can enter the wallet address you want to send tokens to and addd the number of tokens you want to send from your balance.

With 'transfer_from' function you can specify the address you want to send tokens from, with the address you want to send token to.

The 'balance' button is a mapping of the address and the amount of tokens that address contains.

Using 'Name' you can know the name of the token.

Using 'TotalSupply' you can know the total amount of tokens present.

Using 'decimals' you can know the total amount of decimal places present.

Using 'Owner' you can know the address of the owner.

By using 'symbol' you can see the symbol of the token.

With the help of 'approve' function you can approve the address and a amount for some other user.


### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., mint.sol). Copy and paste the code from ERC20.sol file into your file:

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to latest solidity version (or another compatible version), and then click on the "Compile" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the your contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the mintTokens, burnToken function, transferTokens and much more.

## Authors

Akash
email: vermakash876@gmail.com

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
