# Milestone-1

## Milestone 1 deliverables

1.	Complete MVP UI/UX design.

2.	Fetch the on-chain metadata from Fxhash on Tezos and ArtBlock on Ethereum.

3.	Fetch the market trade data from Fxhash on Tezos, and Opensea on Ethereum.

4.	Basic version development of market smart contracts (including listing, buying, selling, and offer)


## 2.	Fetch the on-chain metadata from Fxhash on Tezos and ArtBlock on Ethereum.

Code relavant to on-chain metadata fetching in Fxhash is included in ./App.js and ./queries/strings/FxQueryStrings. The fetched data is then used in other parts in the website.

Code relavant to on-chain metadata fetching in ArtBlocks is included in ./queries/strings/AbQueryStrings and called in ./App/js. The fetched data is then used in other parts in the website.

There are also other queries included in ./query folder. 

## 3. Fetch the market trade data from Fxhash on Tezos, and Opensea on Ethereum.

Code relavant to market data fetching in Fxhash is included in ./App.js and ./queries/strings/FxQueryStrings. 

Code relavant to market data fetching in Opensea is available in ./App.js and ./queries/OpenseaQuery. 

The fetched data are then conveyed to other components in the project in <App> component and used in other parts in the project.

