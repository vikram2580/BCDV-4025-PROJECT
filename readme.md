
Lets assume the assets you are tracking on the blockchain ledger are trading cards. Each trading card represents a comic book character and has an id, size, favorite color, and owner.
These trading cards can be passed between people, with some cards having more 'value' due to rarity or having notable attributes.

In token terms, think of these cards as non-fungible tokens. Each card has different attributes and individual cards can't be subdivided.

We'll create a digital representation of these cards on the blockchain ledger. There are a few important aspects of this solution to consider:

- Ledger - The blockchain ledger on each peer maintains the current state of each card (asset), as well as the history of transactions that led to the current state, so that there is no doubt about the assets issuance, provenance, attributes, and ownership.
- Asset transfer smart contract - manage changes to asset state such as the transfer of cards between people
- Organizations - Since this is a permissioned blockchain we'll model the participants as organizations that are authorized to run nodes or transact on the Fabric network. Our simple network will consist of an ordering service organization and two transacting organizations.
    - Ordering service organization - runs the ordering service to ensure transactions get ordered into blocks fairly, this may be a consortium leader or regulator in the industry. Note that ordering service nodes could also be contributed from multiple organizations, this becomes especially important when running a Byzantine Fault Tolerant (BFT) ordering service.
    - Owner Organizations - Each owner organization is authorized to run peers and submit transfer transactions for the cards (assets) that they own.

![image](https://github.com/vikram2580/BCDV-4025-PROJECT/assets/89578586/27fd85d0-8d77-4fe2-aedf-b6565e4e75bb)

![image](https://github.com/vikram2580/BCDV-4025-PROJECT/assets/89578586/32c0cd4a-50c1-44c9-a433-aa09c7d92fdf)

