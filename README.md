# Smart Contract Lottery

This project is a decentralized lottery/raffle application implemented using Solidity and Foundry. This project was developed following the Cyfrin Updraft online course.
Cyfrin repo: https://github.com/Cyfrin/foundry-smart-contract-lottery-cu

## How It Works

1. Users enter the lottery by sending ETH to the smart contract, paying a predefined minimum entry fee.
2. After a specified amount of time, a winner is selected randomly from the list of participants.
3. The winner receives the entire accumulated prize pool.

## Setup and Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/sergipastor/smart-contract-lottery-cyfrin.git
   cd smart-contract-lottery-cyfrin
   ```

2. **Install Dependencies:**

   ```bash
   make install
   ```

3. **Compile Contracts:**

   ```bash
   make build
   ```

4. **Run Tests:**

   ```bash
   make test
   ```
