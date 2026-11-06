# greencloudvps评测：东京三网直连的真实口碑，$6/月起的Budget KVM怎么选，限制和退款政策一次讲清

搜“greencloudvps评测”的人，通常卡在两个问题上：这家 2013 年成立的老牌 VPS 商到底靠不靠谱，以及它跟搬瓦工这类常被推荐的选择比，值不值得下单。先把结论放在前面：绿云（GreenCloudVPS）的强项是低月付、10Gbps 大端口和 30 多个机房位置；短板也很明确，特价套餐不退款、亚太机房流量减半、热门位置（比如东京）常年缺货。它适合当工具机、建站备机，或者预算有限的轻量应用；如果你的决策依赖“买了不合适能退”，下单前需要多看一眼条款。

> **选购速览**：绝大多数找低价 Linux VPS 的读者，看 Budget KVM 系列就够了，官方月付 **$6 起**（1 核 / 1GB / 15GB SSD / 1.5TB 流量 / 10Gbps 端口），促销期年付能压到几十美元。需要 Windows 环境的话，Budget Windows VPS 从 $8/月起。注意：Budget KVM Sale 系列标注不退款。👉 [查看 Budget KVM 当前价格和各机房库存](https://greencloudvps.com/billing/aff.php?aff=6679)

## GreenCloudVPS 是一家什么背景的主机商

GreenCloudVPS（圈内常称“绿云”）是一家在美国特拉华州注册的 LLC，2013 年成立，私人持有，自有全部硬件和网络设备，并且是 ARIN、APNIC、RIPE 的成员。这两点在低价 VPS 商里不算常见——很多同价位商家是租用上游资源转售，绿云是自己持网。

规模方面，官方数据显示它在三大洲运营约 30 个数据中心位置，总网络容量超过 600Gbps，上游接入包括 Arelion、Lumen、NTT、SoftBank、IIJ、Telstra 这类 Tier-1 运营商。2013 年它拿过 LowEndTalk 的 "#1 Top Provider" 和 "#1 Most Stable Provider" 两个社区奖项，这也是各篇第三方评测反复引用的背书。

需要一并说清的是服务模式：所有套餐均为 unmanaged（无托管），商家只保证物理服务器和正常运行时间，软件层面的问题不负责处理。官方给出的 24/7 工单平均响应时间是 9 到 12 分钟——FAQ 里两处数字不一致，但量级上和用户在论坛里反馈的“几分钟回复”基本对得上。

## 全套餐对比：各产品线和价格

绿云的产品线不少，官网商城当前挂着 15 个类别。价格信息最完整、也是大多数读者真正会买的两条线，是 Budget KVM 和 Budget Windows VPS。

**Budget KVM VPS（官方标准价格，月付）：**

| 套餐 | 内存 / 硬盘 | CPU | 流量 | 月付价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| SSDKVM-1 | 1GB / 15GB SSD | 1 核 | 1.5TB | $6/月 | [ 购买 SSDKVM-1](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-2 | 2GB / 15GB SSD | 1 核 | 2TB | $10/月 | [ 购买 SSDKVM-2](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-3 | 4GB / 30GB SSD | 2 核 | 4TB | $20/月 | [ 购买 SSDKVM-3](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-4 | 8GB / 60GB SSD | 4 核 | 8TB | $40/月 | [ 购买 SSDKVM-4](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-5 | 16GB / 120GB SSD | 8 核 | 12TB | $80/月 | [ 购买 SSDKVM-5](https://greencloudvps.com/billing/aff.php?aff=6679) |

全系 10Gbps 端口、1 个 IPv4 + IPv6、1 次免费备份/快照，仅支持 Linux。**亚太机房（日本、新加坡、香港等）流量直接减半**：五档分别只有 750GB / 1TB / 2TB / 4TB / 6TB，这一点选亚洲机房前必须算清楚。

**Budget Windows VPS（Windows Server 2022，1Gbps 不限流量）：** US1（1 核 1GB / 25GB SSD）$8/月起，中间档 US2 到 US5 依次 $16、$24、$32、$40，顶配 US6（6 核 6GB / 120GB SSD）$48/月。官方页面明确写了允许 Hitleap/Jingling 这类流量工具，做挂机、刷流量工具的目标用户可以留意。👉 [查看 Budget Windows VPS 全部档位](https://greencloudvps.com/billing/aff.php?aff=6679)

**其余产品线一览**（多数未在公开页面完整标注价格，以下单页实价为准）：

- **Budget KVM Sale / Premium KVM Sale / Storage KVM Sale**：定期补货的特价系列，配置和位置每次开仓都不同，年付特价是绿云的主要玩法
- **Ryzen KVM VPS**：NVMe 盘，美国节点 10Gbps 端口，配置从 1 核 1GB/15GB 到 8 核 16GB/150GB；新加坡 DC2、香港 DC2 和东京为 1Gbps 端口
- **CN Premium Optimized**：从命名看面向中国方向线路优化，具体配置和价格需进商城查看
- **EPYC Cloud Resources、Managed Windows VPS、SEO Optimized VPS、10Gbps Windows VPS、Forex VPS、MAC VPS、Mac Mini Dedicated、Semi/Dedicated Proxies**：各有专门用途，按需进商城看
- 配置升级按量加价：内存 $3/GB/月、CPU $3/核/月、硬盘 $3/10GB/月（在资源可用前提下）

还有一个买前要知道的细节：Budget KVM Sale 各位置的硬件差异很大。近期查看官网库存页面，EPYC + NVMe 的新位置（Ashburn、Ogden、多伦多、洛杉矶、阿姆斯特丹等）基本全部售罄，有货的是 Chicago DC2、San Jose、Phoenix、Jacksonville、Kansas City、Dallas 这些 **E5v4 + SATA SSD** 的老配置位置。同样是"Budget KVM"，你拿到的可能是 5950X 级别的 NVMe 机，也可能是性能弱一截的老平台，下单前看清楚位置标注。👉 [查看各位置当前库存和硬件配置](https://greencloudvps.com/billing/aff.php?aff=6679)

## 东京机房：三网直连是真的，晚高峰有代价

绿云在国内用户中的口碑，很大程度建立在东京机房上。多轮中文实测的结论比较一致：东京机房走 IIJ 网络（部分分配到软银 BBTEC 线路），电信、联通、移动三网去程都是 IIJ 直连，回程电信联通走 IIJ、移动走 IIJ 或 Telstra，延迟在同类美国商家里属于第一梯队。硬件方面，此前实测记录里东京用的是 AMD Ryzen 9 5950X 加 NVMe、10Gbps 带宽，跑建站这类负载相当够用（每次开仓的具体硬件以下单页标注为准）。

代价也要说清楚。实测记录里提到两点：一是晚高峰丢包率会升高，白天顺畅不等于晚上同样稳；二是有用户反映资源跑满会被限制，而且官方明确禁止挖矿、禁止 DD WIN（即通过 DD 镜像装 Windows）。想拿它挖矿或者绕过 Linux 限制的，可以省下这笔钱了。

另一个现实问题：东京的 Ryzen KVM 在近期查看库存时显示全部售罄（0 Available），新加坡 DC2 和香港 DC2 有货但只有 1Gbps 端口。热门亚太位置“看得到买不到”是绿云的常态，它的促销模式就是定期开仓补货，卖完即止。

## 补货节奏：绿云真正的购买逻辑

理解绿云，要按“开仓”来理解，而不是按“随时下单”。它的特价套餐集中在几个时间点放货：周年庆（10 月）、黑五，以及不定期的一次性补货。举例来说，2026 年 10 月就有一轮多机房补货，东京 IIJ、东京软银、香港 DC1、新加坡 DC2 和英国考文垂同时上架 Premium KVM Sale，入门档 1 核 EPYC / 2GB / 25GB NVMe / 750GB 流量 / 10Gbps，年付 $25；东京和香港的中配是 2 核 3GB / 35GB / 1TB，年付 $35。

这轮补货里还有几个只有对比过才会发现的门道：

- **东京软银和东京 IIJ 是两条不同线路**，同配置同价格，但去程回程路由不同，对电信、联通、移动的表现要分别测，别默认“东京都一样”。
- **同价位的流量差距巨大**：英国考文垂同样 2GB 内存年付 $25，流量给到 3TB，而东京、香港 DC1、新加坡 DC2 对应型号只有 750GB。亚太机房的直连价值是用流量换的。
- **IPv6 分配也不统一**：新加坡 DC2 是 /112，东京、香港 DC1 是 /64，介意 IPv6 地址段的用户要留意。

第三方测评还记录过一个更典型的例子：新加坡的"2222"活动套餐（2 核 EPYC / 2GB / 22GB NVMe / 750GB），年付 $22、三年付 $60，只在周年庆和黑五上架；非活动期买不到，替代方案起步 $25 年付，配置略有出入。也就是说，同一类套餐在活动期和非活动期的价格、配置都会变，看到补货时先把页面存下来再慢慢对比。

## 三条容易被忽略的限制，买前必须知道

**第一，Budget KVM Sale 系列不退款。** 官方购物车页面对这个系列的每一个套餐都标注了 "No refund/Money back on this plan"。绿云的通用退款政策只覆盖新客户的第一台 VPS、购买后 7 天内，而且特别折扣套餐明确不适用。也就是说，你在促销页买的特价机，基本没有退款兜底。这一点大量评测文章都没写清楚，但它恰恰是低价套餐里最重要的条款。👉 [下单前确认所选套餐的退款标注](https://greencloudvps.com/billing/aff.php?aff=6679)

**第二，亚太流量减半加机房细节。** 前面提到 APAC 流量只有欧美的一半，新加坡 DC1 的特价套餐里连 4GB 内存档也只有 750GB 流量。这些差异都只写在具体的套餐页里，不对比根本看不出来。

**第三，账单信息不实会卡开通。** 支付方式覆盖 PayPal、信用卡、支付宝、银联和加密货币，对国内用户很友好。但官方说明账单信息不准确可能触发反欺诈系统，开通会延迟；新客户用信用卡或 PayPal 首次支付需要一次性验证。正常开通通常 15 分钟内完成，最长可能到 2 小时——别在高峰期下单之后五分钟就开始找客服。

## 和搬瓦工比，什么人该选谁

中文圈买 VPS 绕不开搬瓦工，两者的定位差异其实很清晰。以第三方对比资料中列出的价格：搬瓦工 CN2 GIA-E 起价 $49.99/季，THE PLAN 限量版 $99/年覆盖 18 个机房；绿云的 Budget KVM 月付 $6 起，特价年付的第三方口径在 15 美元到 25 美元之间（不同促销期、不同位置价格不同，以下单页实价为准）。

按场景拆开看：追求中国方向线路质量天花板（CN2 GIA 级别回程）、预算在百美元级别的，搬瓦工的方案确实更对路；预算卡在每年几十美元、要大带宽和多机房选择、能接受“补货式购买”的，绿云的性价比更突出。两家的特价套餐都是卖完即止，谁家都不保证随时有货。

用户评价方面也说句实话：HostAdvice 上 86 条用户评价里，有用户反馈所购 VPS 出现严重丢包和高抖动、提交完整诊断后仍无法解决；而 LowEndTalk 社区的长期口碑和快速工单回复又是另一个方向的记录。这种分歧和机房、线路强相关——新加坡 DC1 有实测跑出接近 8Gbps 本地带宽、单核 Geekbench 6 超过 1200 分的记录，而同一个商家其他位置可能出现完全不同的网络表现，别把单一机房的口碑套用到全部位置上。

## 下单前的最后确认

按情况给个直接的建议：

- 只需要一台便宜的 Linux 工具机、跑脚本或轻量建站 → Budget KVM 的 SSDKVM-1 到 -2 档足够，$6–$10/月
- 想要更好的单核性能和 NVMe → 等 Premium KVM Sale 或 Budget KVM Sale 的 EPYC/NVMe 位置补货（周年庆、黑五是主要时间点），别急着买老平台的 SSD 位置
- 需要 Windows Server、做挂机或流量工具 → Budget Windows VPS，$8/月起
- 严格预算且要求退款保障 → 换一家有常规退款政策的商家，绿云特价套餐没有这个选项

下单时用支付宝或银联都可以，记得账单信息如实填写；买特价套餐前再看一眼位置页面的硬件标注、线路（东京要分清 IIJ 和软银）和库存数。👉 [用支付宝开通一台绿云 VPS](https://greencloudvps.com/billing/aff.php?aff=6679)

## FAQ

**GreenCloudVPS 支持支付宝付款吗？**

支持。官方列出的支付方式包括 PayPal、信用卡/借记卡、支付宝、银联、加密货币（BTC/ETH/BNB/USDT 等）以及美英欧银行转账。新客户首次使用信用卡或 PayPal 需要完成一次支付方式验证。

**绿云的 KVM 套餐能装 Windows 吗？**

不能。Budget KVM 和 Ryzen KVM 全系仅支持 Linux 操作系统，且官方明确禁止通过 DD 镜像方式装 Windows。需要 Windows 有专门的 Budget Windows VPS 产品线，预装 Windows Server 2022，$8/月起。

**绿云适合建站吗？**

适合，尤其是东京机房。三网去程 IIJ 直连、Ryzen 9 5950X 级别硬件加 NVMe 的配置跑中小型网站没有压力，10Gbps 端口在同价位里少见。但要注意晚高峰丢包率升高的实测记录，以及全系套餐只有 1 次免费备份/快照——重要数据需要自己做异地备份。

**特价套餐买错了能退吗？**

基本不能。Budget KVM Sale 等特价系列在购买页明确标注不退款，官方 7 天退款政策仅适用于新客户的第一台常规 VPS。下单前确认清楚位置、配置和流量额度再付款。
