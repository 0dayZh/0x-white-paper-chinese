翻译成员

- [0dayZh](https://github.com/0dayZh)

原文：[https://0xproject.com/pdfs/0x_white_paper.pdf](https://0xproject.com/pdfs/0x_white_paper.pdf)

# 0x: 基于以太坊区块链的去中心化交易所开放协议

Will Warren, Amir Bandeali
0xProject.com

2017 年 2 月 21 日

## 摘要

我们讨论一种基于以太坊区块链的协议，它可以促使 ERC20 代币的点对点交易阻碍变低。该协议预期成为一个开放的标准和通用构建组建，在包含兑换功能的去中心化应用（dApps）中带来互相交互的能力。由以太坊智能合约执行的交易可以被公开的查询，自由的使用并且任何 dApp 都可以接入其中。在此协议之上构建的 dApp 可以访问公开的流动资金池，或者创建他们自己的流动资金池并且根据最终数额收取交易手续费。该协议是无过多意图的：它不会将成本强加给用户，或者从一组用户中抽取额外的价值输送给另外用户。去中心化的治理是用来持续、安全的整合升级到基础协议中，而不会扰乱 dApps 和终端用户。

## 内容

- [1 简介](#)
- [2 现状](#)
- [3 明确说明](#)
    - [3.1 消息格式](#)
        - [3.1.1 点对点委托](#)
        - [3.1.2 广播委托](#)
    - [3.2 智能合约](#)
        - [3.2.1 签名授权](#)
        - [3.2.2 填单 & 部分填单](#)
        - [3.2.3 过期时间](#)
        - [3.2.4 取消委托](#)
- [4 协议代币](#)
    - [4.1 去中心化治理](#)
        - [4.1.1 持续化整合](#)
        - [4.1.2 代币注册](#)
- [5 总结](#)
- [6 致谢](#)
- [7 附录](#)
    - [7.1 ERC20 代币](#)
    - [7.2 合约 ABI](#)
    - [7.3 以太坊域名服务](#)
