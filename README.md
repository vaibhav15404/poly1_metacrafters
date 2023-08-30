## Building with polygon bridge- Module-1

This is the first project in Polygon-Advance, in this project, I have to deploy an NFT collection on the Ethereum blockchain, Map the collection to Polygon, and Transfer assets over via the Polygon Bridge.

1. create 5 nfts,and upload it on your pinata cloud

2. write a contract code

3. write a script for deployment,then run deploy.js using the following command - "npx hardhat run scripts/deploy.js --network goerli" the script will deploy the contract
    After deploying the address will generate. So, copy that address into contarctAddress.js(stored in metadata folder) and also in batchMint.js(stored in scripts folder) and in nfts address in approvedDeposit.js.

4. "npx hardhat run scripts/batchMint.js --network goerli" -The script will mint the 5 NFTs and assign them to our address.

5. Approve and Deposit NFTs to Polygon Mumbai "npx hardhat run scripts/approvedDeposit.js --network goerli"
Run the following commands to approve and deposit the minted NFTs from Ethereum to the Polygon Mumbai network using the FxPortal Bridge:


Author
Vaibhav Rajput

License
This project is licensed under the MIT License.
