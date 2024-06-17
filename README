# FajardoContract.sol
This smart contract leverages the OpenZeppelin ERC20 implementation to ensure security and compliance with the ERC20 standard while adding custom functionalities like minting, burning, and ownership restrictions.

# Description
This Solidity code defines a smart contract named MyToken, which is an ERC20 token with additional functionalities, using the OpenZeppelin library for standardized implementations.

# Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:

// SPDX-License-Identifier: Apache-2.0
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    address public tokenOwner;

    constructor(string memory tokenName, string memory tokenSymbol, uint256 initialAmount) ERC20(tokenName, tokenSymbol) {
        _mint(msg.sender, initialAmount);
        tokenOwner = msg.sender;
    }


## Authors

Metacrafter Anthonette

## License
This project is licensed under the MIT License - see the LICENSE.md file for details
    
