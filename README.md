@[toc]



# CCS
    [Mining] Carlsten, Miles, et al. "On the instability of bitcoin without the block reward." CCS2016.
    
    > * 描述了当block reward降为零后，对tx fees的selfish mining攻击
    
    [Mining] Kwon, Yujin, et al. "Be selfish and avoid dilemmas: Fork after withholding (faw) attacks on bitcoin." CCS2017.
    
    > * 将selfish mining和BWH结合，避免了矿工困境。当两个矿池采用FAW攻击时，算力大的一方总是获胜
    
    [Mining] Tsabary, Itay, and Ittay Eyal. "The gap game." CCS2018.
    
    > * 对block reward降为0后的情况进一步分析，并考虑了挖矿的成本
    
    [Mining] Gao, Shang, et al. "Power adjusting and bribery racing: Novel mining attacks in the bitcoin system." CCS2019.
    
    > * 在FAW的基础上，敌手能够调整渗透矿工算力以最大化收益。其次，将selfish mining 和 bribery attack结合，提出了腐败矿工困境问题

    [DoS]


# S&P
   [Mining] Eyal, Ittay. "The miner's dilemma." 2015 IEEE Symposium on Security and Privacy. IEEE, 2015.
   
   > * 描述两个矿池之间互相采用BWH攻击时，对双方都会造成一定的损失，因此存在一个矿工困境



# USENIX Security
   [consensus] Szalachowski, Pawel, et al. "Strongchain: Transparent and collaborative proof-of-work consensus." USENIX Security 2019.
   
   > * 提出了一种新的共识协议：strong block 和 weak block，两者均具有一定比例的奖励，能够避免selfish mining攻击
   
   

# NDSS





# FC
    [Mining] Eyal, Ittay, and Emin Gün Sirer. "Majority is not enough: Bitcoin mining is vulnerable." FC2014.
   
   > * 对比特币进行自私挖矿，敌手算力大于全网算力的25%时，敌手会盈利
  
    [Mining] Sapirshtein, Ayelet, Yonatan Sompolinsky, and Aviv Zohar. "Optimal selfish mining strategies in bitcoin." FC2015.
    
    > * 以Markov decision process建模selfish mining,提供了敌手的相对收益




# Other
    [Mining] Niu, Jianyu, and Chen Feng. "Selfish mining in ethereum." ICDCS2019.
    
    > * 对以太坊的自私挖矿攻击
    
    [Mining] Ritz, Fabian, and Alf Zugenmaier. "The impact of uncle rewards on selfish mining in Ethereum." Euro S&PW 2018.
    
     > * 对以太坊的自私挖矿攻击
     
    [Mining] Liu, Hanqing, et al. "On the strategy and behavior of bitcoin mining with n-attackers." ASIACCS2018.

    > * 考虑了两个敌手之间的攻击，攻击策略为stubborn mining 和 selfish mining

    [Mining] Bai, Qianlan, et al. "A deep dive into blockchain selfish mining." ICC 2019.

    > * 描述了两个敌手，采用selfish mining互相攻击的场景

    [Cross-chain] Chain Interoperability. Vitalik Buterin. 2016.
    > * 介绍了三类常见的跨链协议，并分析其存在的安全性问题
    
    [Cross-chain] Herlihy, Maurice. "Atomic cross-chain swaps." PODC 2018.
    
    > * 介绍了原子跨链协议的定义等


