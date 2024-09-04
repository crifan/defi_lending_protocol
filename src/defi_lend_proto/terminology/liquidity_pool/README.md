# 流动性池Liquidity Pool

* 流动性池=Liquidity Pool= LP 
  * 领域：DeFi借贷协议中的名词 
  * 是什么：资金池 == 共享资金池 
    * 把钱都放到一个池子pool里，供借贷用 
    * 用户将数字资产存入流动性池，成为协议可以借出的资金 
  * 用途 
    * 很多DeFi借贷协议都用到了 
      * 举例 
        * AAVE 
        * Compound 
  * 安全性 
    * 共享资金池的借贷市场，是以牺牲协议整体安全性为代价，来支持更多的可借贷代币的 
      * 随着支持的代币越来越多，整个平台的安全性将会显著降低 
    * 整个借贷市场的安全性取决于安全性最弱的那个代币市场（木桶效应）。如果这个市场出现漏洞被攻击，那么其他市场也会遭受损失 
      * 举例 
        * 2021年10月，CREAM 允许 $FTT 作为借贷抵押品，随后平台中 $FTT 资产价值超过了整个协议中资产的 40%。社区此时意识到这是一个严重的安全隐患，于是要求下架 $FTT，但此时平台中的 $FTT 已经被大量使用，并用于做空其他 DeFi Bluechip 资产（例如 YFI），随后 CREAM 只能降低 $FTT 的 collateral factor 
        * BSC Venus 借贷平台中的 XVS（Venus 自己的代币）价格被操控（有消息称是 Venus 团队自己进行的市场操纵），导致整个平台遭受了 2亿美金的损失。（$200 M Venus Protocol hack analysis） 
        * CREAM 遭受闪电贷攻击（攻击代币的 Oracle），导致平台遭受 1.3亿美金损失。（Cream Finance Exploited in Flash Loan Attack Netting Over $100M） 
