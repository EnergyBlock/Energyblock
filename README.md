# BlockChain token

This project was created during the EnergyBlock project - funded by Climate Kic. The idea was to create a P2P prototype marketplace for energy trading, mimicking M2M transactions.

This repository only implements a simple demo, where residents of a building can vote on whether to approve the consumption of the solar panel on their roof. 

The token functionality is not yet implemented in real life, but smart meters are connected.

## Usage

Addresses are hard-coded. To try the demo, you have to initialize both testrpc (`testrpc -m "twelve words seed"`) and Metamask ("Import existing DEN") with the same seed (see `seed.txt`). 

1. First run `truffle compile`, then run `truffle migrate` to deploy the contracts onto your network of choice (default "development").
1. Then run `npm run dev` to build the app and serve it on http://localhost:8080

