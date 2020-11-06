@[toc] 



# CCS

# S&P

# Usenix Security

# NDSS

# FC

# Other


## Mining

1.   Eyal I, Sirer E G. Majority is not enough: Bitcoin mining is vulnerable. FC2014.
      * 对比特币进行自私挖矿，阈值为25%。
2.   Sapirshtein A, Sompolinsky Y, Zohar A. Optimal selfish mining strategies in bitcoin. FC2015.
      * 以Markov decision process建模selfish mining。
3.   Eyal I. The miner's dilemma. S&P2015.
      * 描述两个矿池之间互相采用BWH攻击时，对双方都会造成一定的损失，因此存在一个矿工困境。
4.   Carlsten M, Kalodner H, Weinberg S M, et al. On the instability of bitcoin without the block reward. CCS2016.
      * 描述了当block reward降为零后，对tx fees的selfish mining攻击。
5.   Kwon Y, Kim D, Son Y, et al. Be selfish and avoid dilemmas: Fork after withholding (faw) attacks on bitcoin. CCS2017.
      * 将selfish mining和BWH结合，避免了矿工困境。当两个矿池采用FAW攻击时，算力大的一方总是获胜。
6.   sabary I, Eyal I. The gap game. CCS2018.
      * 
7.   Gao S, Li Z, Peng Z, et al. Power adjusting and bribery racing: Novel mining attacks in the bitcoin system. CCS2019.
      * 在FAW的基础上，敌手能够调整渗透矿工算力以最大化收益。其次，将selfish mining 和 bribery attack结合，提出了腐败矿工困境问题。
8.   Szalachowski P, Reijsbergen D, Homoliak I, et al. Strongchain: Transparent and collaborative proof-of-work consensus. USENIX security2019.
      * 提出了一种新的共识协议：strong block 和 weak block，两者均具有一定比例的奖励，能够避免selfish mining攻击。
9.   Feng C, Niu J. Selfish mining in ethereum. ICDCS2019.
      * 对以太坊的自私挖矿攻击。
10.  Liu H, Ruan N, Du R, et al. On the strategy and behavior of bitcoin mining with n-attackers. ASIACCS2018.
      * 
11.  Bai Q, Zhou X, Wang X, et al. A deep dive into blockchain selfish mining. ICC2019.
      * 描述了两个敌手，采用selfish mining互相攻击的场景。

## Blockchain System Security



## Cross-Chain
1.   Chain Interoperability. Vitalik Buterin. 2016.
      * 介绍了三类常见的跨链协议，并分析其存在的安全性问题

## Consensus
