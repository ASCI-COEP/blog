# Simplest Blockchain Explaination
author: <a href='https://www.linkedin.com/in/soureesh-patil'>Soureesh Patil</a>

# Table Of Contents

* [What is blockchain?](#ab)
* [Simple day to day life example](#b)
* [Blockchain Details](#c)
* [Impact on the world](#d)

# <a name="ab"></a> What is blockchain? 

Simply speaking blockchain is a chain of blocks which contain useful information. New information or block is added only after validation by authenticated users (miners). The most important feature of this technology is, once information is added, it is almost impossible to tamper it. Also anyone in the network of the blockchain can see the newly added information but the details of the sender and the receiver are in encrypted form, (created using hashing technique). Hence this technology provides transparency and security.

# <a name="b"></a> Simple day to day life example 

Suppose there are four friends. They often do transactions together and also spend money on behalf of each other. But at the end of the day, they want to have a clear record of all the transactions. They should know who owes how much money to whom. 
One solution is, one of them should monitor and keep record of all the transactions. But if due to some reasons he changed order of some transactions, missed some transactions, or added some invalid transactions, that will be miserable.

# <a name="c"></a> Blockchain Details 

To avoid this, blockchian can be used. Implementing _decentralization_ feature, every one of them will have a copy of the ledger. For new transaction to be added, it should be approved by majority of them. The newly added transaction contains information like sender, receiver, amount, time stamp, its own hash (encrypted form) and more importantly __hash of the previous transaction__.
By adopting this technique, all the transactions will be authenticated and added in right order. 
The most important part, chaining of the transactions, is possible due to _hash of previous transaction_. If anyone tampers the data in the block , the unique identity of the block , ie- __hash__ will be changed. But the next block still contains the old hash and hence , after tampering, it will not be consistent with the common  ledger. This will result in unacceptable transaction, thus securing the blockchain from such attacks. Furthermore, if the attacker tries to change the _previos hash_ component of all the next blocks, it is almost impossible due to the system called '_Proof of Work_' (PoW). The attacker will have to solve a difficult math puzzle which requires great computational power. This process of solving the puzzle and adding new transaction is called _mining_. Mining is continuous process going on in the blockchain as it decides the next person, who will add the new transaction. Miner who adds the transaction get paid for it. Due such competition and huge computational requirements, it is very difficult to tamper the data.

# <a name="d"></a> Impact on the world 

Blockchain is influencing major sectors like banks, cryptocurrency, supply chain, finance, healthcare, smart contracts, voting systems and many more.
In my opinion, due to its features like immutability, transparency, security, decentralization, this technology has potential to revolutionize the world. Reliability and resilience will help it to strengthen its roots. History of usage in illicit activities, grater computational power requirements, slow rate of adding new transactions are some negative points about it. But, its pros are seeming more beneficial than the loss made by its cons. Hence, this technology is trending today.
