# NFT Minter
A frontend that uses a contract to deploy NFTs.

## Prereqs
- Metamask Wallet or equivalent
- Moralis Account
- Nodejs and reactjs

## Setup instructions
1. First, clone this repo:
```
git clone https://github.com/solarsailorneo/minterNFT.git
```
2. You will need to get a Moralis account and spin up a server. I used the Ropsten testnet for this project, but any testnet will do.
3. Once you spin up the server you will need to obtain the *server URL*, *application ID*, and *CLI API Secret*, create an `.env` file in the `frontend` directory, and place the values in the file. The flags are: `REACT_APP_MORALIS_SERVER_URL`, `REACT_APP_MORALIS_APPLICATION_ID`, and `REACT_APP_MORALIS_SECRET` respectively.

## How to use
1. Connect your wallet via metamask.
2. Select the image file that you want to include in your NFT.
3. Click the `Mint Now!` icon to mint your NFT. 
