# NFT Contract on Flow

Project: A sample NFT contract that inherits the NFT implementation contract for the Flow blockchain

## Description

This is a Project Built on Flow, the project defines a unique digital asset with properties name, favorite food, and lucky number. the project also defines a collection resources for managing collection of NFTs, allowing users to mint, withdraw and view their NFTs, the project also defines minter resource which creates new NFTs with specified properties, also the project contains events emitted for contract initialization, NFT withdrawals, and mint.

## Getting Started

### Structure
    - Contracts
        This folder contains the `CryptoPoops.cdc` contract, the contract contains collection storage for storing user collections, also minter resources and events.
        This folder also contains `NonFungibleToken.cdc` contract
    - Scripts
        This folder contains `GetNFTMetadata.cdc` script, which returns the metadata of the nft of the address and id of the nft
    - Transactions
        This folder contains `CreateCollection.cdc` transaction script which takes in the user details like lastname, firstname, address, phone and add to the register dictionary

        This folder also contains `mintNFT.cdc` transaction script which takes in the account, name, favourite food and luckyNumber, creating an nft out of the provided details
        
### Executing program
    - Create a new project on flow playground
    - Under the Contracts folder, create a file `NonFungibleToken.cdc`
    - Copy the content from NonFungibleToken.cdc from the repo to the file 
    - Click on deploy button to deploy the contract
    
    - Under the Contracts folder, create another file `CryptoPoops.cdc`
    - Copy the content from CryptoPoops.cdc from the repo to the file 
    - Click on deploy button to deploy the contract
    
    - Under transactions, create a file `CreateCollection.cdc`
    - Copy the content of CreateCollection.cdc to the file
    - click on send button to create a new collection

    - Under transactions, create a file `mintNFT.cdc`
    - Copy the content of mintNFT.cdc to the file
    - In the form fild, fill in the details and click on send button to create a new nft

    - Under the scripts folder, create a file `GetNFTMetadata.cdc`
    - Copy the content of GetNFTMetadata.cdc from the repo to the file
    - In the form field type the account and id of the nft to get the nft metadata
    - View the metadata in the log

## Authors

Contributors names and contact info

ex. Okeola Mubarak  
ex. [@Mubie_X](https://twitter.com/mubie_X)


## License

This project is licensed under the MIT License 
