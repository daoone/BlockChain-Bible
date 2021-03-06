# 6.1 区块链术语
## 区块 (Block) 
区块是在区块链网络上承载交易数据的数据包，是一种被标记上时间戳和之前一个区块 的哈希值的数据结构，区块经过网络的共识机制验证并确认区块中的交易。 【ref：区块链行业词典】eidt by MJ

## 父块(Parent Block) 
父块是指区块的前一个区块，区块链通过在区块头记录区块以及父块的哈希值来在时间 上排序。 【ref：区块链行业词典】eidt by MJ

## 区块头( Block Header) 
记录当前区块的元信息，包含当前版本号、上一区块的哈希值、时间戳、随机数、 Merkle Root 的哈希值等数据。此外，区块体的数据记录通过 Merkle Tree 的哈希过程 生成唯一的 Merkle Root 记录于区块头。【ref：区块链行业词典】 //eidt by MJ
## 区块体(Block Body) 
记录一定时间内所生成的详细数据，包括当前区块经过验证的、区块创建过程中生成的 所有交易记录或是其他信息，可以理解为账本的一种表现形式。 【ref：区块链行业词典】//eidt by MJ
## 区块链(Blockchain)： 
已验证区块清单，每一个区块都链接到它之前的一个区块，一直到创世块。//eidt by MJ
## 区块容量  
每一个链上的区块的大小，比特币链上每个区块大小为1MB。/eidt by MJ
## 哈希(hash)
散列/ Hash 哈希又称作“散列”，是一种数学计算机程序，它接收任何一组任意长度的输入信息， 通过哈希算法变换成固定长度的数据指纹输出形式，如字母和数字的组合，该输出就是  “哈希值”。哈希使存储和查找信息速度更快，因为哈希值通常更短所以更容易被找到。 同时哈希能够对信息进行加密，一个好的哈希函数在输入域中很少出现哈希冲突，哈希 一个特定文档的结果总是一样的，但找到具有相同哈希值的两个文件在计算上是计算上 不可行的。 【ref：区块链行业词典】//eidt by MJ
## 时间戳(Timestamp)
时间戳从区块生成的那一刻起就存在于区块之中，是用于标识交易时间的字符序列，具 备唯一性，时间戳用以记录并表明存在的、完整的、可验证的数据，是每一次交易记录 的认证。【ref：区块链行业词典】eidt by MJ
## 默克尔根 (Merkle Root)
默克尔根是默克尔树的根节点，该节点为树中所有节点对进行多次哈希计算后所得出的结果。//eidt by MJ
## 默克尔树(Merkle Tree) 
又叫哈希树，是一种二叉树，用来存储哈希值。由一个根节点、一组中间节点和一组叶节点组成。最下面的叶节点包含存储数据或其哈希值，每个中间节点是它的两个孩子节点内容的哈希值，根节点也是由它的两个子节点内容的哈希值组成。//eidt by MJ
## 共识 (consensus) 
比特币网络上的大部分节点，在他们本地的经过验证的区块链上都有一样的区块。
## 共识规则 (consensus rules) 
全节点与其他节点保持共识时要遵守的一些区块验证规则。
## 分叉(Fork) 
分叉也被称为意外分叉。 当两个或者多个区块有一样的区块高度时，就会分叉区块链。典型情况是两个或多个矿工几乎在同一时刻挖出了一个区块。共识攻击的情况下也会出现分叉。//edit MJ
## 硬分叉（Hard Fork）
指在区块链或争取中心化网络中不向前兼容的分叉，硬分叉对加密货币使用的技术进行永 久更改，这种变化使得所有的新数据块与原来的块不同，旧版本不会接受新版本创建的 区块，要实现硬分叉所有用户都需要切换到新版本协议上。如果新的硬分叉失败，所有 的用户将回到原始数据块。【ref：区块链行业词典】//eidt by MJ
## 软分叉（Soft Fork)
指在区块链或去中心化网络中向前兼容的分叉。向前兼容意味着，当新共识规则发布 后，在去中心化架构中节点不一定要升级到新的共识规则，因为软分叉的新规则仍旧符 合老的规则，所以未升级的节点仍旧能接受新的规则。 【ref：区块链行业词典】//eidt by MJ
## 幽灵协议 (GHOST Protocol) 
通过幽灵协议，区块可以包含不只是他们父块的哈希值，也包含其父块的父块的其他子 块(被称为叔块)的陈腐区块的哈希值，这确保了陈腐区块仍然有助于区块链的安全 性，并能够获得一定比例的区块奖励，减少了大型矿工在区块链上的中心化倾向问题。【ref：区块链行业词典】//eidt by MJ
## 分布式存储 (Distributed Data Store:DDS)
传统上的分布式存储本质上是一个中心化的系统，是将数据分散存储在多台独立的设备 上，采用可扩展的系统结构、利用多台存储服务器分担存储负荷、利用位置服务器定位 存储信息。而基于 P2P 网络的分布式存储是区块链的核心技术，是将数据存储于区块 上并通过开放节点的存储空间建立的一种分布式数据库，解决传统分布式存储的问题。【ref：区块链行业词典】eidt by MJ
## 分布式账本（Distributed Ledger Technology-DLT)
分布式账本是指一种在网络成员之间共享、复制和同步的数据库，分布式账本在区块链 中是一个通过共识机制建立的数字记录，区块链网络中的参与者可以获得一个唯一、真 实账本的副本，因此难以对分布式账本进行篡改。更改记录的方式非常困难，技术非常 安全。 Technology-DLT)：分布式账本是指一种在网络成员之间共享、复制和同步的数据库，分布式账本在区块链 中是一个通过共识机制建立的数字记录，区块链网络中的参与者可以获得一个唯一、真 实账本的副本，因此难以对分布式账本进行篡改。更改记录的方式非常困难，技术非常 安全。 【ref：区块链行业词典】eidt by MJ
## 节点(Node)
任何运行了比特币软件的计算机都可以被称为节点。 //eidt by M
## 验证池机制 
POOL 验证池机制是基于传统的分布式一致性技术和数据验证机制的结合，它使得在成熟的分布式一致性算法(Pasox、Raft)基础上，不需要代币也能实现秒级共识验证。 【ref：比特币维基】//eidt by MJ
## 双重支付/双花 (Double-spent)
双重支付是一笔钱被使用了一次以上所导致的结果。比特币通过对添加到区块中的每笔交易进行验证来防止双重支付，确保一笔交易的输入没有被支付过。//eidt by MJ
## 拜占庭将军问题
一个可靠的计算机系统必须能够处理一个或多个组件产生的失败。一个失败的组件可能表现出通常被忽略的行为类型，即发送矛盾的信息到系统的不同部分。处理这类失败类型的问题抽象地被表达为拜占庭将军问题。
## 分片(Sharding) 
分片是区块容量的一种解决方案。通常情况下，每个节点和区块链网络都包含区块链的 完整副本，分片是一种允许节点具有完整的区块链的部分副本的技术，以提高整体性能 和稳定速度。 【ref：比特币维基】//eidt by MJ
## 锁定时间 (Locktime)
锁定时间是交易的一部分，其表明当这笔交易被添加至区块链中的最早时间或区块。//eidt by MJ
## 闪电网络 (Lightning Networks)
闪电网络是哈希时间锁定合约（HTLCs）的一种建议实现方式。闪电网络通过双向支付通道方式，允许支付方通过多个点对点支付通道安全地完成支付。这将形成这样一种支付网络，该网络中的一方可以支付给其他任何一方，即使他们之间没有直接的建立支付通道。//eidt by MJ
## 哈希时间锁定合约（HTLC）
是支付的一个类别，它使用了哈希锁和时间锁来锁定交易，解锁需要接收方提供通过加密支付证明承认在截止日期之前收到了支付，或者接收方丧失了认领支付的能力，此时支付金额将返回给支付方。//eidt by MJ
## 雷电网络 (Raiden Network) 
雷电网络是一种以太坊链下扩容解决方案，它使得使用以太坊技术的加密货币能够即时 和低成本交易。交易双方只要在链上存在交易信道，就能在链下根据被锁定的余额进行 高频、双向的即时确认交易，将这样多个通道形成的支付路径构成“雷电网络”。 【ref：比特币维基】//eidt by MJ
## 隔离见证 (Segregated Witness - SW) 
隔离见证是一种技术，通过把占用大量存储空间的区块的数字签名重新放置到不同的记 录(也称为隔离)，使每个区块能进行更多的交易，以达到扩容的目的。区块链上不仅 记载了每笔转账的具体信息，还包括了每笔交易的数字签名以核实交易的合法性。矿工 在打包区块的时候需要用数字签名来验证每笔交易，确认无误之后才会将该笔交易记 录在区块里。但对于用户不需要验证信息，且每个比特币记录大小被限制在 1 兆字节 (MB)，每 10 分钟记录一次新的记录，所以通过隔离见证转移签名以扩大区块空间。【ref：比特币维基】//eidt by MJ
## 侧链技术
侧链（sidechain）协议允许资产在比特币区块链（blockchain）和其他区块链之间互转。以比特币举例，侧链不能发行比特币，但可以通过支持与比特币区块链挂钩来引入一定数量的比特币。当比特币在侧链流通时，主链上对应的比特币会被锁定，直到侧链的比特币回到主链。//edit by 云辉

