Source: https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/

Setup Steps:
```sh
npm i
cp .env.sample .env # replace vars
cd contracts
```
Test Steps:
```sh
npx hardhat compile
npx hardhat --network ropsten run scripts/deploy.js
# https://ropsten.etherscan.io/address/0x3D30Fc59202a2Ed5303a5a114d550D891e9daB0c

```


Resources:
1. https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key
1. https://hardhat.org/config/

Logs To Savour
```sh
The hash of your transaction is:  0x06152fb258f1e8b568e61674f9c09b3a5ac774647c06d9bc501e28886a845e19 
Check Alchemy's Mempool to view the status of your transaction!
```
