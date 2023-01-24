# Web3.0 华语媒体 RSS订阅源
作者：**[@panghu960](https://twitter.com/panghu960)**

> 项目初衷：一直想找几个主流web3.0媒体华语RSS媒体，一直找不到（比如律动，金色财经，链捕手）等等，无奈只能自己写一个《华语主流媒体RSS订阅源》。


## 请我喝杯咖啡
ETH：0xE971263B24024Fdf7d7fb090F5c89861486816b2


## 当前已支持：
- [x] 律动Blockbeat
- [x] 金色财经
- [x] Odaily 星球日报
- [x] PANews

## NEXT
- [ ] 文章重复检测

## 律动Blockbeat：

### 文章

[https://rss.web30.lol/b2](https://rss.web30.lol/b2)

##  金色财经

### 文章
现在更新了一个支持正文显示的版本。推荐🔥

[https://rss.web30.lol/jinse2](https://rss.web30.lol/jinse2)

### 其他版本⬇️

#### 快讯

举例: [https://rss.web30.lol/jinse/lives](https://rss.web30.lol/jinse/lives)

路由: `/jinse/lives`

#### 头条



举例: **[https://rss.web30.lol/jinse/timeline](https://rss.web30.lol/jinse/timeline)**

路由: `/jinse/timeline`

#### 分类**

举例: **[https://rss.web30.lol/jinse/catalogue/zhengce](https://rss.web30.lol/jinse/catalogue/zhengce)**

路由: `/jinse/catalogue/:caty`

参数:`caty`, 必选 - 分类名，参见下表

| 政策 | 行情 | DeFi | 矿业 | 以太坊 2.0 | 产业 | IPFS | 技术 | 百科 | 研报 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| zhengce | fenxishishuo | defi | kuang | 以太坊 2.0 | industry | IPFS | tech | baike | capitalmarket |

## Odaily 星球日报

#### 快讯

作者: **[@ncziztk](https://github.com/ncziztk)**

举例: **[https://rss.web30.lol/odaily/newsflash](https://rss.web30.lol/odaily/newsflash)**

路由: `/odaily/newsflash`

参数: 无

#### 文章

作者: **[@ncziztk](https://github.com/ncziztk)**

举例: **[https://rss.web30.lol/odaily](https://rss.web30.lol/odaily)**

路由: `/odaily/:id?`

参数:

- `id`, 可选 - id，见下表，默认为最新

| 最新 | 新品 | DeFi | NFT | 存储 | 波卡 | 行情 | 活动 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 280 | 333 | 331 | 334 | 332 | 330 | 297 | 296 |

#### 用户文章

作者: **[@ncziztk](https://github.com/ncziztk)**

举例: **[https://rss.web30.lol/odaily/user/2147486902](https://rss.web30.lol/odaily/user/2147486902)**

路由: `/odaily/user/:id`

参数:

- `id`, 必选 - 用户 id，可在用户页地址栏中找到

#### 活动

作者: **[@ncziztk](https://github.com/ncziztk)**

举例: **[https://rss.web30.lol/odaily/activity](https://rss.web30.lol/odaily/activity)**

路由: `/odaily/activity`

参数: 无

## PANews

### 深度

作者: [@nczitzk](https://github.com/nczitzk)

举例: [https://rss.web30.lol/panewslab](https://rss.web30.lol/panewslab)

路由: `/panewslab/:category?`

参数:

- `category`, 可选 - 分类，见下表，默认为精选

| **精选** | **链游** | **元宇宙** | **NFT** | **DeFi** | **监管** | **央行数字货币** | **波卡** | **Layer 2** | **DAO** | **融资** | **活动** |
| ------ | ------ | ------- | ------- | -------- | ------ | ---------- | ------ | ----------- | ------- | ------ | ------ |

### 快讯

作者: [@nczitzk](https://github.com/nczitzk)

举例: [https://rss.web30.lol/panewslab/news](https://rss.web30.lol/panewslab/news)

路由: `/panewslab/news`

参数: 无

### 专栏

作者: [@nczitzk](https://github.com/nczitzk)

举例: [https://rss.web30.lol/panewslab/author/166](https://rss.web30.lol/panewslab/author/166)

路由: `/panewslab/author/:id`

参数:

- `id`, 必选 - 专栏 id，可在地址栏 URL 中找到

### 专题

作者: [@nczitzk](https://github.com/nczitzk)

举例: [https://rss.web30.lol/panewslab/topic/1629365774078402](https://rss.web30.lol/panewslab/topic/1629365774078402)

路由: `/panewslab/topic/:id`

参数:

- `id`, 必选 - 专题 id，可在地址栏 URL 中找到

