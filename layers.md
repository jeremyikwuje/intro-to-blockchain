# Blockchain Layers

> ***It’s slow and it’s costly, but as more and more people have it, those things go away. There are newer technologies that build off of blockchain and make it more approachable. - Jack Dorsey, Cofounder of Twitter***

For blockchain technology to continue to grow in users and transactions, it must continue to be secure, decentralized and also scalable. 

However, based on CAP theorem, there's a widely held notion that public blockchain technology(like Bitcoin) must sacrifice security, decentralization or scalability. The CAP theorem states that a decentralized database, such as a blockchain, can only satisfy two of the three guarantees mentioned above simultaneously.

Bitcoin blockchain for instance has impenetrable security over a broad decentralized network. But it can only handle 7 transactions per second - not scalable. This is a problem because centralized solutions like Visa can handle 20,000 transactions per second.

<p align="center">
  <img src="https://github.com/jeremyikwuje/intro-to-blockchain/blob/main/assets/layers-meme-1.jpg" alt="Memes">
</p>

As a result of this, **the most important goal has been to create a blockchain network that is decentralized and highly secure while also handling a high volume of transactions per second.**

This led to the concept of blockchain layers. Individuals and companies began creating network solutions either on top of an existing blockchain or an entirely new blockchain network. The focus of layers has been either as a way to increase transaction speed, handle large volumes, or reduce fees.

There are two ways to understand blockchain technology and layers solutions.

1. Blockchain architecture 
2. Blockchain protocol

Blockchain architecture consists of five layers—the hardware layer, the data layer, the network layer, the consensus layer and the application layer.
 
The blockchain protocol is made up of four layers—Layer 0, Layer 1, Layer 2 and Layer 3. Let’s take a look at each of these categories separately. 

> Protocol refers to the set of rules that govern a network.

Let's explain each of these layers on architecture and protocol.

## 1. Blockchain Architecture 

### Hardware layer

The first layer of the blockchain is the hardware layer. This consists of hardware, like network connections, the computers within the network and data servers. All these contribute to the computing power of the blockchain.

> Node is referred to as the computers in the blockchain network. The job of these computers is to decrypt transactions.

### Data Layer

This is the layer next to the hardware layer where details of transactions in the network are stored. Transactions or data are stored in a block. Each current block which has data is connected to the previous block and the next block that will be generated. Only the genesis block is only connected forward and not backward.

> A block is the fundamental unit of a blockchain. A genesis block is the first block of the network.

### Network layer

A blockchain has a peer-to-peer network, which ensures that computers(nodes) in the network communicate with one another on the state of the chain. Each node has to know about the transactions which other nodes are validating. The network layer enables this communication.

### Consensus layer

Recall, a consensus mechanism is a way in which every computer(node) in the network agrees on what is written on the blockchain data layer. The consensus layer is responsible for the validation of a block. 

For example, in the Bitcoin blockchain, Tom and Jerry are two miners on the blockchain. They receive transactions which have to be decrypted and added to a block.

Tom receives transactions: A and B
Jerry receives transactions: B and C

I guess you spotted the problem. If both Tom and Jerry validate the transactions and add them to the blockchain, then transaction B will be stored twice on the blockchain. This means double spending will occur. To avoid double spending, the Bitcoin consensus layer requires that they compete and solve a cryptic mathematic puzzle and the one who solves first will be the one to add the block to the blockchain. If Tom solves first, then Tom receives transactions A and B and John recieve only transaction C. No double spend.

> Recall, Bitcoin uses a form of consensus mechanism known as Proof of Work (PoW). Which is considered the most secure, though energy intensive.

### Application layer
This is the layer in the blockchain on which applications are built. These applications can be backend programs like smart contracts or user-facing apps like wallets, browsers, social media, NFT sites and so on.

> These apps may look and feel like normal applications or websites, the difference is the decentralised nature of the database at the backend of these applications.

## 2. Blockchain Protocol 

### Layer zero (L0)

Layer 0 is the underlying infrastructure for the blockchain network. It is the blockchain itself. Layer zero is the base technology that allows Bitcoin, Ethereum and all other blockchain networks to function.

### Layer one (L1)

This is basically an implementation of the blockchain itself. Blockchain by itself is just data storage. Layer one is where things like consensus mechanisms, programming languages, block time, dispute resolution, and rules and parameters that maintain the blockchain network are implemented. L0 and L1 are sometimes combined as one. 

> Bitcoin, Ethereum, and Solana are L1 blockchain networks.

### Layer two (L2)

As L1 blockchains like Bitcoin and Ethereum transactions load increase, they become slow, expensive, and limited. To speed up transactions, reduce cost, and expand the blockchain, Layer 2 solutions are created to address the limitations of L1 without tempering or distorting the functionality. 

L2 solutions are scaling solutions for the Layer 1 blockchain. Polygon is an L2 scaling solution for the Ethereum blockchain and Lightening Network is an L2 solution for the Bitcoin Network. 

> Rollups, Sidechains, and Nested blockchains are various kinds of L2 solutions.

### Layer three (L3)

Layer three can be seen as the application layer of the blockchain. The job of L3 projects is to host decentralized applications(dapps) and other user-facing apps on the blockchain network. They perform best when they run on top of an L2 solution.

> L3 is usually divided into two sub-layers: application and execution layers.

### Conclusion 

Blockchain technology is made possible because of a mix of many existing technologies like cryptography, game theory, computer network and so on.

The blockchain architecture layers are what keep the network, data and applications up and running. The blockchain protocol layers are focused on improving the utility of the blockchain for the real world.

Every layer is an advancement of the blockchain. Layer zero lays the groundwork for the rest of the protocol, on which new and different blockchains solutions are created.

The end goal of all blockchain layers is to increase the utility of blockchain technology and meet the growing demand.



**Next >> [What can Blockchain be use for?](https://github.com/jeremyikwuje/intro-to-blockchain/blob/main/blockchain-use-cases.md)**

**Prev << [Consensus Mechanism](https://github.com/jeremyikwuje/intro-to-blockchain/blob/main/consensus-mechanism.md)**

