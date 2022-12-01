# What is a Consensus Mechanism?

> ***Whereas most technologies tend to automate workers on the periphery doing menial tasks, blockchains automate away the center. Instead of putting the taxi driver out of a job, blockchain puts Uber out of a job and lets the taxi drivers work with the customer directly. - Vitalik Buterin, Co-Founder of Ethereum***

A "consensus" means a general agreement has been reached. For instance, consider a group of people going to a game station. If there is no disagreement on the proposed game to play, then a consensus is achieved. If there is disagreement, then the group must have a way to agree on a game to play. In a case where they couldn't reach an agreement, the group will eventually split.

**A consensus mechanism is a way in which the blockchain network agrees on what new information is stored in that database.**

Each blockchain has a consensus mechanism ensuring that the data stored in that database is true and therefore trustworthy.

The two widely used consensus mechanisms are:

* Proof of Work (PoW)
* Proof of Stake (PoS)

**Proof of Work(PoW) is Bitcoin consensus mechanism**. In a POW, we have miners, a group of people verifying transactions (the new information being written to the Bitcoin database). Miners compete with each other by using computers to solve a hard mathematical puzzle. Since solving this puzzle is difficult, miners invest in high computers and electricity, and as a reward for their work, the network pays them bitcoins.

> A bitcoin is a reward that the network gives to miners to thank them for verifying transactions. These transactions are verified in batches or blocks.

**Proof of Stake(POS)** is another consensus mechanism many blockchain platforms use. Instead of needing to do intense computation work like in PoW, we have validators, a group of people who validate transactions by staking their coins to the network. If a validator successfully validates a transaction, they earn a reward e.g ETH. Ethereum once used a Proof of Work(PoW) consensus mechanism but later switched to a Proof of Stake(PoS) in 2022.

> ***In a PoW, we have miners who risk capital by expending energy to verify transactions. In a PoS, we have validators who explicitly stake their coins to validate transactions. Miners and Validators who act dishonestly by trying to verify inaccurate information are penalized or kicked out of the network.***

**Security** is a major consideration in a consensus mechanism; the blockchain network has to be kept secure.

In a Pow, the network is kept secure by the fact that **you'd need 51% of the network's computing power to defraud the blockchain**. This would require such huge investments in equipment and energy; you are likely to spend more than you would gain.

In a PoS, the network is secure crypto-economically because **an attacker attempting to take control of the chain must destroy a massive amount of ETH**. A system of rewards incentivizes individual stakers to behave honestly, and penalties disincentivize stakers from acting maliciously.

> ETH or ether is the native cryptocurrency of the Ethereum network. Every Blockchain network usually has a native currency to pay for gas fee or transactions. BTC or bitcoin(with lowercase b) is the native currency of the Bitcoin network.

Proof-of-work and proof-of-stake alone are not the only consensus mechanism. Proof of Authority and Proof of History are also widely used.

When choosing a blockchain platform, it is important you consider and understand the consensus mechanism it is using.

**Next >> [Blockchain Layers](https://github.com/jeremyikwuje/intro-to-blockchain/blob/main/layers.md)**

**Prev << [What is a Blockchain?](https://github.com/jeremyikwuje/intro-to-blockchain/blob/main/what-is-a-blockchain.md)**
