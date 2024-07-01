Setup your .env file with your Metamask account.

Install all dependancies by using:
```shell
npm install
```

Install some important dependancy:
```shell
npm install remixd or npm install -g @remix-project/remixd --force
npm install --save-dev hardhat  
npm install @openzeppelin/contracts
```
      
Setup your Smart Contract and deploy using following commands:
```shell
#run the Hardhat node
npx hardhat node

#deploy the contract on Fuji C chain
npx hardhat run scripts/deploy.js --network fuji

#open smart contract on Remix
remixd -s <your_folder_location> -u https://remix.ethereum.org
```

Test on a testnet.

Note: if remixd gives error run powershell as admin and run Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser 

loom video for verification: https://www.loom.com/share/e9c43e3b42574379a2802912a4ae9978?sid=eabf0172-720d-433d-930d-cb6a5414d2b6
