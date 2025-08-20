# DID:BSV Method Specification: A UTXO friendly method. 
03 October 2024

**Authors**
- Thomas Moretti
- Leon Mlakar
- Božo Dragojevič
- Kapil Jain
- Maria Eugenia Lopez
- David Bricman
- Marko Kramer
- Goran Stevanič

**Contributors**
 - Marko Macek

**Reviewers** 
- Owen Vaughan
- Robert Alizon
- Liuxuan Pan

Feedback 
- Issues: https://github.com/teranode-group/TNG-Identity-bsvdid-method/tree/main

<br> 
<br> 

## 1. Abstract
This document outlines a method for the issuance, status updates, key rotation, and revocation of Decentralized Identifiers (DIDs) using a public, UTXO-based blockchain as a data registry. In this approach, DIDs are issued and managed through transactions recorded on the blockchain, leveraging its transparency and immutability. The blockchain allows a UTXO to be spent only once, which provides a double spend protection, resulting in a final spent state that is permanent and verified by the network. This characteristic makes the UTXO model ideal for reflecting the status of a DID, such as revocation, which, is irreversible once executed. DIDs can also be updated by linking a transaction chain to the DID Document, with a new version controlled solely by the DID Controller. Our approach supports both issuer-initiated and user-initiated status updates and revocation requests, ensuring secure and verifiable DID management within a distributed ecosystem. This document describes key rotation methods for DID recovery. We described a proposal to accomplish low latency for DID resolution and a governance mechanism to guide the implementation and deployment of DIDs, emphasizing the critical role of the blockchain in maintaining a reliable and transparent data registry. 

<br>
<br>

Full specification of DID:BSV method is here. [DID:BSV Method specification](https://docs.teranode.group/tng-identity-documentation/did/bsv-did-method-specifications/method-specification.-a-utxo-friendly-method) 

Universal resolver documentation for DID:BSV method. [Universal resolver documentation](https://docs.teranode.group/tng-identity-documentation/did/bsv-did-universal-resolver)

 
 






