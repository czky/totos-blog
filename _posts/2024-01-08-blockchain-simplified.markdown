---
layout: post
title:  "Blockchain Simplified: Is it really a block?"
date:   2024-01-06 14:49:39 +0200
categories: jekyll update
author: "Thomas-Andrei Zareczky"
---

## Understanding the Blockchain Basics
At its core, a blockchain is a *revolutionary* concept that can be encapsulated into a pretty simple term: decentralized ledger. Let's unravel this sophisticated system by breaking it into smaller components.

## Blocks and Transactions: The Building Blocks
A **blockchain** is essentially a chain of blocks, and each block contains data, usually *transaction records*, including:
- The sender and receiver of a transaction,
- The timestamp of a transaction,
- The amount and type of currency sent.

<img src="{{ "/photos/blockchain/blocks-blockchain.png" | absolute_url }}">

You may ask: "*Why can't we do the same thing with a digital database?*". Well, because blockchains differ from other types of digital databases with a few ways:
- Blockchains are *open-source software*, meaning **everybody has access** to the source code of it and can see everything that goes on.
- Data can *only be added* in blockchains; once a blockchain network *verifies new information*, it **can't be altered** anymore.
- Data is stored on *multiple servers*, providing greater **reliability, transparency and performance** than any conventional database.

## Rules for Valid Blocks: The Order of the Blockchain
For a block to be valid, it must adhere to specific rules:
- **All transactions** must be valid,
- Both involved accounts must have **valid numbers**,
- The sender must have **sufficient funds**,
- Transactions **must be signed** by the rightful owner.
- Two blocks can't reference the same previous block, resulting in *chronological order* of the blockchain.

## Power of the Decentralization
**Traditional financial institutions** maintain ledgers for their accounts in a *centralized way*, while **blockchain ledgers** are *decentralized*, eliminating the need of a *single controlling entity.*

**Centralized** implies a *concentration of authority / control* in a central point, making it the main point for *decision-making and coordination* within a organization or system.

**Decentralization** is important because it *distributes control, decision-making an power* across a system, *reducing the overall risk* of a single point of failure, while keeping everything *secure, transparent and less vulerable* to manipulation or disruption.

## Smart Contracts
**One fascinating aspect** of blockchain technology is the introduction of **smart contracts**. These are *self-executing contracts* with the *terms of agreement written directly into the cod*e, making it easy to *automate and enforce* the execution of contractual agreements and *reducing the needs of intermediaries and increasing efficiency*.

## Privacy and Security
The security of blockchains relies heavily on the principles of cryptography. Cryptography is the field that encapsules the science of securing communication and information through the use of ciphers, codes and different techniques.
- **Randomness**,
- **Integrity**,
- **Authentication**,
- **Non-repudiation**,
- **Hash Functions**: Those transform *input data into a fixed-sized hash value* (eg. [SHA-256](https://en.wikipedia.org/wiki/SHA-2)),
- **Asymmetric Cryptography**: Involves using a pair of public and private keys, data being *encrypted with one key* can only be *decrypted by the other key*. (eg. [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) / [ECC](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography)),
- **Symmetric Cryptography**: The same thing as the one above, but instead of using two keys, *only one* is use to *both encrypt and decrpyt* the data. (eg. [DES](https://en.wikipedia.org/wiki/Data_Encryption_Standard) / [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard))

## The Role of Proof of Work and Proof of Stake: Maintaining Order
In order to prevent chaos, the blockchain eploys either Proof of Stake or Proof of Stake mechanisms.
- **Proof of Stake**: Requiring participants to prove a *significant positive balance* in their account, *maitaining system integrity and discouraging malicious activity*.
- **Proof of Work**: Solving *complex math equations or problems* to create a new block, *incentivizing participants* with newly creating currency and *ensuring time intervals* between blocks.

<img src="{{ "/photos/blockchain/process-blockchain.png" | absolute_url }}" style="float: center; margin: 0 0 50px 50px;">

## Conclusion
It's crucial to note that blockchains **extend their utility beyond financial transactions**. They can seamlessly track *copyright licenses, software, stocks and much more*. In essence, a blockchain is a *decentralized ledge*, going hand in hand with *cryptography*. The **continued evolution** of blockchain technology promises a lot *more advancements in transparency, applications, and the reshaping of traditional industries*.

## Sources
- [Blockchain - Wikipedia](https://en.wikipedia.org/wiki/Blockchain)
- [Blockchain Facts: What Is It, How It Works, and How It Can Be Used - Investopedia](https://www.investopedia.com/terms/b/blockchain.asp)
- [What is Blockchain - Oracle](https://www.oracle.com/uk/blockchain/what-is-blockchain/)
- [Blockchain - IBM](https://www.ibm.com/topics/blockchain)
- [What is Blockchain - AWS Amazon](https://aws.amazon.com/what-is/blockchain/?aws-products-all.sort-by=item.additionalFields.productNameLowercase&aws-products-all.sort-order=asc)
- [Blockchain - Synopsys](https://www.synopsys.com/glossary/what-is-blockchain.html)
- [What is Blockchain - McKinsey & Company](https://www.mckinsey.com/featured-insights/mckinsey-explainers/what-is-blockchain)

