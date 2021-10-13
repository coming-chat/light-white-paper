# light-white-paper
## Background
- 1, Internet products have spread to all aspects of our lives. We have begun to pay attention to the quality of services. Privacy is a must for everyone, so we launched Coming Chat to allow everyone to enjoy the convenience of the Internet while taking into account personal privacy.
- 2， Social products such as Facebook/Wechat require users to provide specific passports or national ID cards, which is not conducive to globalization. We launched Coming ID as a unified global digital identity. No matter which country you are from, we ourselves use our private key to issue an identity passport for ourselves. We all belong to the same earth, the same blue sky, Coming ID global digital identity, which aims to make the communication in the global village faster and more convenient.
- 3，Encrypted wallets, the current encrypted wallets on the market, are relatively primitive wallets with various chains of BTC or ETH, which lack too much technology and provide users with greater security and convenience. The Schnorr signature algorithm is a major advancement of the elliptic curve, and the threshold signature can be derived from the aggregate signature. As long as it supports Schnorr's elliptic curve, we can customize Coming's dedicated threshold signature wallet (a special use case for distributed privacy computing). The use of threshold wallets can make user assets more secure, and the organization's multi-party collaborative privacy custody business is more secure and convenient.
- 4，NFT: NFT on Ethereum is a separate creation and issuance of NFT by contract. The creation of our Coming Card NFT provides 10^12 digital identities, which is convenient for users to create and issue Card NFTs in a unified manner, and it is also convenient for NFTs to quickly circulate with the help of digital identities and provide good practical NFTs.
- 5， The unified portal of Dapps, also known as the portal of Web3. Provide a unified entrance for Dapp development users to choose and develop various contract platforms. Provide a unified entrance for ordinary Dapp users, which is convenient for users to operate and use Dapp. Similar to Wechat's small program.

## 旨在解决的问题
### 中心化账户到去中心化账户体系的转移。
传统的互联网，采用的是对称加密账户体系， 对称加密导致我们的密码在中心化服务器上都有存证，牵涉到金融相关的系统， 就更需要各种安全防火墙，金融风控技术和成本去为此类应用买单。我们现在用户所在用的产品，如银行系统，社交软件如（Facebook，微信，twitter等）都是此类产品。 只要黑客攻击了中心化数据库，或者企业内部人员内幕操作，所有的用户都会遭殃。
BTC的出现， 用非对称的账户体系， 在全球数字金融圈中带来了革命性改变， 让每个用户拥有了自己账户的控制权， 没有任何中心化机构可以内幕操作以及任何黑客 通过黑掉中心化服务器黑掉整个账户体系。
但应用非对称加密的账户体系技术 还只是在 数字金融中小试牛刀。 我们的Coming， 不仅在数字资产钱包中采用非对称加密密钥账户体系， 还整合了全球数字身份和NFT的接入。 让社交和社交的所有信息都是可以归还给用户，真正做到账户体系的去中心化，以及用户是自己的真正主人，没有任何第三方可以控制你的私密信息和资产。
### 完全分布式的消息中转网络服务。
  2021年10月份，有29亿月活的Facebook发生 服务器被绑架，导致超过15亿用户在近1天的时间内受到了无法通讯的影响，这对于个即时通讯社交APP来说，是不可容忍的。导致这个问题的根本原因是： 中心化数据库被绑架，如果我们的服务器是分布式的， 有数十个甚至更多， 就不会存在这种中心化的问题。这也是我们Coming 消息服务器一直在致力于解决的问题。
  
## Technical details of each functional module
### Private social
隐私社交： Facebook是全球社交软件的龙头， 但他在隐私方面一直被诟病。TG在隐私社交上因为万人群和流畅的体验获得了隐私社交软件的成功， 但他还是中心化的， 只是TG的数据存在TG公司服务器上，TG公司不像Facebook一样去使用用户的数据盈利。再者传统的社交软件，都需要手机号等现实身份信息，其次都是用对称加密服务， 会导致中心化服务被泄露，所有用户数据就会永久泄露。
Status 在隐私通讯上解决了上面隐私的问题，它舍弃了手机号， 采用了非对称加密技术，让用户自己控制自己的一切，即使黑客攻击掉了服务器，或者服务器泄露了，也不会影响用户的数据和财产。但Status只是一个隐私通讯工具，没有社交的属性，基本限制了其发展。
Coming Chat： 采用类似Status相关的最严格隐私技术理论， 在保护用户隐私的前提上， 通过数字身份，NFT等等社交元素去丰富Coming的社交属性， 使其成为在保证用户隐私的情况下，达到传统社交软件的体验。
### Encrypted digital identity
数字身份：全球230多个国家和地区，各个地区都有各个国家的身份， 这个身份的认证和转换，需要太多的中间服务机构参与，既影响了效率，也在中间提供了太多的暗箱操作。
基于加密学的数字身份， 可以给全球提供一个 自己认证自己，无须任何中间机构参与的全球身份。
### Crypto wallet and payment
加密钱包：传统钱包 和 门限钱包。  Coming会支持传统钱包 作为基点 接入Dapp服务， 借用门限钱包扩大丰富钱包的生态。
### NFT creation and circulation platform
NFT创作和交易平台： 以太坊上的NFT创作平台是单个合约一套NFT的模式， 是割裂的NFT， 除了头部的NFT以外， 排名靠后的NFT合约基本没法流通。
C-Card结合 数字身份和卡片NFT的设计模式， 发行1~12位的数字，接近于1000亿张， 足以支撑市面上所有的NFT版本流通。 在同一个合约下， 使得我们的NFT方便流通和达成统一共识。
### Dapp portal platform
聚合平台： 去中心化的应用，如Dex等， 他们提供了一个很好的链上去中心化应用， 但没有给用户提供一个完美的交互入口。 Coming 旨在把这些去中心化应用 聚合到一个入口，让用户只要拥有了Coming，就能更好的和各类应用交互。

## 背景
- 1， 互联网产品已经普及到我们生活的方方面面，我们开始关注服务的质量，隐私是每个人的必须，所以我们推出Coming Chat，用来让大家在兼顾个人隐私的情况下，可以享受互联网的便捷。
- 2， Facebook/Wechat 等社交产品，需要用户提供具体护照或者各国身份证，这很不利于全球化。我们推出Coming ID 作为统一全球数字身份，不论你来自哪个国家，我们自己用自己的私钥来给自己发行身份护照。我们同属于同一个地球，同一片蓝天，Coming ID 全球数字身份，旨在让地球村的交流更快速便捷。
- 3，加密钱包， 现在市面上流通的加密钱包，是比较原始的 BTC或者ETH 各种链的钱包，缺乏太多的技术，和给用户提供更大的安全和方便。 施诺尔签名算法是椭圆曲线的一大进步， 聚合签名可以衍生出门限签名。只要支持施诺尔的椭圆曲线，我们就可以去定制化Coming 专用门限签名钱包（是 分布式隐私计算的一个特别用例）。 使用门限钱包可以让用户资产更安全，机构多方协同隐私托管业务更安全方便。
- 4，NFT： 以太坊上的NFT是单独割裂的一个一个合约创作和发行NFT。 我们Coming Card NFT 的创作，提供10^12个数字身份，方便用户统一去创作发行Card NFT，也方便NFT借助于数字身份可以快速流通以及很好的实用性NFT。
- ５，Dapps的统一入口，也叫做Web3的入口。 为Dapp开发用户提供一个统一的入口，方便选择使用开发各类合约平台。 为普通Dapp使用用户提供一个统一的入口，方便用户去操作使用Dapp。类似于Wechat的小程序。  
