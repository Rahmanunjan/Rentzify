# RENTZIFY - THE FIRST DECENTRALISED RENT DEPOSIT DAPP!

-------------------------------------------------------
-------------------------------------------------------

A DeFi platform built on Moonbeam securing and monetising rent deposits. 
----
### SUMMARY
**Rentzify** is using an **ERC-4626** solidity smart contract deployed on the Moonbeam parachain to make rent deposits secure. The security is via use of a decentralised platform. Additionally, the use of a smart contract and a Multisig controls access to rent deposits in the vault. Deposits will be added to the vault and a native token used to accord shares to *renters* wallets. Also, a **Multisig Wallet** will set up signatories to the deposited tokens with nominees from *renters* and *Landlords* ( 3 each). Deposits are withdrawn in the following conditions:
+ 4 out of 6 signatories sign the transaction.
+ Yield is earned on part or whole of the deposits. Borrowers pay 5% of their stake to the renters. *Landlords* receive 20% of the yield from the *renters*. The platform takes 2.5 %.
+ Renters end their tenancy.
+ The DAO has given a final decision on an arbitrated case.
+ Individuals are banned/banished from the vault.

*Non tenants* can utilish flash loans, yield farming and other DeFi tools to stake an equivalent token into the Vault. Hence, *tenants* and *landlords* will be recipients of the yield bearing vault. 
----
### PROBLEM
1. Landlords are charging exorbitant rent deposits.
2. Landlords are refusing to return rent deposits.
3. Landlords are receiving rent deposits priot to property viewings.
4. Claims courts have a lengthy process while refunding claimed rent deposits.
----
### POLKADOT STACK
1. Moonbeam parachain - Provides a development environment for implementing the Ethereum and Subrate API. 
2. Moonbeam API - Allows integration of Solidity smart contracts.
3.   Polkadot Mulitisg Accounts.
4.   Polkadot OpenGov governance.
5.   ChainLink Oracle pallet.
----
### TECHNICAL DESCRIPTION
1. Renters will convert their fiat payment to the equivalent native token (BenzToken, BZT) and store in their wallet.
2. Renters will have their wallet (Multisig Wallet) connect to the platform.
3. Renters will make their crypto rent deposit payment to the vault. 
4. Renters will receive a token denoting their number of shares.
5. Landlords will connect with their wallet, assign their nominees (Renters likewise)

### FEATURES
+ Front end enabling users make a rent deposit to Landlord
+ Wallet Connection (ERC-4337 or smart contract wallet compatibility) for renters and Landlords
+ Vault smart contract in Solidity implementing ERC-4626
+ Account abstraction SDK (Biconomy) to onboard new web3 users (implementing a paymaster)
+ TBD login to preserve identity
+ Aave implementation of GHO stable coin
+ CCIP Chainlink integration to facilitate cross chain interoperability
+ L2 integration using Cartesi to reduce gas cost
+ SWARM integration to store data
----

### HOW TO USE
+ Renters will connect their wallets to the front end
+ Landlord and Renters will pay fee to use app
+ Rent deposits will be paid by crypto and deposited from wallet to the vault
+ Renters will choose from front end what percentage landlord can be paid
  
----

### PRESENTATION/PITCH
Canva link: https://www.canva.com/design/DAGLi002DzU/rNmPoQH7GDQlNW_swdfMxQ/edit?utm_content=DAGLi002DzU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
----
### ROADMAP
1 - 3 months : 
1. Build fully functioning Vault smart contract on Moonbeam. (2 weeks)
2. Integrate Multisig Wallet (Preference will be for an account abstraction, smart contract or ERC-4337 wallet) ( 1 week)
3. Set up OnChain Governance (Either through Polkadot OpenGov or a parachain) (1 week)
4. Integrate ChainLink (1 week)
5. Write white and yellow paper ( 4 days)
6. Build business road and 1 year Road map ( 4 days)
7. Target product market fit by conducting a pilot test (Core market are international students in Ireland. Irelkand has no centralised rent deposit scheme and over 125 000 students.) (5 weeks)
8. Smart contract audit (2 - 4 weeks)
9. MVP launch (after implementations from smart contract audit, 2 weeks)
----
### PROBLEMS ENCOUNTERED DURING BUILDING
1. Unable to obtain Metamask balance through web3.js
2. Ran out of test tokens
3. Buggy Front end
4. Web3.js wouldnt integrate with vault smart contract
----

### TECHNOLOGIES
+ Web3 login (TBD) - for secure identity
+ Account Abstraction Wallets - enable users implement tools of ERC-4337 (paymaster, userops, Bundler etc)
+ Moonbeam - Customised Parachains for different type of properties (commercial, airbnb , leases etc) and EVM implementation on Polkadot
+ CCIP(Chainlink Cross-Chain Interoperability Protocol) Chainlink for Blockchain Interoperability - Allows cross chain operations and oracle implementation.
+ AI generated Recommender system for reputable tenants and landlords (Proof of reputation) - Allows governance of users and suggestions. 
----

### COLLABORATORS
----

### RESOURCES
+ [https://docs.google.com/document/d/1w-SvSY5ILF0CTrq9y7InEKUHLj1bCQeS9h7mnJsctZc/edit]
 