侧链的实现方案一共有五种模式：

单一托管模式

联盟模式

SPV模式

驱动链模式

混合模式
## 图灵完备
一切可计算的问题都能计算，这样的虚拟机或者编程语言就叫图灵完备的。//edit by 云辉
## 缠结 (Tangle) 
Tangle 是 IOTA 项目创造的一种改革性的去区块化分布式账本，它是可扩展的、轻量 级的，还能在无需任何费用的前提下进行价值转移。Tangle (缠结)是基于有向无环图 (DAG)的机构，而不是像区块链的连链式架构，它能定期添加区块，从而实现更高的 交替吞吐量和零交易手续费。【ref：比特币维基】//eidt by MJ
## 有向无环图 (Database Availability Group -DAG) 
DAG 指有向无环图，是常用于计算机领域的数据结构。DAG 具备独特的拓扑结构，经 常被用于处理动态规划，导航中获得最短路径等场景中。在区块链领域，DAG 用来解 决扩容性的问题，通过增加区块大小或者区块频率在网络中产生大量分叉，但是攻击者 还是需要 51% 的算力才能进行攻击。 【ref：比特币维基】//eidt by MJ
## nonce：区块头里的一个虚设栏
是通过计算机运算随机得出的一个数字。这个数字和一个区块里的其他数据经过哈希运算后，所得出的哈希值在某个特定范围内，则这个区块被验证。// edity by MJ
## 公有链（Public Chain）
对所有人开放、任何人可参与，采用PoW或POS共识机制，比如比特币、莱特币，以太坊等。// edity by MJ
## 私有链 （Private Chain）
组织或机构控制写入权限，读取权限可以对外开放，也可以进行任意程度的限制。比如 Eris Industries。// edity by MJ
## 联盟链 （Consortium Chain）
共识过程受到预选节点控制的区块链。如Linux及机会下面的超级账本(Hyperledger)项目，区块链联盟R3CEV等。A consortium blockchain is a blockchain where the consensus process is controlled by a pre-selected set of nodes; for example, one might imagine a consortium of 15 financial institutions, each of which operates a node and of which ten must sign every block for the block to be valid. The right to read the blockchain may be public or restricted to the participants. There are also hybrid routes such as the root hashes of the blocks being public together with an API that allows members of the public to make a limited number of queries and get back cryptographic proofs of some parts of the blockchain state. These blockchains may be considered “partially decentralized” （https://blockchainhub.net/blockchain-glossary) 
