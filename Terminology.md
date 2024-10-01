# Terminology
The following terms are used to describe concepts in this specification. 

|Terms|Terminology|
|-----|-----------|
| _Blockchain_ | The Bitcoin blockchain is the transaction database that is extended by nodes participating in the [mining](https://wiki.bitcoinsv.io/index.php/Mining) process on the Bitcoin network. The blockchain contains [transactions](https://wiki.bitcoinsv.io/index.php/Transactions) validated and processed by nodes on the network. Using the blockchain, anyone can add and verify a record of all of the [confirmed](https://wiki.bitcoinsv.io/index.php/Confirmation) transactions that have taken place on the ledger up until the most recent block was found. ([BSV Blockchain, UTXO](https://wiki.bitcoinsv.io/index.php/Blockchain)) | 
| _Blockchain Transactions_ | A Bitcoin transaction consists of a version number, a lock time value, a list of inputs and a list of outputs. The primary functionality of a Bitcoin transaction is to transfer custody of bitcoin from one person to another. A transaction uses [UTXOs](https://wiki.bitcoinsv.io/index.php/UTXO) as inputs and distributes their value to new outputs. UTXOs are the 'coins' in which all bitcoins are stored. ([BSV Wiki, Bitcoin Transactions](https://wiki.bitcoinsv.io/index.php/Bitcoin_Transactions)) |
| _Chain of Dust_ | In Bitcoin Satoshi Vision (BSV), a "Chain of Dust" refers to a sequence of minimum required value transactions that are created by spending small amounts of Satoshi’s. This concept is related to "dust" in the cryptocurrency context. These are small blockchain transactions where one dust transaction leads to another. Each subsequent transaction in the chain is dependent on the previous one, creating a linked sequence. ([BSV Wiki, UTXO](https://wiki.bitcoinsv.io/index.php/UTXO)) |
| _Decentralised identifier_ | A globally unique persistent identifier that does not require a centralized registration authority and is often generated and/or registered cryptographically. The generic format of a DID is defined in [3.1 DID Syntax](https://www.w3.org/TR/did-core/#did-syntax). A specific [DID scheme](https://www.w3.org/TR/did-core/#dfn-did-schemes) is defined in a [DID method](https://www.w3.org/TR/did-core/#dfn-did-methods) specification. Many—but not all—DID methods make use of [distributed ledger technology (DLT)](https://www.w3.org/TR/did-core/#dfn-distributed-ledger-technology) or some other form of decentralized network. ([W3C. DIDs v1.0, 2022](https://www.w3.org/TR/did-core/#dfn-did-documents))|
| _DID Controller_ | An entity that has the capability to make changes to a DID document. A DID might have more than one DID controller. The DID controller(s) can be denoted by the optional controller property at the top level of the DID document. Note that a DID controller might be the DID subject. (W3C, DID V.1.0,2022) |
| _DID Document_ | A set of data describing the DID subject, including mechanisms, such as cryptographic public keys, that the DID subject or a DID delegate can use to authenticate itself and prove its association with the DID. A DID document might have one or more different representations. (W3C, DID V.1.0,2022) |
| _DID Issuer_ | An individual or entity that  issued a DID. This term is specific to this document. | 
| _DID Manager_ | In this document we call DID manager to a package that includes the DID resolver and DID controller. DID Manager term is specific to nChain implementation.| 
| _DID Resolver_ | A DID resolver is a software and/or hardware component that performs the DID resolution function by taking a DID as input and producing a conforming DID document as output. (W3C, DID V.1.0,2022) |
| _DID Subject_ | The entity identified by a DID and described by a DID document. Anything can be a DID subject: person, group, organization, physical object, digital thing, logical thing, etc. (W3C,DID V.1.0, 2022, Section 5.1.1) |
| _Ledger_ | In this document, the ledger is distinguished from the blockchain. The Bitcoin ledger refers to information store that keeps records (3.81) of transactions (3.93) that are intended to be final, definitive and immutable (3.51). Unlike the blockchain, which is a chain of blocks verified by miners, the ledger specifically focuses on the individual transactions. (SO22739-2024) |
| _UTXO_ | UTXO is an acronym for unspent transaction output. Every Bitcoin transaction in every block contains at least one output. Outputs are then spent by inputs of later blockchain transactions and typically must be unlocked with a digital signature (most commonly ECDSA in Bitcoin). Until an output is used as an input in another transaction, this output is called a UTXO. (BSV Wiki, UTXO) |
| _Verifiable data registry_ | In order to be resolvable to DID documents, DIDs are typically recorded on an underlying system or network of some kind. Regardless of the specific technology used, any such system that supports recording DIDs and returning data necessary to produce DID documents is called a verifiable data registry. Examples include distributed ledgers, decentralized file systems, databases of any kind, peer-to-peer networks, and other forms of trusted data storage. (W3C, DID V.1.0,2022) | 
| _Verifiers_ | In this document, a verifier refers to an entity, organization, or individual that checks the status of the DID and verifies that the signature of the subject or DID controller matches the signatures in the presentation. (W3C, DID V.1.0,2022) | 
















