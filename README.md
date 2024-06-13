# Project_eth_beg
This is my first smart contract using solidity for the metacrafter program.
The `MyToken` contract is a simple Solidity smart contract for creating and managing a basic token system on the Ethereum blockchain. It specifies the Solidity compiler version 0.8.26 and uses the MIT License. The contract includes three public variables: `tokenName` ("FIRST"), `tokenAbbr` ("MTA"), and `totalSupply` (initially 0), which track the token's name, abbreviation, and total supply.

A mapping called `balances` tracks each address's token balance. The `mint` function allows for the creation of new tokens by increasing the `totalSupply` and updating the specified address's balance. Conversely, the `burn` function allows for token destruction by reducing the `totalSupply` and the balance of the specified address, provided the address has sufficient tokens.

In essence, `MyToken` provides a straightforward framework for minting and burning tokens, making it a foundational example of token management on Ethereum.
