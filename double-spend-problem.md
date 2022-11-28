# Double Spend Problem
If you are intending to start a career in blockchain/web3, one important thing to understand is the Double Spend Problem.

> A double spend problem is the potential of a single asset(or digital money) to be spent more than once.

## The Problem
Digital files like text, audios, and videos are easily duplicated. You can record a song on a computer, with the click of a button create multiple copies of that song, send those copies to more than one person while keeping the original copy. This is one of the things that makes like computers desiring and easy to use.

But the ability and ease to duplicate money in countless amount is a problem. A monetary system where anyone is allowed to duplicate the money they have is bad. In computer science, this problem is called the double spend problem, the potential of a single asset to be spent more than once.

## Physical Money
Let’s say I have 10 dollars in cash. I give you 5 dollars, leaving me with a balance of 5 dollar. I can’t physically spend my 10 dollars again because my balance is just 5 dollar. No double-spending. If I tried to duplicate the 10 dollars, and send you a fake note, I may be charge for counterfeiting.

However, on the internet, the double spend problem can easily occur. I can just copy/paste the 10 dollars and send to you, leaving me with same 10 dollar in my wallet too.

## Solutions
Initially, to get around this issue of double spending money, we trusted a central financial entity (like a bank or PayPal) to verify transactions and dictate the balance of any given account. So no one can easily duplicate their money.

However, the problems with trusting a financial entities are many. They are slow. Most of them charge fees and impose limits on the size, type, and number of transactions a user can execute. If you live in Europe and send 1000 dollars to your family in Africa, it may take up to 30 days for them to receive the money.

In 2009, a revolution began with the arrival of Bitcoin blockchain. For the first time in history, rather than trusting on central entities to avoid the double spend problem, the public  could verify transactions of digital money without the need for that central entity. If I have 10 Bitcoin in my wallet, and I send you 5 of them, then we could trust technology and cryptography to update our wallet balances instead of trusting a bank.

Bitcoin solves the double spend problem by using a [decentralized ledger](https://river.com/learn/terms/d/decentralized-ledger/), which the public can access. Because the public can examine the full history of transactions, everyone is sure that no coins have been double spent. Additionally, the transaction records in the network is immutable and not control by a single entity or individual.

When I sends 5 bitcoin to you, the network destroy the 5 bitcoin I(the sender) own and create a new coin owned by you (the receiver). The destruction of my(the sender) 5 bitcoin  is recorded for all to see, so that I can never send it to someone else. And on average the transaction is confirmed and settle within an hour. There is no limit in the transaction one can make. And a single entity can't flag off the transaction.

Next >> [Single Point Failure](https://github.com/jeremyikwuje/intro-to-blockchain/single-point-failure.md)
