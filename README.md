# NFT Minter
This program uses React as our frontend framework that connects Metamask to your frontend project, call smart contract methods from your frontend, and sign transactions using Metamask.


## Setting up
Input the contractAddress obtained from mySpecialAsset into nftMinter/src/utils/interect.js. 

```
const contractAddress = "0x785aA57c0619f5f6651CE72d9c31E5D282485fe4";
```

To update the Pinata Key and Secret Key, edit the file in nftMinter/.env.

```
REACT_APP_PINATA_KEY = cb8239994fa9d8825f7f
REACT_APP_PINATA_SECRET = 4613a3af87a118327147a4c7d367f26c7625254410107c2781ce0c39da7845af
```

Once addresses and keys are updated, run the command `npm start` to start localhost:3000.
