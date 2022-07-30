# rarity-ranking-nft-moralis

App made using Moralis API to fetch data on-chain. Ethereum NFT project is displayed and sorted by rarity.
In this example: Bored Ape Yacht Club

## App

This App is divided by: frontend and backend.

On the backend folder there's a simple main.js file that fetches all the data from the Ethereum Blockchain. Manages the data to get the info needed. And then uploades it into Moralis Database.

On the frontend folder you'll find a React template by Moralis to dispatch all the data from the database mentioned before.

To work on this project you'll need:

- Moralis Web3 account, create an App on Ethereum and get the credentials
- Fill the credentials into .env file, which you'll need to create out of .env.template file. **Both in frontend and backend folder**.
- `npm install` both frontend and backend
- To fill the database, you'll need to `node main.js` on the backend folder - this will take a while, you can sit and take a coffee
- After filling the database, you can run the client side by `npm run start` on the frontend folder 