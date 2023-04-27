## Mining

### What is mining?

Mining is a crucial process in the world of blockchain. It is the mechanism that enables the creation and validation of new blocks in the chain

A block needs to be validated first before getting written on to the blockchain.

This is called mining

### How does mining work?


The first thing to understand about mining is that it involves solving a complex mathematical problem which is finding a valid block hash

A hash of a block is calculated by hashing the blocks data, number, previous hash, nonce + other stuff. 

Miners attempt to solve a cryptographic equation by finding a valid block hash. 

They can't modify the block number or data, so they alter the nonce and keep searching for a valid number.

To make the task challenging, the blockchain defines a target, and hashes above the target are invalid while those below it are valid. 

The target is usually small, which is why the block hash begins with zeros.

The first miner to find the right nonce number earns a reward for validating the block. The miners' primary role is to validate blocks, and once a block is validated, it is added to his blockchain copy and then checked by others for consensus.

I really recommend you to play with this tool that illustrates block mining. It will really help you understand hashes and mining. Built by Anders Brownworth:

https://andersbrownworth.com/blockchain/block


