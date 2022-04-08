# Protocol

## ACT Network protocol

The ArabCryptoTalk Network (ACT) is a decentralized information database platform that uses a decentralized headless content management system that is entirely controlled by token holders. Token holders have the right to approve or reject network-wide rules that govern ArabCryptoTalk, and buy-sell services on the network.

![ACT Protocol](<../../../.gitbook/assets/Customer Touchpoint Map (9).jpg>)

### Token module

The token module is responsible for token balances, the minting schedule, and the send/receive/fee functionalities. It has the right to modify the state of the article module.

### Staking ACT Tokens

Staking ACT tokens is required to propose an article, vote, and propose/vote on network governance actions. ACT is staked by locking the tokens in a vesting period that will be determined by the community vote.

### News module

The article module is in charge of generating editing proposals and updating the state of the news database, which subsequently takes an IPFS Hash, stores the data onto Arab Blockchain, and pins it to IPFS nodes.

### Governance module

The governance module has the ability to modify any module, including itself. Governance actions have the ability to change the software for any of the three modules, but not the database that stores token balances and news. This module allows the submission of changes to token holders for approval. If the community of stakeholders approves the changes, the governance module then deploys those changes on the corresponding module. This helps the community to reach agreement.
