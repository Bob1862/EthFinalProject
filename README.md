# CREATING A NFT_TOKEN

This solidity program "myToken" is a simple program which imitates the token creation (minting and burning coins) process on my local Blockchain.

## Description

The program consists of:

1.3 public state variables which will provide the token name, token abbreviation and total supply for my token.
2.Minting function "mintToken()" which will take address and value as parameters and then it increases the total supply by that number and increases the balance of the address by that amount.
3.Burn function "burnToken()" which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
4.This burn function will also check the amount to be burned must be less than or equal to the balance present in that address.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/. Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the "myToken" file in my repo with a .sol extension. Now compile and deploy the program.

KINDLY REFER TO PROJECT2 FILE TO SEE THE CODE

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile  project2.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "myToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the sayHello function. Click on the "myToken" contract in the left-hand sidebar, and then click on the "mint" and "burn" function. Finally, click on the "transact" button to execute the function and retrieve the the output in the resultant token that we got after minting and burning some of the token.

## Authors

Metacrafter Chris  
@ASHWANI SINGH
@ash995656@gmail.com


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
