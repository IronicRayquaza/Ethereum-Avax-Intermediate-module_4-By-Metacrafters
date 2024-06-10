1. Setup your .env file with your Metamask account.

2. Install following dependacy:

      npm install --save-dev hardhat  

      npm install @openzeppelin/contracts

3. Setup your Smart Contract:
   
     run the Hardhat node: npx hardhat node

     deploy the contract on Fuji C chain: npx hardhat run scripts/deploy.js --network fuji

     open smart contract on Remix: remixd -s <your_folder_location> -u https://remix.ethereum.org

4. Test on a testnet.


loom video for verification: https://www.loom.com/share/32651e04139c4542bf97170b797c32fd?sid=55fb7db1-aac8-4881-badb-a6214d23a55d
