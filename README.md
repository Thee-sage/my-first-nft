Project Name: MY-FIRST-NFT
INTRODUCTION: It is one of my initial projects a ERC 721 token based upon open zepplin source code and some other resources, here are the steps how it is created

STEP 1: Choose an open Source Code like open Zepplin code Wizard, free to use and secured as a beginner you won't be able to make a smart contract with security levels like these on your own.
STEP 2: Read through the documentation and learn the basics and then go for ERC 721 contract from there and then choose how you want your nft to be you want it to be mintable and Enumerable and ownable and then proceed to copy it.
STEP 3: Now open Remix IDE(integrated development environment) and make a new file and copy paste the source code into your new file which could be named anything
and further modify it by naming the contract itself and also setting up a limit here is the code for that "uint256 MAX_SUPPLY = 10000;" after this you have to make a message to show that you have reached the limit of minting" require( tokenId >= 10000, "not enough for you");".
STEP 4: COMPILE!
STEP 5: Now log into a ecosystem like Alchemy and create your first app but with test ethers not the real ones and choose the chain of deployment which is ethereum goerli testnet.
STEP 6: Now copy the rpc URL from your project which would be in the key section of your app initialising with https, and copy it.
STEP 7: Make a metamask Account and add a new network with name "Alchemy Goerli" and choose the chain id for goerli which is 4 and and the RPC URL and add the network also add some testnet ethers from alchemy faucet.
STEP 8: Deploy your smart contract and dont use the ethers provided by remix use "injected provider" connect your metamask and deploy.
STEP 9: Create Metadata which you can get from open sea metadata standards(https://docs.opensea.io/docs/metadata-standards) edit it according to your way and now you have the metadata for your nft.
STEP 10: Now log in to filebase and create a new bucket add now upload the image that you want to be your first nft and upload the metadata that you have downloaded and upload now take the ipfs cid from the overview of ipfs metadata and just go to your remix ide and go to the safe mint function of your deployed contract and write "ipfs://(whatever your ipfs cid is)" and add your address above as you want to mint your nft and a metamask notification would pop up and there you go approve it and you have finally minted your own nft! Now you have to see if it is properly uploaded or not so go to opensea.testnets log in with your metamask and you will be able to see your first nft.
CONGRATULATIONS!
