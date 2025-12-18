# DApp

This repository contains the source code for our DApp, which combines a Python-based web interface with the Solidity smart contracts deployed on the Sepolia test network.

## Repository Contents

- `/app.py`, `/templates/`, `/static/`  
  Flask-based web interface and routing logic.
- `/user.db` SQLite database used to store user logs.
- `/requirements.txt` Python dependencies for running the application.

## Smart Contract Code

The Solidity smart contracts used in this project is available here:

- Contract source (Gist): 
    - `deposit_money.sol`: 
    https://gist.github.com/Odile-Rothbart/71423d31ac05a31114295c8dd31f962a#file-contracts-6106-deposit_money-sol
    - `transfer_money.sol`: 
    https://gist.github.com/Odile-Rothbart/7fce8273f4eb40a632a720a796a3c2ff#file-contracts-6106-transfer_money-sol

The contracts are deployed on the Sepolia Ethereum test network.