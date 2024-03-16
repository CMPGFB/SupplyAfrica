# SupplyAfrica

SupplyAfrica is a Clarity smart contract cultivated by Christopher Perceptions and presented at W3Africa 2024 as a decentralized framework for supply chain management for Africa. 

It's designed to facilitate the tracking and management of items across Africa. It allows companies to register items with an initial status, update the status of owned items, and retrieve item information based on item IDs. 

SupplyAfrica aims to support mass adoption of decentralized systems within supply chain management.

# Deployment 

Explorer Link: https://explorer.hiro.so/txid/SP2HJVJQS0TRBTQ1WAWWN9H9W2HKGDZ7H5EZCEAQC.supplyafrica?chain=mainnet

# Functions

- Item Registration: Register items with a unique ID and an initial status.

- Status Updates: Update the status of an item. Only the item's owner can perform this action.

- Item Information Retrieval: Retrieve the owner and current status of an item by its ID.

# Requirements

Stacks Blockchain API (for deployment and interaction)

Clarity CLI (for local testing and development)

# Installation

Clone this repository to your local machine using:

<pre>
git clone https://github.com/cmpgfb/supplyafrica.git
</pre>

Navigate to the project directory:

<pre>
cd supplyafrica
</pre>

# Deploy

To deploy the SupplyAfrica contract to the Stacks testnet or mainnet, follow these steps:

Ensure your Stacks account has sufficient STX for the contract deployment transaction.

Use Clarinet to deploy the contract, specifying your account as the sender.

<pre>
clarinet deploy --contract supplyafrica.clar --network [testnet|mainnet]
</pre>

# Usage

Registering an Item: Call the register-item function with the desired initial status of the item. The function returns a unique item ID.

Updating an Item's Status: Call the update-item-status function with the item's ID and the new status. Note: Only the item's owner can update its status.

Retrieving Item Information: Call the get-item-information function with the item's ID to retrieve its current status and owner.

# Contributing

SupplyAfrica is cultivated with Africa in mind, so contributors are always welcomed. 

# License

This project is open source and available under the MIT License.

# Disclaimer

The SupplyAfrica smart contract are provided as-is, without any warranties or guarantees of any kind. The author of this repository is not responsible for any potential issues or losses that may arise from the use or deployment of these contracts. 
