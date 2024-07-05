# Introduction

## Brief History
The identity of Bitcoin creator Satoshi Nakamoto remains one of the most fascinating mysteries of the digital age. In 2008, in the midst of the global economic crisis, which threatened to collapse global economies, a mysterious figure emerged. With a meticulously crafted white paper, Satoshi Nakamoto introduced [`Bitcoin: A Peer-to-Peer Electronic Cash System`](https://bitcoin.org/bitcoin.pdf). Unlike previous monetary systems, Bitcoin operates without central control, incorporating a set of rules without rulers. For a couple of years, Nakamoto nurtured the system, leading volunteers and developers before disappearing without fanfare, leaving behind an invention that would change the world.

In January 2009, Nakamoto mined the first block of the Bitcoin blockchain, known as the `Genesis Block`, effectively launching the Bitcoin network. This initial block contained a cryptic message referencing bank bailouts during the financial crisis, symbolizing Bitcoin's intent as an alternative to the conventional banking system. The main goal was to create a decentralized currency that would allow peer-to-peer transactions without the need for intermediaries.
You can refer to the article [The Crypto-Currency](https://www.newyorker.com/magazine/2011/10/10/the-crypto-currency) by Joshua Davis, published on October 3, 2011, in The New Yorker.

Satoshi Nakamoto combined many previous discoveries to create a decentralized electronic money system that doesn't rely on any central authority. The goal was to distribute the computation to securely verify transactions. Satoshi's key innovation uses a distributed computing system to conduct a global "election" every 10 minutes allowing the decentralized network to reach consensus on the status of transactions. This mechanism helps solve the problem of double spending, where a single monetary unit can be spent twice, which plagued all digital currencies before Bitcoin.

## Who Controls Bitcoin? 
```Bitcoin is a system of rules without rulers```

No one has personal control over the Bitcoin system; Rather, it operates on mathematical principles, open source code, and consensus among participants. Although the developers working on Bitcoin's code appear to control the protocol, Bitcoin operates as a peer-to-peer network. Think of a website or any application whose database resides on a central server over which you have no control. Bitcoin doesn't work like that; It is a peer-to-peer network (which runs on each person's own system) where nodes can join or leave, verify transactions and maintain a ledger. If someone modifies the software, you cannot force others to accept the updates.

## The Bitcoin Network
The Bitcoin network is a decentralized peer-to-peer system that enables direct transactions between users without the need for intermediaries. Here are some of the key elements and principles that make up the Bitcoin network:

- #### The Bitcoin protocol
  The Bitcoin protocol is a decentralized peer-to-peer network that allows users to transact directly with each other. This ensures that transactions are secure, verifiable and immutable.
- #### Blockchain
  Blockchain is a public transaction ledger that records all Bitcoin transactions. Each block in the chain contains a list of transactions and these blocks are linked chronologically.
- #### Consensus rules
  Consensus rules are a set of guidelines that govern how transactions are verified and how new bitcoins are issued.
- #### Cryptographic security
  Advanced cryptographic techniques are used to secure transactions and control the creation of new bitcoins. This ensures that transactions are tamper-proof and that Bitcoins cannot be counterfeited.
- #### Byzantine fault tolerance
  The Bitcoin network is designed to be Byzantine fault tolerant, meaning it can reach consensus even if some participants act maliciously. This is achieved through a consensus mechanisms like Proof of Work (PoW), and economic incentives.
- #### Proof of Work (PoW)
  Proof of work is a consensus mechanism where miners verify transactions by solving a complex mathematical problems and add them to the blockchain. This process requires significant computational effort and energy. In return for their efforts, miners receive bitcoins (economic incentive) as rewards for validating transactions.
- #### Nash equilibrium
  In the context of the Bitcoin network, a Nash equilibrium is one in which no participant can benefit by changing their strategy while others keep their strategy unchanged. The best strategy for each participant is to follow the rules of the network, ensuring cooperation and stability.

## Why Bitcoin Doesn't Have a Hierarchical Network
In the structure of current fiat monetary systems, at the top of the hierarchy is the central bank, which is the primary monetary authority of a country. They are responsible for creating and issuing the national currency, setting interest rates, controlling the supply, and implementing policies to manage inflation and economic stability. Below the central bank are the commercial banks, which interact directly with the central bank and the public. Apart from commercial banks, there are also many different types of financial institutions like investment banks, insurance companies etc. Finally, at the bottom of the hierarchy are individuals and businesses, who are the primary users of the financial system.

This hierarchical network is highly centralized. Only selected organizations can become nodes, meaning only specific individuals can participate in the network. Decisions about the money supply and interest rates are made by a small, unselected (biased) group. In addition, we need permission to open a bank, open an account, transfer money or do anything we want. Governments may freeze our accounts or even monitor transactions. They are the control of all your finances!. This network is also deeply politicized. Central bankers, often former investment bankers or lawyers, hold significant power over the economy. Their decisions can affect inflation, interest rates and the money supply, indirectly taxing the public through currency devaluation.

In stark contrast, the Bitcoin network is open and permissionless. Anyone can join the network, mine Bitcoin, send and receive Bitcoin, and verify transactions without permission from the central authority. Transactions on the Bitcoin network are recorded in public ledgers (the blockchain). Once a transaction is added to the blockchain, it cannot be altered or changed. This immutability is enforced by cryptographic security and the decentralized nature of the network. With its open, permissionless nature and global neutrality, Bitcoin is the ideal monetary network that will transform the future of global finance. You can watch Matthew Kratter's [What Makes The Bitcoin Network So Special](https://www.youtube.com/watch?v=FghNnUJptIU) talk on YouTube for more details.

## The Bitcoin Currency
Bitcoin is a type of digital currency that lives only on the Internet. Unlike traditional currencies like the rupee or dollar or the euro, bitcoins are neither physical currencies nor digital currencies that you can see/touch. This makes Bitcoin more efficient at sending money around the world without the delays and costs of traditional banking. People use Bitcoin to buy goods, transfer money, save or store value. People also buy, sell or exchange bitcoins for other currencies.

Bitcoin has several key advantages that make it ideal for digital transactions:
- Speed: Bitcoin transactions are processed quickly, especially compared to traditional banks, where international transfers can take days. This is a great advantage for people who need to send or receive money from all around the World.
- Security: Bitcoin transactions are protected by advanced cryptography, which makes them very hard to alter or fake. This high level of security helps protect users from fraud and ensures the integrity of every transaction.
- Reliability: Bitcoin operates on a decentralized network, meaning there is no single point of failure. It also makes the network more resilient, ensuring that it continues to function even if some parts go offline or are attacked.
- Global Access: Bitcoin can be sent and received anywhere in the world. This makes it perfect for international trade and helps people who don't have access to traditional banking services.
- Virtual Nature: Since Bitcoin is completely digital, it does not require any physical form. Reduces the risks and costs associated with dealing with cash or physical assets.

In short, Bitcoin's speed, security, reliability, global reach and virtual nature make it an excellent choice for digital transactions and an interesting alternative to traditional currencies.

## Double Spend Problem
Before Satoshi Nakamoto's revolutionary work on Bitcoin, the concept of digital money was riddled with many challenges, most notably the double-spending problem (the risk of spending digital money more than once). For instance, a rupee or dollar bill or any physical asset like a gold or a house cannot be spent or sold twice due to physical possession and centralized control mechanisms like legal records or physical ownership. However, digital currencies lack these physical forms and centralized oversight, planting a unique challenge. Without a trusted intermediary such as a bank, digital currency can be duplicated many times and wasted.

Nakamoto's key innovation in solving the double spending problem was the application of blockchain technology. Each transaction is added into a block, and these blocks are linked chronologically to form a chain. And to ensure the integrity of the blockchain, Nakamoto introduced a consensus mechanism called Proof of Work (PoW). In this, transactions are verified by a network of miners who solve complex mathematical problems. After verification, the corresponding block of transactions is added to the blockchain, and the miner is rewarded with bitcoins. For a transaction to be considered valid, multiple miners must independently verify and confirm the transaction. This decentralized verification process ensures that any attempt to double spending is rejected. If someone tries to make two transactions using the same Bitcoin, only the first confirmed transaction will be added to the blockchain, while the second one will be invalidated.

Although Nakamoto's solution is robust, theoretical scenarios exist, there are chances for double spending to occur. 
Read about: Finney Attack, Race Attack and 51% Attack.

## Privacy in Bitcoin Transactions
Once transactions are verified, they are recorded on a public ledger, which allows you to view details such as sender's and receiver's addresses, the amount transferred, and timestamps. These addresses are usually pseudonymous (some alphanumeric strings) and do not directly reveal personal identities, although they can sometimes be linked to people through other means. To improve privacy, it is recommended not to reuse addresses. Creating a new address for each transaction makes it very difficult to link multiple transactions to the same user. Unlike bank account numbers, knowing a Bitcoin address does not allow anyone to withdraw money from your wallet; You have to start all expenses. However, by sharing the same address with multiple people, you can see how many bitcoins others have sent to that address. Therefore, creating a new invoice with a new address every time you request payment is important to maintain privacy.

## Inflation in Bitcoin
Bitcoin's inflation mechanism is basically different from fiat currencies due to its fixed supply and scheduled halving events. Unlike fiat currencies like the rupee or dollar, which can expand the money supply based on political and economic decisions, Bitcoin has a total supply of 21 million coins, ensuring scarcity. New bitcoins are introduced into circulation through mining, where miners are rewarded for adding new blocks to the blockchain. This reward is halved every four years, reducing the number of new bitcoins. With the 2024 halving, the block reward collected by miners is now 3.125 bitcoins, set to decrease to 1.5625 bitcoins in the next halving event.

The impact of these halving events is significant because they guarantee a predictable and steadily falling inflation rate. Bitcoin's issuance rate is highly predictable and the total supply is expected to peak in the year 2140. Currently, Bitcoin's inflation rate is about 0.9% annually and will reduce every four years until it reaches zero. This is in stark contrast to fiat currencies, whose inflation rates fluctuate widely.

## The Advantage of Irreversible Transactions in Bitcoin
There is an ongoing debate about the irreversibility of Bitcoin transactions, with some critics arguing that this feature is a major drawback. However, this view misunderstands the fundamental principles and benefits of Bitcoin technology. In fact, the irreversibility of transactions is one of Bitcoin's greatest strengths. 

Here's why:

Bitcoin does not depend on banks or intermediaries to approve transactions. Instead, it uses a decentralized system, meaning that no one person or organization controls it. This system ensures that once a transaction is made it cannot be changed, providing great security and confidence.

This feature comes with both pros and cons.
#### Pros:
  It would increase protection against fraud and errors, similar to traditional financial systems where erroneous or fraudulent transactions can be reversed, providing a sense of security.
  
#### Cons:
  Losing Decentralization: Bitcoin is decentralized, meaning no single person or group controls it. Making transactions reversible would need a central authority to manage reversals, which goes against Bitcoin’s principles.

  Complicated System: Adding the ability to reverse transactions would make Bitcoin more complicated and harder to manage.

  Possible Misuse: People might falsely claim mistakes or fraud to reverse transactions and get their money back unfairly.

  Trust Issues: Bitcoin is trusted because once a transaction is done, it can’t be changed. This gives users confidence that their transactions are final and secure. Reversing transactions could weaken this trust.

While the idea of ​​reversible transactions may seem attractive for greater security, it fundamentally changes what makes Bitcoin unique. Bitcoin's strengths lie in its decentralization, security and belief that once a transaction is made, it is final!. Bitcoin already provides ways to protect users from reverse transactions (Multisignature and escrow services). These mechanisms allow buyers and sellers to set conditions for the release of funds, provide ways to resolve disputes, and ensure that both parties meet their obligations. 
