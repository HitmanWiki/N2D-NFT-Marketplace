
<a href="http://youtube.a3b.io" target="_blank"><img src="https://github.com/net2devcrypto/N2D-NFT-Marketplace/blob/main/n2DMarket.png" width="260" height="50"><h2>Multi-Chain NFT Marketplace</h2></a>
##
🚀👩‍🚀This repo contains all the files to follow along and implement a MultiChain NFT MarketPlace! Be sure to watch my Youtube tutorials so you can learn and follow along!

** THE FILES ATTACHED TO THIS REPO ARE FOR EDUCATIONAL PURPOSES ONLY **

** NOT FINANCIAL ADVISE **

** USE IT AT YOUR OWN RISK** **I'M NOT RESPONSIBLE FOR ANY USE, ISSUES ETC.. **

Please follow instructions for the video tutorial you are watching.

## Part-1 Hardhat and EthersJS

Click for video:

<a href="https://www.youtube.com/watch?v=wxeA8NKPNUA&t=539s" target="_blank"><img src="https://github.com/net2devcrypto/misc/blob/main/ytlogo2.png" width="150" height="40"></a> 

Steps:

1-Create an new NextJS app:

```shell
npx create-next-app n2dmarket
```

2- Install hardhat in the n2dmarket project folder.

```shell
npm i hardhat
```

3- Create a hardhat environment.

```shell
npx hardhat
```

4- Refer to the Hardhat and EthersJS knowledge base and 
practice some info gathering using the hardhat console:

```shell
npx hardhat console
```

Hardhat Knowledge Base : https://hardhat.org/tutorial

EthersJS Knowledge Base: https://docs.ethers.io/v5/

## Part-2 NFT Market Resell Smart Contract

Click for video:

<a href="https://www.youtube.com/watch?v=60Babg2TJtU" target="_blank"><img src="https://github.com/net2devcrypto/misc/blob/main/ytlogo2.png" width="150" height="40"></a> 


1-Retrieve the NFT Collection Smart Contract Address.

2-Deploy the NFT Market Resell Smart Contract located in Part2 Folder.

Add the NFT Collection Address when deploying the smart contract.

## Part-3 Deploy a NextJS WebFront End

Click for video:

<a href="https://www.youtube.com/watch?v=TTSyNZCifLs&t=1837s" target="_blank"><img src="https://github.com/net2devcrypto/misc/blob/main/ytlogo2.png" width="150" height="40"></a> 

Steps:

1- Navigate to your n2dmarket project folder and install the remaining dependencies:

```shell
npm i --save-dev "@types/react"

npm i axios @nextui-org/react sf-font

npm i simple-crypto-js web3modal

npm i @metamask/detect-provider

npm i ipfs-http-client

npm i web3

npm i --save-dev @types/canvas-confetti
```

2- Proceed to replace the files in your n2dmarket folder with each respective

file attached in the Part-3 Folder, Add the "engine" folder to the project root folder.


3- Deploy your test NFT Collection and NFT Market Resell Smart Contracts (refer to Part2 Vid)

and go to /engine/configuration and update the values accordingly:

```shell

export var hhresell = "YOUR NFT RESELL MARKET SMART CONTRACT";

export var hhnftcol = "YOUR NFT COLLECTION SMART CONTRACT";

var hhrpc = "YOUR MAINNET OR TESTNET RPC ADDRESS";
```

List of RPC Address to use depending on which testnet the contracts have been deployed:

Polygon Mumbai: https://matic-mumbai.chainstacklabs.com

BSC Testnet: https://data-seed-prebsc-1-s3.binance.org:8545

ETH Goerli: https://rpc.ankr.com/eth_goerli

CTRL + S to save configs

Run the web server and validate:

```shell
npm run dev
```

Watch part 3 vid for more details.

## Part-4 Relist and Buy NFTs!

Click for video:

<a href="https://www.youtube.com/watch?v=1QP6UYZc8fU&t=2155s" target="_blank"><img src="https://github.com/net2devcrypto/misc/blob/main/ytlogo2.png" width="150" height="40"></a> 

Steps:

1- New changes have been performed on the Resell SmartContract.
Redeploy it on your favorite testnet and save the address.

Contract link: 

https://github.com/net2devcrypto/N2D-NFT-Marketplace/tree/main/Part2-NFT-Market-Resell-Contract

2- Install NFT Carousel Dependency:

```shell
npm i --save-dev react-multi-carousel
```

3- Proceed to replace the files in your market project folder with each respective

file attached in the Part-4 Folder, Replace "engine" and "public" folder with all files as well.


4- Obtain your Resell Smart Contract Owner Wallet Private Key. (Wallet used to deploy contract)

Go to /engine/configuration and update the values accordingly:

Replace with your Private key in "hhraw":

```shell
const hhraw = "0xREPLACEWITHPRIVATEKEY";
```

Add your smart contract addresses here:

```shell
export var hhresell = "YOUR NFT RESELL MARKET SMART CONTRACT";

export var hhnftcol = "YOUR NFT COLLECTION SMART CONTRACT";

var hhrpc = "REPLACE WITH THE TESTNET RPC";
```

CTRL + S to save configs

Run the web server and validate:

```shell
npm run dev
```
Watch part 4 vid for more details.

## Part-5 Create The NFT Marketplace Contract and App to upload Art and mint NFTs.

Click for video:

<a href="https://www.youtube.com/watch?v=60Babg2TJtU" target="_blank"><img src="https://github.com/net2devcrypto/misc/blob/main/ytlogo2.png" width="150" height="40"></a> 


1-Deploy the Marketplace Contract to sell created NFTs located in Part5 Folder repo. Copy the contract address.

2-Deploy the NFT Smart Contract to create NFTs located in Part5 Folder, add the NFT Market smart contract to sell created NFTs when deploying and copy the contract address once deployed.

3- Go to /engine/configuration and add the additional contracts accordingly:

```shell

export var hhnft = "YOUR CREATE NFT SMART CONTRACT";

export var hhmarket = "YOUR SELL CREATED NFT MARKETPLACE SMART CONTRACT";

```

4- From Part5 Folder, Proceed to add the NFT and Market ABI files to the engine folder. Proceed to replace the files in your project with the ones provided in the Part5 folder. Test and practice. Time to learn more! 

View Part 5 video for more info. 


