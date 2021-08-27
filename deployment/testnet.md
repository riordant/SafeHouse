# Deploy

- Go to https://remix-alpha.ethereum.org/

- Change network to BSC Testnet in Metamask (see here for importing BSC Testnet into MetaMask: https://docs.binance.org/smart-chain/wallet/metamask.html)

- Change to address that has Testnet BNB in Metamask (Get free Testnet BNB here: https://testnet.binance.org/faucet-smart)

- Create new file called `SafeHouse.sol`

- Copy and paste `contracts/SafeHouse.sol` into this file

- in the left sidebar go to SOLIDITY COMPILER

- Change to `v0.6.6`

- Check "Enable optimization". Leave "runs" at 200

- Click "Compile"

- in the left sidebar go to DEPLOY & RUN TRANSACTIONS

- Change ENVIRONMENT to `Injected Web3`

- Change ACCOUNT to the same account in MetaMask

- Change CONTRACT to `SafeHouse - SafeHouse.sol`

- Beside "Deploy", click the box, and type `1`.

- Click Deploy

- Wait for deployment on BSC Testnet.

  
  

# Verify

- Contract address is shown in Remix in the window on the left side. Copy the deployed address to clipboard. We'll call this `ADDRESS`.

- go to https://testnet.bscscan.io/address/{ADDRESS}

- Click Contract > Verify & Publish

- `Please select Compiler Type` > Solidity (Single File)

- `Please select Compiler Version` > 0.6.6

- `Please select Open Source License Type` > No License (None)

- Continue

- Optimization > Yes

- Paste in `SafeHouse.sol`

- Complete Capctha, done.



# Add Liquidity

- go to https://pancake.kiemtienonline360.com/#/add/BNB/{ADDRESS} (PancakeSwap testnet that works). 

- Give it up to 10 seconds to load the token contract.

- Click "Connect" in the top right, select your deployment address

- Input BNB, and amount of tokens to add to liquidity (BNB amount/token amount is the price per token in BNB)

- Click "Approve", and then "Supply".