# Deploy

- Go to https://remix-alpha.ethereum.org/

- Change network to BSC in Metamask

- Change to address that has BNB in Metamask

- Create new file called `SafeHouse.sol`

- Copy and paste `contracts/SafeHouse.sol` into this file

- in the left sidebar go to SOLIDITY COMPILER

- Change to `v0.6.6`

- Check "Enable optimization". Leave "runs" at 200

- Click "Compile"

- in the left sidebar go to DEPLOY & RUN TRANSACTIONS

- Change ENVIRONMENT to Injected Web3

- Change ACCOUNT to the same account in MetaMask

- Change CONTRACT to `SafeHouse - SafeHouse.sol`

- Click Deploy

- Wait for deployment on BSC.

  
  

# Verify

- copy deployed address to clipboard

- go to https://bscscan.io/address/{ADDRESS}

- Click Contract > Verify & Publish

- `Please select Compiler Type` > Solidity (Single File)

- `Please select Compiler Version` > 0.6.6

- `Please select Open Source License Type` > No License (None)

- Continue

- Optimization > Yes

- Paste in `SafeHouse.sol`

- Complete Capctha, done.

# Add Liquidity

- copy deployed address to clipboard

- go to https://bscscan.io/address/{ADDRESS}

- Click Contract > Verify & Publish

- `Please select Compiler Type` > Solidity (Single File)

- `Please select Compiler Version` > 0.6.6

- `Please select Open Source License Type` > No License (None)

- Continue

- Optimization > Yes

- Paste in `SafeHouse.sol`

- Complete Capctha, done.
