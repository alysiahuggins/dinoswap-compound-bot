# Description
Watch my Youtube vid for more instructions on how to use this repository.

This code is used to auto compound your DINO tokens that you earn from the DINO/USDC farm on Dinoswap into the Jurassic DINO pool. The tokens are auto compounded every four minutes.

Dinoswap is a yield farm on the polygon network.


<br>

# Disclaimer
You can use this code and extend it for your own personal use.
This is not production ready code.
Please be very careful with your private key and never push it to a public repository. It's advised that you use an account that doesn't have all your funds attached to it. 

<br>

# Prerequisites
- Node JS installed `brew install node`
- You have a DINO/USDC LP deposited to the Dinoswap Yield Farm (dinoswap.exchange)
- You have MATIC tokens in your account to pay for gas fees 

<br>

# Steps to run
1. navigate to the folder in your terminal
2. run `npm install`
3. copy env_sample to a new file (.env) and enter your Polygon RPC URL and the private key of the account that currently has its LP in the DINO/USDC farm `cp env_sample .env`
4. make sure that the `.env` file is in the `.gitignore` file
5. Now you're ready to run the auto compounding bot `node index`

<br>

# DINOSWAP Smart Contracts on Polygon
``DINO/USDC Farm - 0x1948abc5400aa1d72223882958da3bec643fb4e5``
``DINO Jurassic Pool - 0x52e7b0c6fb33d3d404b07006b006c8a8d6049c55``
