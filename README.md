# Lottery Smart Contract 🎰

This is a simple **Lottery Smart Contract** written in Solidity.

## Features
- Only the **manager** can pick a winner.
- Players can participate by sending **0.001 ETH**.
- Winner is selected randomly and gets the entire contract balance.
- After winner selection, the lottery resets.

## How it Works
1. Deploy the contract (manager = deployer).
2. Participants send 0.001 ETH to join.
3. Manager calls `selectWinner()` to randomly select and reward a winner.

## Tech Stack
- Solidity `^0.8.18`
- Remix IDE / Hardhat (for testing & deployment)
- Ethereum blockchain

## License
MIT License
