# DMIT IP 质量到底怎么样：全是原生 IP 吗？能解锁 Netflix 和 ChatGPT 吗？被墙了怎么换？（附 Pro / Eyeball / Tier 1 区别与全套餐价格）

DMIT 的 IP 质量，能先确定的有三件事。全系是原生 IP，IPv6 信息里 ISP 和 ASN 都写着 AS906 DMIT Cloud Services，用的是商家自有网段，不是从云厂商租来的广播地址。洛杉矶节点实测 Netflix US、Disney+ US、HBO Max、Hulu、ChatGPT、Google Gemini、Claude 全部通过。香港节点 Netflix HK、Disney+ HK 通过，ChatGPT 只认移动 App，Gemini 不过。

价格这边，最便宜的入门是 LAX.EB.WEE，$39.9 一年，1 核 1G 内存 20G 硬盘，每月 1T 流量、1Gbps 带宽。电信宽带如果晚高峰也要稳，看 LAX.Pro.WEE，$36.9 一年，配置接近，回程走 CN2 GIA。

下面按 IP 归属、平台解锁、被墙处置、三档线路区别、全套餐价格的顺序讲，每节单独回答一个问题，跳着看也不会断。

> **急着下单的看这里**
>
> - 只要一个干净的原生 IP，预算优先：LAX.EB.WEE（$39.9/年）或 CORONA（$49.9/年，2Gbps 带宽）
> - 电信宽带，晚上八九点也在用：LAX.Pro.WEE（$36.9/年）起，或者 Pro 月付 TINY（$9.99/月）
> - 面向香港和华南低延迟：HKG.Pro.TINY（$39.9/月）；只做国际业务、不要求大陆优化：SJC.T1.WEE（$36.9/年）
>
> 👉 [查看 DMIT 当前在售套餐与实时价格](https://www.dmit.io/aff.php?aff=9081)

## 全套餐价格表：洛杉矶与圣何塞

洛杉矶分四条线：Pro（CN2 GIA）、Pro 不限流量、sPro（高防）、EB（CMIN2）；圣何塞只有 T1 一条国际线路。以下价格与额度来自公开整理的套餐表，DMIT 会不定期调整在售档位和库存，付款前以商品页显示的数字为准。

**LAX.Pro（三网 CN2 GIA，测试 IP 154.17.2.2）**

| 套餐 | CPU / 内存 / 硬盘 | 流量 · 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| Pro.WEE（限量） | 1核 / 1G / 20G | 500G/月 · 500Mbps | $36.9/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MALIBU（限量） | 1核 / 1G / 20G | 1000G/月 · 1Gbps | $49.9/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.PalmSpring（限量） | 2核 / 2G / 40G | 2000G/月 · 2Gbps | $100/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.TINY | 1核 / 2G / 20G | 1T/月 · 1Gbps | $9.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.Pocket | 1核 / 2G / 40G | 1.5T/月 · 4Gbps | $14.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.STARTER | 2核 / 2G / 80G | 3T/月 · 10Gbps | $29.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MINI | 4核 / 4G / 80G | 5T/月 · 10Gbps | $58.88/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MICRO | 4核 / 4G / 160G | 7T/月 · 10Gbps | $74.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MEDIUM | 4核 / 8G / 160G | 14T/月 · 10Gbps | $168.88/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.LARGE | 8核 / 16G / 320G | 25T/月 · 10Gbps | $338.88/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.GIANT | 12核 / 24G / 640G | 50T/月 · 10Gbps | $619.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |

**LAX.EB（三网 CMIN2，测试 IP 154.17.226.2）**

| 套餐 | CPU / 内存 / 硬盘 | 流量 · 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| EB.WEE（限量） | 1核 / 1G / 20G | 1000G/月 · 1Gbps | $39.9/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.CORONA（限量） | 1核 / 1G / 20G | 1500G/月 · 2Gbps | $49.9/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.FONTANA（限量） | 2核 / 2G / 40G | 2500G/月 · 4Gbps | $100/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.TINY | 1核 / 2G / 20G | 1.5T/月 · 2Gbps | $9.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.Pocket | 1核 / 2G / 40G | 3T/月 · 4Gbps | $14.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.STARTER | 2核 / 2G / 80G | 5T/月 · 10Gbps | $29.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.MINI | 4核 / 4G / 80G | 10T/月 · 10Gbps | $58.88/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.MICRO | 4核 / 4G / 160G | 14T/月 · 10Gbps | $74.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.MEDIUM | 6核 / 8G / 160G | 30T/月 · 10Gbps | $168.88/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.LARGE | 8核 / 16G / 320G | 50T/月 · 10Gbps | $338.88/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.GIANT | 8核 / 24G / 640G | 100T/月 · 10Gbps | $619.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |

同样价位下，EB 给的 CPU 核数和内存更容易做大，比如 MEDIUM 档 EB 是 6 核，Pro 是 4 核；代价是回程从 CN2 GIA 换成 CMIN2。

**LAX.Pro 不限流量与 LAX.sPro 高防**

| 套餐 | CPU / 内存 / 硬盘 | 流量 · 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| Pro.uMINI | 2核 / 2G / 20G | 不限 · 30Mbps | $239.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.uMICRO | 4核 / 8G / 50G | 不限 · 50Mbps | $399.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.uMEDIUM | 4核 / 8G / 80G | 不限 · 100Mbps | $799.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.uLARGE | 8核 / 16G / 100G | 不限 · 200Mbps | $1399.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| sPro.CREATOR | 2核 / 2G / 20G | 1.5T/月 · 100Mbps | $71.99/季 | [查看](https://www.dmit.io/aff.php?aff=9081) |

不限流量那几档的卖点是流量不设上限、带宽封顶，30Mbps 起。这个价位只对跑长连接、持续下载、代理中转这类场景有意义，普通建站用不上。sPro 则是去程挂 Cloudflare Magic Transit 的 5Tbps+ 高防，回程仍是 CN2 GIA，被打过的站才需要考虑。

**SJC.T1（国际线路 + 20Gbps DDoS 防御，测试 IP 174.136.205.2）**

| 套餐 | CPU / 内存 / 硬盘 | 流量 · 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| T1.WEE | 1核 / 0.5G / 10G | 1T/月 · 10Gbps | $36.9/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.TINY | 1核 / 0.75G / 10G | 2T/月 · 10Gbps | $6.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.STARTER | 1核 / 1.5G / 20G | 4T/月 · 10Gbps | $12.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.MINI | 2核 / 2G / 40G | 8T/月 · 10Gbps | $21.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.MICRO | 2核 / 4G / 80G | 16T/月 · 10Gbps | $32.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.MEDIUM | 4核 / 4G / 120G | 32T/月 · 10Gbps | $49.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.LARGE | 4核 / 8G / 200G | 64T/月 · 10Gbps | $99.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.GIANT | 8核 / 16G / 400G | 128T/月 · 10Gbps | $199.99/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |

## 全套餐价格表：香港与东京

香港和东京的价格明显高于洛杉矶，HKG.Pro 的入门 TINY 就要 $39.9/月。这两地的档位与流量口径在不同整理版本里略有出入（比如 HKG.Pro.TINY 有 400G 和 500G 两种记录），下表按较新的一份整理列出，具体以商品页为准。

**HKG.Pro（电信 CN2 GIA / 联通 AS9929 / 移动 CMI，测试 IP 103.117.100.2）**

| 套餐 | CPU / 内存 / 硬盘 | 流量 · 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| Pro.TINY | 1核 / 1G / 20G | 400G/月 · 1Gbps | $39.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.STARTER | 1核 / 2G / 40G | 800G/月 · 1Gbps | $79.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MINI | 2核 / 2G / 60G | 1200G/月 · 1Gbps | $119.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MICRO | 4核 / 4G / 80G | 1600G/月 · 1Gbps | $159.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MEDIUM | 4核 / 8G / 160G | 1800G/月 · 1Gbps | $179.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.LARGE | 8核 / 16G / 320G | 2400G/月 · 1Gbps | $239.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.GIANT | 8核 / 24G / 640G | 4800G/月 · 1Gbps | $499.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |

**HKG.EB（CMIN2，测试 IP 154.3.32.3）与 HKG.T1（国际线路）**

| 套餐 | CPU / 内存 / 硬盘 | 流量 · 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| EB.TINYv2 | 1核 / 1G / 20G | 1T/月 · 1Gbps | $29.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.STARTERv2 | 1核 / 2G / 40G | 2T/月 · 2Gbps | $59.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.MINIv2 | 2核 / 2G / 60G | 3T/月 · 2Gbps | $89.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.MICROv2 | 4核 / 4G / 80G | 4T/月 · 4Gbps | $129.9/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.WEE | 1核 / 1G / 20G | 1000G/月 · 4Gbps | $36.90/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.TINY | 1核 / 1G / 20G | 2000G/月 · 4Gbps | $6.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.STARTER | 1核 / 2G / 40G | 4000G/月 · 10Gbps | $12.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.MINI | 2核 / 2G / 60G | 8000G/月 · 10Gbps | $21.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.MICRO | 4核 / 4G / 80G | 16000G/月 · 10Gbps | $32.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.MEDIUM | 4核 / 8G / 160G | 32000G/月 · 10Gbps | $49.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.LARGE | 8核 / 16G / 320G | 64000G/月 · 10Gbps | $99.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.GIANT | 8核 / 24G / 640G | 128000G/月 · 10Gbps | $199.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |

**东京 TYO.Pro / TYO.T1 / TYO.EB（TYO.T1 测试 IP 154.31.112.5）**

| 套餐 | CPU / 内存 / 硬盘 | 流量 · 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| Pro.TINY | 1核 / 1G / 20G | 500G/月 · 1Gbps | $21.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.STARTER | 1核 / 2G / 40G | 1000G/月 · 1Gbps | $39.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MINI | 2核 / 2G / 60G | 2000G/月 · 1Gbps | $79.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MICRO | 4核 / 4G / 80G | 4000G/月 · 1Gbps | $159.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MEDIUM | 4核 / 8G / 160G | 5000G/月 · 1Gbps | $259.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.WEE | 1核 / 1G / 20G | 1000G/月 · 4Gbps | $36.90/年 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.TINY | 1核 / 1G / 20G | 2000G/月 · 4Gbps | $6.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.STARTER | 1核 / 2G / 40G | 4000G/月 · 10Gbps | $12.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.MINI | 2核 / 2G / 60G | 8000G/月 · 10Gbps | $21.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| T1.MICRO | 4核 / 4G / 80G | 16000G/月 · 10Gbps | $32.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.TINY | 1核 / 1G / 20G | 1000G/月 · 1Gbps | $25.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.STARTER | 1核 / 2G / 40G | 2000G/月 · 2Gbps | $55.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.MINI | 2核 / 2G / 60G | 3000G/月 · 2Gbps | $85.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |
| EB.MICRO | 4核 / 4G / 80G | 4000G/月 · 4Gbps | $119.90/月 | [查看](https://www.dmit.io/aff.php?aff=9081) |

东京 EB 系列的价格放在同配置的 Pro 旁边，差距不算大，但 EB 的回程是 CMIN2、Pro 是 CN2 GIA。东京这两条线里，Pro 更值得考虑。

## 原生 IP 和住宅 IP 是两回事

原生 IP 指的是 IP 在 ARIN、APNIC 这类机构里的注册归属，显示为当地的本地 ISP 或运营商，而不是某个数据中心的网段。普通 VPS 查 IP 归属，经常看到 Amazon AWS、Cloudflare 这些名字；原生 IP 查到的是 Comcast、AT&T、Softbank 一类本地运营商。Netflix、Disney+ 这些平台的地区判定，第一步就看这个归属，所以原生 IP 的通过率明显高于数据中心广播 IP。

这里有两个概念经常被混在一起。独享 IP 说的是这个地址只分给你一个用户，不跟别人共用；原生 IP 说的是地址的归属属性。DMIT 的套餐基本是独享原生 IP，两个属性都占，但它们是独立的两件事，别当成同义词。

DMIT 的边界也要说清楚。它给的是注册地和机房一致的原生 IP，比数据中心广播段干净，在平台眼里更接近一个真实的本地用户。但这不等于家庭宽带的住宅 IP。如果你要做的是几十上百个账号的矩阵运营，需要的是一个可轮换的家庭宽带 IP 池，VPS 上的原生 IP 满足不了这种需求，那属于住宅代理服务的范畴，买 DMIT 是买错了东西。

## 实测：洛杉矶几乎全通过，香港差一截

公开测评里有一份洛杉矶节点的完整流媒体检测记录，IPv4 和 IPv6 都在线，系统是 Debian 12，跑在 AMD EPYC 9654 上。Netflix、Disney+、YouTube Premium、Amazon Prime Video、HBO Max、Hulu、Dazn、Peacock、Crunchyroll 全部返回 Yes 且地区为 US，ChatGPT、Google Gemini（USA）、Claude 也都是 Yes，Reddit、Steam 美区货币正常。没过的几项是 Spotify Registration（No）、Paramount+（报 406 错误）、MGM+（No）、Meta AI（No）、Starz（页面错误），Bing 地区判定标了 US (Risky)。

香港节点的情况要弱一些。Netflix HK、Disney+ HK、YouTube Premium HK、Amazon Prime Video HK 都通过，TVBAnywhere+ 不过，ChatGPT 显示只能用移动 App，Google Gemini 是 No，Claude 状态为 Unknown。想在香港机器上跑 ChatGPT 网页版的，这条要先知道。

硬件性能方面，两台实测机的 Geekbench 5 数据是这样的：

| 节点 | CPU | 内存 / 硬盘 | Geekbench 5 单核 / 多核 |
| --- | --- | --- | --- |
| 洛杉矶 | AMD EPYC 9654 96-Core，1 核 @2396MHz | 958.7 MiB / 21.0 GiB | 1437 / 1433 |
| 香港 | AMD EPYC 7C13 64-Core，1 核 @1996MHz | 960.6 MiB / 21.0 GiB | 940 / 946 |

单核 1437 放在 1 核 1G 的入门套餐上算不错，跑个轻量站点、代理转发、小脚本都够。香港的 940 低一截，但香港卖的是延迟不是算力。

流媒体解锁这件事有个前提：平台的风控名单一直在变，今天能过不代表三个月后还能过，商家本身也不做保证。买之前拿测试 IP 自己跑一遍检测脚本，比看任何测评都准。

## IP 被墙了怎么办：15 天一次免费换

这是国内用户最该提前知道的一条。DMIT 的政策是每 15 天可以免费申请更换一次 IP，其他时间换 IP 收 $5，走工单提交。也就是说，一个 IP 被封了不算灾难，等窗口或者花 5 美元就能换掉，成本可预期。

流量超额的规则要分开看。T1 系列超额后不停机，改成限速继续用，洛杉矶 T1 大约限到 100Mbps、香港和东京 T1 大约限到 50Mbps 这一档。Pro 和 EB 系列的超额限速低得多，第三方整理的套餐表里标在 2–10Mbps，香港部分套餐的表格直接写“超量暂停”。买之前在自己的商品页确认这一档的超额规则，别按 T1 的经验套到 Pro 上。

👉 [对照 DMIT 的 IP 更换条款与当前套餐价格](https://www.dmit.io/aff.php?aff=9081)

## Pro、Eyeball、Tier 1 的差别不在 IP，在回程路由

很多人把“IP 质量”和“线路质量”当同一件事，其实 DMIT 三条线给的 IP 属性是一样的，都是原生 IP，真正拉开差距的是回程走哪张网。

| 产品线 | 测试 IP | 去程 | 回程 |
| --- | --- | --- | --- |
| LAX.Pro | 154.17.2.2 | 电信联通 CN2 GIA，移动 CMI | 三网 CN2 GIA |
| LAX.sPro | 45.88.194.2 | 三网 Cloudflare Magic Transit 高防 | CN2 GIA |
| LAX.EB | 154.17.226.2 | 电信联通 CN2，移动 CMIN2 | 三网 CMIN2 |
| SJC.T1 | 174.136.205.2 | 电信 CT163，联通 AS4837，移动 CMI | 同去程，附 20Gbps 防御 |
| HKG.Pro | 103.117.100.2 | 电信 CN2 GIA，联通 AS9929，移动 CMI | 同去程 |
| HKG.EB | 154.3.32.3 | 电信联通绕日本 NTT，移动 CMI | 回程直连 |
| TYO.T1 | 154.31.112.5 | 电信联通 NTT，移动 CMI | 同去程 |

Pro 和 EB 之间还有一个不写在参数表里的差别：Pro 的 CN2 GIA 路由是锁定的，即便遇到攻击或者上游成本波动也不换路由；EB 的 CMIN2 在极端情况下可能被切换。对线路稳定性有硬要求、不能接受某天醒来路由变了的，这个差别值那点差价。

速度上的差距在晚高峰才显出来。公开测评里，电信方向 EB 单线程大约跑到 150Mbps，Pro 能稳在 180Mbps 左右；测评者的原话是“不要以为能拉 150Mbps 就觉得够用了，等晚高峰你就知错了”。移动方向受本地 QoS 影响更大，武汉移动千兆到 Pro 的实测落在 146–186Mbps 区间，波动来自运营商侧而不全是机房。这些是第三方单次测试的数字，不是官方带宽承诺，只当趋势看。

T1 的定位完全不同。它走国际线路，不做中国大陆优化，胜在便宜和带宽大，SJC.T1.WEE 一年 $36.9 就有 10Gbps 端口和 1T 月流量，还带 20Gbps DDoS 防御。你的访客主要在海外、或者只是拿它做落地和备份，T1 就够。

👉 [用年付价格开通 LAX.Pro，锁定 CN2 GIA 回程](https://www.dmit.io/aff.php?aff=9081)

## 年付、优惠码和退款：真实成本怎么算

年付限量款和月付正价款的差价很大。以洛杉矶 Pro 为例，WEE 限量款 $36.9 一年，折合每月约 3 美元；同样是 1 核，月付 TINY 是 $9.99/月，一年下来接近 120 美元。差价的来源不只是计费周期，还有配置：WEE 是 1G 内存、500G 月流量、500Mbps 带宽，TINY 是 2G 内存、1T 月流量、1Gbps 带宽。年付限量款更像是清库存的引流档，缺货就没了，续费时能不能保持同价，官方没有公开承诺，下单页会写明。

社区整理的优惠码目前有这些，全部需要结账时在 Promo Code 框里逐个试，能不能用、能用到哪一档，以实际校验结果为准：

- `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF`：洛杉矶 Eyeball 系列，季付及以上终身 8 折，不含月付
- `HKG-T1-ANNUALLY-45OFF-RECUR`：香港 T1 年付终身 5.5 折，同时给 CPU、内存、硬盘加量
- `2025-TYO-T1-HI-GSL-NON-MONTHLY-30OFF`：东京 T1 季付及以上终身 7 折
- `SJC-Unmetered-Annually-30OFF`：圣何塞不限流量方案年付 7 折
- `2025-XMAS-LAX-T1-10-OFF-RECURRING` / `2025-XMAS-LAX-T1-ANNUALLY-EXCL-WEE-TINY-20OFF-RECURRING`：洛杉矶 T1 的循环 9 折与年付 8 折

规律很清楚：折扣基本挂在季付和年付上，月付大多不参与，多个码也不能叠加。想省钱就把计费周期拉长。

退款方面，新购订单有 3 天退款窗口，条款里对已使用流量设了上限（第三方转述的数字是 30GB 以内），具体数值和申请方式在下单页的退款说明里核对，别只看二手整理。付款支持支付宝、微信、PayPal 和信用卡，国内用户不用绑境外卡。

## 谁不适合买 DMIT

三种情况建议直接排除。

只需要国际线路、访客不在中国大陆的，SJC.T1 或者 HKG.T1、TYO.T1 更划算，一年 $36.9 起，没必要为 CN2 GIA 付溢价。

需要大批量家庭宽带 IP 做账号运营的，原生 IP 解决不了问题，该去找住宅代理服务商。

预算卡得极死、只看单价的，DMIT 不是这个定位。它的价格在同配置里偏高，多出来的钱买的是回程路由和 IP 归属的干净度。

## 常见问题

**原生 IP 和独享 IP 是一回事吗？**
不是。独享说的是这个 IP 只给你一个人用，原生说的是 IP 的注册归属是本地运营商。DMIT 的套餐通常两个都满足，但概念要分开，别拿“独享”当“原生”的证明。

**DMIT 能解锁 Netflix 吗？**
洛杉矶节点实测 Netflix、Disney+、HBO Max、Hulu 都是美区通过，香港节点 Netflix HK、Disney+ HK 也通过。流媒体平台会随时调整封锁策略，商家不保证长期有效，买之前用测试 IP 自己验。

**流量超了会断网吗？**
T1 系列是限速继续用，不会停机。Pro 和 EB 的超额限速更低，香港部分套餐标注超量暂停。按自己那一档的商品页说明为准。

**香港和洛杉矶怎么选？**
华南地区到香港的延迟低得多，做面向大中华区的业务选香港。要美区 IP 解锁、做面向美国的站点或工具，选洛杉矶，价格还便宜一大截。

**支持哪些付款方式？**
支付宝、微信、PayPal、信用卡，工单是中文的。

## 最后怎么定

按需求对号入座就行：

- 只要原生 IP、预算优先：LAX.EB.WEE $39.9/年，或加 10 美元上 CORONA 拿 2Gbps 带宽
- 电信宽带、晚高峰也要稳：LAX.Pro.WEE $36.9/年起，长期用直接上月付 TINY
- 站被打过：LAX.sPro.CREATOR，去程有 5Tbps+ 高防
- 香港低延迟：HKG.Pro.TINY $39.9/月
- 纯国际业务：SJC.T1.WEE 或 HKG.T1.WEE，$36.9/年
- 流量吃不住上限：LAX.Pro 不限流量系列，30Mbps 起

下单前确认两件事：商品页上你选中那一档的实时价格和库存，以及优惠码在结账页是否真的校验通过。这两项都可能和本文写作时不同。

👉 [进 DMIT 官网核对价格并下单](https://www.dmit.io/aff.php?aff=9081)
