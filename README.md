
---

# DegenToken

DegenToken is an ERC-20 token smart contract developed for Degen Gaming on the Avalanche blockchain. The token allows players to earn rewards in the game and exchange them for in-game store items. The contract follows the ERC-20 standard and includes additional functionalities to support the reward program and item redemption.

## Functionality

The DegenToken contract provides the following functionalities:

1. Minting new tokens: The contract owner can mint new tokens and assign them to specific addresses.
2. Burning tokens: Any token holder can burn their tokens if they no longer need them.
3. Transferring tokens: Players can transfer their tokens to other addresses.
4. Redeeming items: Players can redeem their tokens for items in the in-game store.
5. Checking token balance: Players can check their token balance at any time.
6. Adding new items: The contract owner can add new items to the in-game store.
7. Viewing items: Players can view the available items and their details.

## Getting Started

To deploy and interact with the DegenToken contract, follow these steps:

1. Deploy the contract on the Avalanche blockchain using Remix or your preferred development environment.
2. Set the name and symbol for the token during contract deployment.
3. Mint initial tokens to the desired addresses using the `mint` function.
4. Add items to the in-game store using the `insertItem` function.
5. Players can transfer, burn, and redeem tokens as needed.
6. Players can view available items and their details using the `showItems` function.
7. Players can redeem items by their ID using the `redeemItem` function.

## License

This contract is licensed under the MIT License. SPDX-License-Identifier: MIT.

---
