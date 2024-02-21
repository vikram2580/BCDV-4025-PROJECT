## Requirements
Please ensure you've got the required tools on your local machine or in a virtual machine -- To check, run ./check.sh

## Project Description
We're creating digital trading cards on a blockchain. These cards are like unique, collectible items, similar to non-fungible tokens (NFTs). Each card has its own set of attributes and cannot be divided into smaller parts.

our solution:

Ledger: The blockchain ledger keeps track of all the cards and their history. It shows who owns each card, its attributes, and the history of transactions related to it. This ensures transparency and trust in the ownership and history of the cards.

Smart Contract: We'll have a smart contract that controls how cards can be transferred between people. This contract manages the rules for transferring ownership of cards securely.

Organizations: In our permissioned blockchain setup, we'll have different types of organizations:

Ordering Service Organization: This organization runs the ordering service, which is responsible for organizing transactions into blocks fairly. It's like a referee ensuring everything is in order. Sometimes this can be a group of organizations coming together for fairness.

Owner Organizations: Each owner organization is allowed to run their own nodes (like computers) on the network. They can submit transactions to transfer the cards they own. Think of these as the players in our card trading game.owner.


## Snapshots of application, results
![image](https://github.com/vikram2580/BCDV-4025-PROJECT/assets/89578586/27fd85d0-8d77-4fe2-aedf-b6565e4e75bb)

![image](https://github.com/vikram2580/BCDV-4025-PROJECT/assets/89578586/32c0cd4a-50c1-44c9-a433-aa09c7d92fdf)

![image](https://github.com/vikram2580/BCDV-4025-PROJECT/assets/89578586/a53e4d2d-298a-4e48-a0e7-67b8535e2d70)

![image](https://github.com/vikram2580/BCDV-4025-PROJECT/assets/89578586/124bd976-144f-41ff-abbe-0b6c0ea37a32)

## Transaction Flow - Fabric gatway flow and transection submission Flow
![fabric-gateway-model](https://github.com/vikram2580/BCDV-4025-PROJECT/assets/89578586/cdc67607-0a33-460f-a0be-090f3015f1cf)

![transaction-submit-flow](https://github.com/vikram2580/BCDV-4025-PROJECT/assets/89578586/c1c4948a-adc0-4863-82ee-6f00d223d00b)


## Roles and Policies

1. Business Analyst:
Responsibilities:
Analyzes business processes and identifies areas where blockchain technology can bring value.
Defines use cases and user stories for the asset transfer system.

2. Architect:
Responsibilities:
Designs the overall system architecture for the asset transfer application.
Defines the technical specifications, including the choice of technologies and frameworks.
Creates solution design documentation outlining the system's components, interactions, and data flows.
Ensures the system's scalability, security, and performance meet requirements.

3. Blockchain Developer:
Responsibilities:
Develops the chaincode (smart contract) for the asset transfer system.
Implements the business logic for asset creation, transfer, and querying.
Ensures the chaincode follows best practices and security standards.
Works on integration with the frontend application through the API.

4. Full Stack Developer:
Responsibilities:
Sets up the Hyperledger Fabric network for the asset transfer system.
Configures peers, orderers, and channels according to the architecture.
Deploys and manages the chaincode on the Fabric network.
Develops the frontend application using typescript.
Implements frontend features for asset viewing, transfer, and other functionalities.
Integrates the frontend with the backend (REST API) for communication with the blockchain network.
