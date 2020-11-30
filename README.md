



# CCS
   [Mining] Carlsten, Miles, et al. "On the instability of bitcoin without the block reward." CCS2016.
    
   > * 描述了当block reward降为零后，对tx fees的selfish mining攻击
    
   [Mining] Kwon, Yujin, et al. "Be selfish and avoid dilemmas: Fork after withholding (faw) attacks on bitcoin." CCS 2017.
   
   > * 将selfish mining 和 BWH相结合，提出了FAW，并解决了矿工困境问题。即当两个矿池采取FAW互相攻击，大的一方总获胜
   
   [Mining] Tsabary, Itay, and Ittay Eyal. "The gap game." CCS 2018.
   
   > * 考虑了block reward降为0后，多个敌手之间的博弈场景，并考虑挖矿成本
   
   [Mining] Gao, Shang, et al. "Power adjusting and bribery racing: Novel mining attacks in the bitcoin system." CCS 2019.
   
   > * 基于FAW，动态调整渗透矿工的算力以最大化收益。将bribery attack 和 selfish mining结合，并提出腐败矿工困境
    
   [DoS] Mirkin, Michael, et al. "BDoS: Blockchain Denial of Service." CCS 2020.
   
   > * 提出了一种区块链拒绝服务攻击，并不要求敌手需要较大算力
   
   
   
 
# S&P
   [Mining] Eyal, Ittay. "The miner's dilemma." 2015 IEEE Symposium on Security and Privacy. S&P 2015.
   
   > * 描述两个矿池之间互相采用BWH攻击时，对双方都会造成一定的损失，因此存在一个矿工困境



# USENIX Security
   [consensus] Szalachowski, Pawel, et al. "Strongchain: Transparent and collaborative proof-of-work consensus." USENIX Security 2019.
   
   > * 提出了一种新的共识协议：strong block 和 weak block，两者均具有一定比例的奖励，能够避免selfish mining攻击
   
   [transaction] Yousaf, Haaroon, George Kappos, and Sarah Meiklejohn. "Tracing transactions across cryptocurrency ledgers." USENIX Security 2019.
   
   > * 分别提出了两种启发式方法追踪跨链交易，其中增强式启发方法依赖Shapeshift的API
   
   [Attack] Tramèr, Florian, Dan Boneh, and Kenny Paterson. "Remote side-channel attacks on anonymous transactions." USENIX Security 2020.
   
   > * 提出了一种side-channel attack，通过流量分析、PING and REJECT attack 破坏 ZCash 和 Monero 的不可连接性和匿名性。
   
# NDSS





# FC
   [Mining] Eyal, Ittay, and Emin Gün Sirer. "Majority is not enough: Bitcoin mining is vulnerable." FC2014.
   
   > * 对比特币进行自私挖矿，敌手算力大于全网算力的25%时，敌手会盈利
  
   [Mining] Sapirshtein, Ayelet, Yonatan Sompolinsky, and Aviv Zohar. "Optimal selfish mining strategies in bitcoin." FC2015.
    
   > * 以Markov decision process建模selfish mining,提供了敌手的相对收益
   
   [Mining] Negy, Kevin Alarcón, Peter R. Rizun, and Emin Gün Sirer. "Selfish Mining Re-Examined." FC2020
   
   > * 考虑一种新的私自挖矿攻击：间歇性自私挖矿，即阶段一采用自我挖矿，阶段二采取诚实策略。可以发现，这种策略能够提高敌手的单位时间收益。此外，文章中还分析了间歇性自私挖矿在不同DAA（困难程度调整算法）上的表现



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


