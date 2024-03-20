# README

This repository contains a simple React application for calculating Fibonacci numbers using a deployed Ethereum smart contract.

## Description

The React application consists of a single component `App` which interacts with the Ethereum blockchain to call the `fib` function of the deployed Fibonacci smart contract.

## Smart Contract

The smart contract is written in Solidity and provides a single function:

- `fib(uint n)`: This function takes a non-negative integer `n` as input and returns the `n`th Fibonacci number as an unsigned integer.

The Fibonacci sequence is defined as follows:

```
F(0) = 0
F(1) = 1
F(n) = F(n-1) + F(n-2) for n > 1
```

## Usage Instructions

1. Clone this repository to your local machine.

2. Install the necessary dependencies by running `npm install`.

3. Start the React application by running `npm start`.

4. Ensure that you have a local Ethereum client running (such as Ganache) or connect to a testnet like Rinkeby.

5. Deploy the Fibonacci smart contract to your chosen Ethereum network.

6. Update the `Fibonacci.json` file with the deployed contract's address and ABI.

7. Interact with the React application by entering a number into the input field and clicking "Submit" to calculate the corresponding Fibonacci number.

## Additional Notes

- Make sure you have MetaMask or another Ethereum wallet installed in your browser to interact with the Ethereum blockchain.

- Ensure that your Ethereum client is synchronized and connected to the correct network.

- This repository is provided for educational and demonstration purposes. It is highly recommended to fully understand the code and the implications of interacting with the Ethereum blockchain before using it in a production environment.

Feel free to explore and experiment with the React application! If you have any questions or issues, feel free to open an issue in this repository.
