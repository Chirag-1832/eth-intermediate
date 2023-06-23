# eth-intermediate
# Errorhandling Smart Contract

This smart contract demonstrates the usage of `require()`, `assert()`, and `revert()` statements in Solidity.

## Description

The AssertionExample contract contains a `divide()` function that performs division of two numbers. It showcases the usage of different assertion statements to enforce conditions and handle exceptional cases.

## Installation

To interact with the smart contract, you'll need the following:

- An Ethereum development environment like Remix or Truffle.
- Solidity compiler (version ^0.8.0).

## Usage

1. Deploy the `AssertionExample` contract to an Ethereum network of your choice.

2. Call the `divide()` function, providing the dividend and divisor as parameters.

   - The `require()` statement ensures that the divisor is not zero. If it is, the transaction reverts with an error message.

   - The `assert()` statement verifies that the dividend is greater than or equal to the divisor. If it's not, the transaction reverts.

   - The `revert()` statement checks if the quotient is greater than 10. If it is, the transaction reverts with an error message.

3. The `divide()` function returns the quotient of the division.

## Authors

Chirag Arora

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
