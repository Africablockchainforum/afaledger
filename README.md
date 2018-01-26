# afaledger
What is Afaledger

Afaledger – is a decentralised peer to peer digital payment system, transactions are verified by network nodes and recorded in a public distributed ledger. Is an open source project for Africa developers, vendors, enterprise end-users and enthusiasts of business blockchain platform. Support the growth and innovation of Afaledger project.

Distributed Ledger Technology (DLT)

A distributed ledger is a type of data structure which resides across multiple computer devices, generally spread across locations or regions.

Distributed Ledger Technology includes blockchain technologies and smart contracts. While distributed ledgers existed prior to Bitcoin, the Bitcoin blockchain marks the convergence of a host of technologies, including timestamping of transactions, Peer-to-Peer (P2P) networks, cryptography, and shared computational power, along with a new consensus algorithm.

In summary, distributed ledger technology generally consists of three basic components:

    A data model that captures the current state of the ledger
    A language of transactions that changes the ledger state
    A protocol used to build consensus among participants around which transactions will be accepted, and in what order, by the ledger.
    
    Blockchains

According to hyperledger.org,

"A blockchain is a peer-to-peer distributed ledger forged by consensus, combined with a system for "smart contracts" and other assistive technologies."

Smart contracts are simply computer programs that execute predefined actions when certain conditions within the system are met.

Consensus refers to a system of ensuring that parties agree to a certain state of the system as the true state. Blockchain is a specific form or subset of distributed ledger technologies, which constructs a chronological chain of blocks, hence the name 'block-chain'. A block refers to a set of transactions that are bundled together and added to the chain at the same time. In the Bitcoin blockchain, the miner nodes bundle unconfirmed and valid transactions into a block. Each block contains a given number of transactions. In the Bitcoin network, miners must solve a cryptographic challenge to propose the next block. This process is known as 'proof of work', and requires significant computing power. We shall discuss proof of work in more detail in the Consensus Algorithms section. For a brief history of blockchain technology, please click here.

Timestamping is another key feature of blockchain technology. Each block is timestamped, with each new block referring to the previous block. Combined with cryptographic hashes, this timestamped chain of blocks provides an immutable record of all transactions in the network, from the very first (or genesis) block.

A block commonly consists of four pieces of metadata:

    The reference to the previous block
    The proof of work, also known as a nonce
    The timestamp

    The Merkle tree root for the transactions included in this block.

Merkle Tree

The Merkle tree, also known as a binary hash tree, is a data structure that is used to store hashes of the individual data in large datasets in a way to make the verification of the dataset efficient. It is an anti-tamper mechanism to ensure that the large dataset has not been changed. The word 'tree' is used to refer to a branching data structure in computer science, as seen in the image below. According to Andreas M. Antonopoulos, in the Bitcoin protocol,

"Merkle trees are used to summarize all the transactions in a block, producing an overall digital fingerprint of the entire set of transactions, providing a very efficient process to verify whether a transaction is included in a block."

Development process

Developers work in their own trees, then submit pull requests when they think their feature or bug fix is ready.
