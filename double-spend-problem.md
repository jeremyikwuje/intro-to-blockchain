# Double Spend Problem
If you are intending to start a career in blockchain/web3, one important thing to understand is the Double Spend Problem.

> **A double spend problem is the potential of a digital single asset(or digital money) to be spent more than once.**

When you send a photo to me on WhatsApp, the original photo will still remain with you. I will only receive a copy of the file. You have not transferred the ownership of the file to me. Imagine it is the same way money works.

If sending money online is just like sending a photo, you will never want to transferred the ownership. You will love to spend the "same money twice".

But a financial system where anyone is allowed to spend their money twice is bad.

## Physical Money
In the physical world, the double spend problem is not issue. Let’s say I have 10 dollars in cash. I give you 5 dollars, leaving me with a balance of 5 dollar. I can’t physically spend my 10 dollars again because my balance is just 5 dollar. No double-spending.

## Solutions
For a long time, the practical solution for us to get around this issue of double spending money in the digital world is to trust a central financial entity, like a bank or PayPal. Anytime you send money to me, we both trust that this entity will verify the transaction and transfer the ownership from you to me. So no one is double spending.

However, the problems with trusting a financial entities are many. They are slow. Most of them charge fees and impose limits on the size, type, and number of transactions a user can execute. If you live in Europe and send 1000 dollars to your family in Africa, it may take up to 30 days for them to receive the money.

In 2009, a revolution began with the arrival of Bitcoin blockchain. For the first time in history, rather than trusting on central entities to avoid the double spend problem, the public  could verify transactions of digital money without the need for that central entity. If I have 10 Bitcoin in my wallet, and I send you 5 of them, then we could trust technology and cryptography to update our wallet balances instead of trusting a bank.

Bitcoin solves the double spend problem by using a [decentralized ledger](https://river.com/learn/terms/d/decentralized-ledger/), which the public can access. Because the public can examine the full history of transactions, everyone is sure that no coins have been double spent. Additionally, the transaction records in the network is immutable and not control by a single entity or individual.

When I sends 5 bitcoin to you, the network destroy the 5 bitcoin I(the sender) own and create a new coin owned by you (the receiver). The destruction of my(the sender) 5 bitcoin  is recorded for all to see, so that I can never send it to someone else. And on average the transaction is confirmed and settle within an hour. There is no limit in the transaction one can make. And a single entity can't flag off the transaction.

Next >> [Single Point Failure](https://github.com/jeremyikwuje/intro-to-blockchain/single-point-failure.md)
