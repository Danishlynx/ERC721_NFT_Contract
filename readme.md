# NFTopenSea - TrumpNFT (TNFT) Smart Contract

NFTopenSea is a Solidity smart contract designed to facilitate the minting and management of NFTs (Non-Fungible Tokens) represented by the TrumpNFT (TNFT) token. This contract leverages the Ethereum blockchain and is equipped with features for creating and owning limited edition NFTs.

## Features and Functionality
1. Minting NFTs
The contract allows users to mint NFTs by invoking the mint function. Minting an NFT generates a unique token associated with a specific identifier. Each NFT created using this contract is owned by the Ethereum address that initiates the minting process. To ensure controlled scarcity, a maximum supply of 10 NFTs is enforced. Users cannot mint more NFTs once this limit is reached.

2. Contract Initialization
The contract is initialized with the name "TrumpNFT" and the symbol "TNFT" for the NFTs it creates.
3. Metadata URI
The contract includes functionality for specifying a base URI for the metadata associated with each NFT. This base URI is used to retrieve detailed information about an NFT, such as its name, description, and attributes.

The base URI is set to "ipfs://QmSquBiBsxx2XQeRrDZ8uWtVJrEbYLnbhXd8YkKvctBqFA/," and the token ID is appended to it to access the specific metadata for each NFT.

## Getting Started
To use this smart contract:

Deploy the contract to the Ethereum blockchain, making it accessible to users.

Users can mint NFTs using the mint function, taking care not to exceed the maximum supply limit.

To display NFT information on popular marketplaces like OpenSea, users should provide the appropriate metadata URI constructed using the base URI and the token ID.

## These NFTs can be minted from etherscan

## License
This smart contract is distributed under the terms of the GPL-3.0 License.

Note: While this contract serves educational purposes and demonstrates NFT creation, users should exercise caution when working with Ethereum smart contracts and cryptocurrency assets.

Project Implementation:

![Screenshot 2023-08-27 091701](https://github.com/Danishlynx/metana_bootcamp/assets/69537135/34883a79-b717-4aa8-bd9e-cf938d5b74f2)

![Screenshot 2023-08-27 091735](https://github.com/Danishlynx/metana_bootcamp/assets/69537135/37bea47a-d519-4663-9d38-3a38ce60c0e7)


![Screenshot 2023-08-27 091742](https://github.com/Danishlynx/metana_bootcamp/assets/69537135/ade8d748-ed86-4a65-9d40-c1f7c44e56a9)


![Screenshot 2023-08-27 091757](https://github.com/Danishlynx/metana_bootcamp/assets/69537135/2aa0fd50-b39b-48c1-b48e-70d6d1443922)


![Screenshot 2023-08-27 093224](https://github.com/Danishlynx/metana_bootcamp/assets/69537135/0fa45620-9fac-4bfa-a206-451d85a6c67a)


![Screenshot 2023-08-27 095847](https://github.com/Danishlynx/metana_bootcamp/assets/69537135/4e1d822f-601a-4eb3-b7b0-6a820370c179)



![Screenshot 2023-08-27 100708](https://github.com/Danishlynx/metana_bootcamp/assets/69537135/46c94c05-4dd9-4e55-ac9f-de11efd32a1c)
