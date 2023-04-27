# Blockchain

To understand how Bitcoin or Ethereum work, it's important to first understand the underlying technology that powers them: blockchain.

Here, we will explain the basics of blockchain technology and how it relates to cryptocurrencies. We'll discuss what blockchain is, how it works, the benefits it provides and much more. We'll also explore some common terms and concepts related to blockchain, such as distributed ledger, mining, and cryptography. Lets dive in!


## What is the Blockchain?

A blockchain is just a chain of blocks that contains data. As a database, it stores data electronically in digital format. In its simplest form, a blockchain is a continuously growing list of data. That data is stored in blocks, and all those blocks are linked together. Think of a blockchain as a train🚆. A train that consists of multiple carriages connected in a line where each carriage contains some amount of data. So whats the purpose of a blockchain?

The purpose of a blockchain is to provide a:

   -Distributed
   -Decentralized 
   -Immutable
   -Secure and transparent 

 ledger into which data could be recorded by a network of computers that agree upon a common state of data
 
 ## How does the blockchain work?
 
As the name suggests, blockchain is a chain of blocks. It consists of blocks that are cryptographically linked to each other chronologically in a virtual chain. 

The blockchain collects data and enters it into a block, like a cell in a spreadsheet containing information. Blocks contain 2 important things:

1. Data - could be anything (e.g., transactions)

2. A piece of information that links back to the previous block - hash

### Cryptography
 
This creates a chain of blocks that are linked together in a sequential and chronological order through a unique hash that is generated using the information contained within each block, including the hash of the previous block in the chain. What is a hash?

Blockchain is secured by a variety of different cryptography concepts. Blockchain uses hashes to link the blocks together in the chain. Each block contains the hash of the previous block, creating a secure and tamper-proof link between them. 

Read more about [Cryptography and hashes](github.com/Abbas-Khann/Solidity-Mastery/blob/main/Absolute-beginner/Cryptography.md#hashing)

Okay, so why is the blockchain “distributed”?

### DLT

To understand blockchain, you first have to understand what a distributed ledger is. [Read here](https://github.com/Abbas-Khann/Solidity-Mastery/tree/main/Absolute-beginner#distributed-ledger-technologydlt) before you move on

A blockchain is simply a type of DLT that is :
 
  • Shared
  • Replicated
  • Synchronized
 
among a large number of participants who are spread across the world
 
It is a network of participants holding equal control that agree upon a common state of data

All the participant own the blockchain, it's decentralized! - There is no third party or central authority involved. And anyone can become a participant!

### Nodes

Each participant holds a copy of that database and shares it with other participants. These participants are called nodes. 

So, how many copies are there and how is data entered?🤔

There is not a single master copy of the blockchain.

Each node💻 :

   - keeps their own copy of the blockchain

   - constantly checks with other nodes to make sure everyone has the same record of data

To add a block all nodes must approve that their copy is the same as the copies of other nodes and reach a consensus.Data is entered & updated by the participants of the network.  All changes can be written & saved to all involved nodes only after approval by the majority. Nodes reach an agreement on what the blockchain looks like at any given moment.🤝

### What are the benefits of a distributed network?

By having each individual node store their own copy, it means there is:

1. No single point of failure✅

2. Reduced risks of fraud🛡️ - tampering and manipulation

3. Decentralization and transparency🌐- no need for a third party or a central authority

Because all nodes have equal power, there needs to be a mechanism for fairly deciding who can add blocks to the blockchain⬇️

## Mining
Before a block is added to the blockchain, it first needs to be validated. This is called mining. Each block must contain an answer to a complex mathematical problem that miners are trying to solve

Read more about [mining](https://github.com/Abbas-Khann/Solidity-Mastery/blob/main/Absolute-beginner/Mining.md#mining)

Valid block = block where the mathematical puzzle is solved

The first miner to solve the puzzle :

   1.Gets a reward for his effort 

   2.Gets to add the block to his copy of the blockchain
   
Nodes then synchronize with that copy and reach a consensus about the present state of the blockchain.🔄

How does the network of nodes in a blockchain system agrees on the validity of new blocks?

## Consensus

Consensus is the process by which the network of nodes in a blockchain system agrees on the validity of new blocks

Read more about [consensus and the consensus methods](https://github.com/Abbas-Khann/Solidity-Mastery/blob/main/Absolute-beginner/Consensus.md)

What happens when the block is added?

When a block is added to the blockchain it cannot be changed.

The block is closed and new blocks are created that chain with each other.

## Summary


Blockchain is a distributed, decentralized, immutable, and secure ledger that stores data in a continuously growing list of blocks that are linked together using cryptographic techniques. Each block contains data and a hash of the previous block, creating a tamper-proof chain. The blockchain is secured by a variety of cryptography concepts. Data is entered and updated by participants in the network who hold equal control, with each node keeping its own copy of the blockchain and constantly checking with other nodes to ensure everyone has the same record of data. Mining is the process by which blocks are validated and added to the blockchain, and consensus is the mechanism by which the network of nodes agrees on the validity of new blocks. The blockchain provides benefits such as reduced risks of fraud, no single point of failure, and decentralization and transparency, making it a valuable technology for various industries
