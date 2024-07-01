# MyToken Project

MyToken is an ERC20 token contract on the Ethereum blockchain, featuring functionalities for minting, transferring, and burning tokens.

## Description

MyToken is a smart contract written in Solidity that implements an ERC20 token. It extends OpenZeppelin's `ERC20` and `Ownable` contracts, providing standard token operations and access control for minting and burning.

## Contract Features

- **Minting Tokens:** Only the owner can mint new tokens.
- **Transferring Tokens:** Users can transfer tokens to others.
- **Burning Tokens:** Users can burn their own tokens.

## Getting Started

### Installing

Clone the repository:
```bash
git clone https://github.com/your-username/MyToken.git
```

## Executing Program
1. Navigate to the project directory:
```bash
cd MyToken
```

2. Install dependecies:
```bash
npm install
```

3. Compile the contracts:
```bash
npx hardhat compile
```

4. Deploy the contract to a network:
```bash
npx hardhat run scripts/deploy.js --network rinkeby
```

5. Interact with the deployed contract using the Hardhat console or Remix IDE.

## Help 
For any issues or questions, contact akdsabilala@mymail.mapua.edu.ph.

## Author
Allen Kyle Sabilala
[@Kycehhh](https://twitter.com/Kycehhh)

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contract Details
- Constructor: Sets up the contract with an initial owner.
- Minting: Enables the owner to mint new tokens.
- Burning: Allows any user to burn their own tokens.
- Ownership: Uses Ownable.sol to restrict certain actions to the owner.
For the complete code, see contracts/MyToken.sol.
