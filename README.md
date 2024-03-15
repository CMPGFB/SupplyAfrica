# SupplyAfrica

SupplyAfrica is a Clarity smart contract cultivated by Christopher Perceptions and presented at W3Africa 2024 as a decentralized framework for supply chain management. 

It's designed to facilitate the tracking and management of items across Africa. It allows companies to register items, update their statuses, and maintain a history of these statuses over time. Developed with transparency, efficiency, and scalability in mind, SupplyAfrica aims to support mass adoption of decentralized systems within supply chain management applications.

# Smart Contracts

- Item Registration: Companies can register items, assigning them a unique ID and initial status.

- Status Updates: Item owners can update the status of their items, with each update being recorded in the item's history.

- History Tracking: Each item has a history of status updates, allowing for traceability and accountability.

- Access Control: Only the item's registered owner can update its status, ensuring security and integrity.

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

Registering an Item
Call the register-item function with the company's principal and the initial status of the item.

Updating Item Status
Call the update-item-status function with the item's ID and the new status.

Retrieving Item Information
Call the get-item-information function with the item's ID to retrieve its current status and history.

# Contributing

SupplyAfrica is cultivated with Africa in mind, so contributors are always welcomed. 

# License

This project is open source and available under the MIT License.

# Disclaimer

The SupplyAfrica smart contract are provided as-is, without any warranties or guarantees of any kind. The author of this repository is not responsible for any potential issues or losses that may arise from the use or deployment of these contracts. 
