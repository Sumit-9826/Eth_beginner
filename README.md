**#Smart Contract for MyToken**

A basic Solidity smart contract for a token called "Sumit" with the symbol "SK" can be found in this repository. The contract maintains balances for various addresses and permits token minting and burning.

## Contract Information

- **Token Symbol**: SK 
- **Token Name**: Sumit
- **Total Supply**: Starting at 0

## Features

- Minting tokens: This adds more tokens to the total supply and credits the designated address with them.
- Burning tokens: If the address has enough tokens, this reduces the total supply and debits the designated address.

## Functions

### Open Variables

- {string public tokenName}: The token's name.
- {string public tokenSymbol}: The token's symbol.
- {uint256 public totalSupply}: The token's total supply.

### Mapping

A mapping that maintains track of the balance for each address is `mapping(address => uint256) public balances}.

### Mint Function - 

Tokens can be created and assigned to a specific address using the `mint` function. As a result, the recipient address's balance and the total number of tokens available increase.

### Burn Function: 

Using the burn function, tokens from a given address can be destroyed. Assuming the holder has sufficient tokens to burn, this reduces both the total supply of tokens and the balance in their address.

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at [Remix](https://remix.ethereum.org/).

#Author
Sumit Kumar

#License
This project is licensed under the MIT License.


