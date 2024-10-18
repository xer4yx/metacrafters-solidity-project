# metacrafters-solidity-project: TokenGenerator
## Description

`TokenGenerator` is a simple Solidity smart contract that allows users to mint and burn custom tokens. The contract defines a token named **NITROFOX** (NFX) with functionality for tracking balances, minting new tokens, and burning existing tokens. 

### Key Features:
1. **Public Variables**:
   - `TOKEN_NAME`: Holds the name of the token.
   - `TOKEN_ABBREVIATION`: Short form for the token name.
   - `totalSupply`: Tracks the total supply of the token.

2. **Mapping**:
   - A mapping from addresses to balances to track each user's token holdings.

3. **Minting**:
   - The `mint` function allows the creation of new tokens, increasing the total supply and the balance of the specified address.

4. **Burning**:
   - The `burn` function allows the destruction of tokens, decreasing the total supply and the balance of the specified address. It ensures the balance of the sender is sufficient before burning.

## Getting Started

To get started with this contract, you will need the following:
- **Solidity Compiler**: Version ^0.8.26 or above.
- **Remix IDE**: An online Solidity development environment.

## Executing Program

You can execute the program by following these steps:

1. Visit [Remix Ethereum IDE](https://remix.ethereum.org).
2. Create a new Solidity file (e.g., `TokenGenerator.sol`).
3. Copy and paste the Solidity code from this repository into the new file.
4. Compile the contract using the Solidity compiler version ^0.8.26.
5. Deploy the contract using the provided `Deploy & Run Transactions` tab.
6. Once deployed, you can interact with the contract by:
   - Calling the `mint` function to mint new tokens.
   - Calling the `burn` function to burn existing tokens.

## Author

[Angelo M. Bicomong](https://github.com/xer4yx)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
