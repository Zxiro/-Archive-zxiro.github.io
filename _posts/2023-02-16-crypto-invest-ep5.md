---
layout: post
title:  "加密領域的十大趨勢 01 - 蛤 我的 ETH 為什麼不見了"
date:   2023-02-16 09:18
category: essay
icon: article
keywords: tag1, tag2
image: ETH.jpeg
preview: 0
---
# 2023 加密領域的十大趨勢 Wallet Utility Improvement
 
 (This is the translation of article: https://medium.com/hashed-official/top-10-trends-in-2023-an-overview-by-hashed-81d85cad9a6e )

隨著加密行業的發展以及其基礎建設的發展，終端用戶的安全以及 UX 重要性隨之提升。但作為 dApps 接口的錢包卻仍存有挑戰。
錢包注記詞、個人私鑰管理還有簽署協定這些對於大部分的終端用戶是一個不可忽視的阻力。以下會提到現有的錢包解決方案。

![](https://i.imgur.com/To9u0ZY.png){:style="display:block; margin-left:auto; margin-right:auto" width="100%"}

1. 錢包私鑰管理以及簽署驗證

* Web3Auth ([Home](https://web3auth.io/))
	* 使用 MPC 多方計算（Multi-Party Computation）來提供非託管 (non-custodial ) 的登入體驗
	* 用戶無需記憶註記詞，可以用 Web2 帳號來登入錢包
	* 透過 Shamir Secreting Sharing（SSS）生成三個密鑰分片，由用戶以及 Auth Network 來做控管。
	* 大幅度地降低使用者使用錢包的困難度，也在中心化/去中心化做了一定的  Tradeoff （Web3Auth 仍存有某部分的存取權限）。
	
![](https://i.imgur.com/FDCbfTI.png){:style="display:block; margin-left:auto; margin-right:auto" width="100%"}

* Magic [Magic](https://magic.link/) 
	* 提供 SDK (Software Development Kit) 給開發者，讓使用者可用 E-mail / SMS 登入
*  Ramper [Ramper](https://www.ramper.xyz/)
	* 透過其提供的 Mobile SDK ，用戶可以使用社交帳戶還有 SSO (Single Sign On ) 來登入

2. 行動裝置錢包

* Coin98
	* 用戶基數達到 6 M 的行動超級 App

* Robinhood
	* 正在開發獨立的錢包應用程式來解決以下問題
		* 不親民的設計
		* 過高費用

3. 智能合約錢包
	* 智能合約可以提供如花用限制、自動交易還有大幅提高安全性的多簽功能

* Argent [Argent – The best Ethereum wallet for DeFi and NFTs.](https://www.argent.xyz/)
	* 提供社交回覆（V 神大推）還有有限制的下單功能
* Safe  [Overview - Safe](https://safe.global/) 
	* 提供多簽功能讓使用者管理他們的數位資產

4. MetaMask [Download Flask & Get Access to our Cutting Edge Features | MetaMask](https://metamask.io/flask/)
* 作為加密錢包的始祖以及領導團隊，MetaMask 推出了 MetaMask Flask 來去對應其他錢包團隊的挑戰。
* Flask 提供用戶自訂義 MetaMask 錢包的功能，不過 Flask 面向的對象多為開發者居多，提供開發者權限去嘗試不同鏈上的功能可能性

![](https://i.imgur.com/MEgEwCL.png){:style="display:block; margin-left:auto; margin-right:auto" width="100%"}


### EIP - 4337  Account Abstraction
* 現在以太坊上有兩種帳號 EOA (Externally Owned Accounts), CA (Contract Account). AA (Account Abstraction) 能夠讓用戶不再需要註記詞並且讓 EOA 擁有如 CA 一般的能力。
* 抽象性讓用戶不需要知道帳戶的底層邏輯而能夠操作它。由於以太坊上的交易只能通過由 ECDSA 所保護的 EOA 發起，但 EOA 的限制相較於能自定義的 CA 多，所以造成 EIP-4337 的發起。

	* ![](https://i.imgur.com/cpILSVo.png){:style="display:block; margin-left:auto; margin-right:auto" width="100%"}
	* ![](https://i.imgur.com/73fITB2.png){:style="display:block; margin-left:auto; margin-right:auto" width="100%"}

* 簡單來說， AA 讓 EOA 具有 CA 的可自定義興，可以透過硬體錢包、多簽機制、社交恢復等手段幫助用戶降低 EOA 原生限制所造成的以太坊進入門檻。
* Visa 已在 StarkNet demo AA 可以提供的自動交易潛力。

### Conclude
* 未來一年在錢包賽道上的項目約能分為
	* Mobile Login
	* Convenient User Onboarding
	* Smart Contract Wallet
		* Programmable
		* Auto Transactions
* 若 EIP-4337 能夠完成審核以及推入以太坊 ，智能合約錢包的出現將對整個錢包上至區塊鏈產業造成強大的典範轉移 (Paradigm Shift)
* 工商時間：請下載我的團隊推出的瀏覽器插件來加強你的交易體驗 ([Moonkat](https://moonkat.io/))

* ![](https://i.imgur.com/XpJ6EY2.png){:style="display:block; margin-left:auto; margin-right:auto" width="100%"}

### Reference
* https://medium.com/hashed-official/top-10-trends-in-2023-an-overview-by-hashed-81d85cad9a6e
* https://foresightnews.pro/article/detail/19436
* https://www.blocktempo.com/ethereum-eip-4337-account-abstraction/