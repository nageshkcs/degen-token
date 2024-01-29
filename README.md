# Book Subscription Smart Contract

This is a Solidity smart contract for a book subscription service called `BookSubscription`. It allows users to subscribe to different types of books using a custom ERC20 token called `DEGEN` (DGN). Users can purchase tokens, redeem books, transfer tokens, and destroy tokens if needed. The contract is implemented with some basic functionalities like token minting, burning, and ownership control.

## Overview

The `BookSubscription` contract provides the following functionalities:

1. **Token Minting**: The contract owner can mint `DEGEN` tokens and assign them to specific addresses.

2. **Token Burning**: Users can destroy a certain amount of their tokens.

3. **Book Redemption**: Users can redeem books by exchanging a certain amount of tokens. Two types of books are available: `classmate_junior` and `classmate_senior`.

4. **Token Transfer**: Users can transfer their tokens to other addresses.

## Getting Started

To use the `BookSubscription` contract:

1. Deploy the contract by providing the initial owner's address.

2. Mint some initial tokens to start the token economy.

3. Users can interact with the contract by:

   - Purchasing tokens from exchanges or other users.
   - Redeeming books by calling the `redeemBook` function.
   - Transferring tokens to other users using the `transferTokens` function.
   - Destroying tokens if needed using the `BurnTokens` function.

## Prerequisites

- Solidity compiler version 0.8.0 or higher.
- OpenZeppelin contracts for ERC20 token and Ownable functionalities.

## Deployment

Deploy the contract on a compatible Ethereum Virtual Machine (EVM) using tools like Remix, Truffle, or Hardhat. Make sure to provide the initial owner's address during deployment.

## Usage

1. **Mint Tokens**: The owner can mint tokens by calling the `mintTokens` function, specifying the recipient's address and the amount of tokens to mint.

2. **Redeem Books**: Users can redeem books by calling the `redeemBook` function, providing the book number they want to redeem.

3. **Transfer Tokens**: Users can transfer tokens to other addresses by calling the `transferTokens` function, specifying the recipient's address and the amount of tokens to transfer.

4. **Destroy Tokens**: Users can destroy a certain amount of their tokens by calling the `BurnTokens` function.

## License

This contract is licensed under the MIT License.

```
// SPDX-License-Identifier: MIT
```
## Author 

Nagesh K C 

nageshkc02@gmail.com
