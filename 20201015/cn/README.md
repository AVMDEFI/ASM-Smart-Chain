# ASM Smart Chain发布
## ASM Smart Chain介绍
在ASM主链周年3.0版本迭代中，ASM主链升级聚焦支撑各类DAPP运转、孵化DEFI生态，最终达到生态应用百花齐放、百家争鸣。有别于ASM1.0聚焦主链记账和ATPOS、ASM2.0主链探索DAPP生态主要以自建客户端和提供开放接口为主，ASM3.0主链all in dapp & defi，拥抱开源生态和协议，以Metamask等开源钱包作为DAPP入口，遵循WEB3.0协议和技术栈，提供DEFI基础设施并为DEFI生态注入ASM特有的天然激励，ASM 3.0智能程度将远超过往版本，因此我们命名为ASM Smart Chain，即ASM智能链。

ASM智能链拥有卓越的性能，百万级并发处理能力。ASM智能链5秒钟急速出块，请求毫秒级确认，基于强一致性的共识算法，保证数据能够及时反馈并提高了数据的可靠性。智能合约的执行可能会阻塞交易功能，并给交易增加不确定性因素，因此将以太坊虚拟机（EVM）的可编程性和互操作性带入ASM智能链中，支持所有现有的以太坊工具，并具有更快的确定性和更便宜的交易费用。

ASM Smart Chain账户地址解释说明
![Image text](https://img-blog.csdnimg.cn/20190325161324784.png)

ASM Smart Chain账户地址中有实际意义是是后20位（16进制，即40个数字与字母组合）

【ASM开头，长度为43】在长度为43的数字与字母组合ASM账户体系中，前3位为ASM，后40位为账户地址；

【0x开头，长度为42】为兼容web3应用，ASM账户地址亦表现为以0x开头加40位账户地址的长度为42的账户地址。

上述两种地址在AWallet均兼容通用，在Metamask钱包等只显示为42位地址，在中心化交易所（如ZT）只显示为43位地址。

## 使用Metamask钱包连接ASM Smart Chain
详见教程

电脑版
http://shafheqinvieqni.oss-accelerate.aliyuncs.com/metamask-for-chrome-on-ASM-Smart-Chain.pdf

手机版
http://shafheqinvieqni.oss-accelerate.aliyuncs.com/metamask-for-mobile-on-ASM-Smart-Chain.pdf

## ASMSwap - ASM Smart Chain上第一个去中心交易所
使用Metamask访问https://swap.asm.am

理解ASMSwap的AMM自动做市机制https://www.zhihu.com/question/406610359/answer/1356131135

ASMSwap需要配合Metamask使用

手机操作教程：http://shafheqinvieqni.oss-accelerate.aliyuncs.com/how-to-use-ASMSwap.pdf

电脑版操作教程：http://shafheqinvieqni.oss-accelerate.aliyuncs.com/how-to-use-ASMSwap-on-PC.pdf

## GIFT - 献给ASM社区成员的ASM一周年礼物
GIFT Token 

供应总量100,000枚，0预挖、0私募、0预留，

发行方式：100%代币与ASM 1:1投入ASMSwap流动池

即初始代币提供(50/50):100,000 $ASM/100,000 $GIFT（初始流动性池永久冻结，即GIFT对ASM兑换比例永远大于1ASM）

发行时间2020.10.20 18:00(UTC+8)

GIFT Token为ASM公链的周年纪念币，是ASM公链DeFi生态的首发币，对整个生态有着重要的意义，在后续ASM DeFi生态建设过程中，将会不断为GIFT赋能，让其拥有更多的价值和意义。

参与前建议了解AMM自动做市协议，GIFT代币价格由AMM自动做市协议决定：

(1)GIFT代币价格=流动性池中ASM总量/流动性池中GIFT代币总量，代币价格仅供参考，兑换时会有兑换滑点。

(2)兑换前后流动性池的代币余额乘积不变=$ASM的数量*$GIFT的数量=（初始流动性）100,000 $ASM*100,000 $GIFT=10,000,000,000

举例说明（注：以下推演未含0.3%交易手续费）

GIFT初始价格=100,000 $ASM/100,000 $GIFT=1ASM.

假设第一笔使用1000个ASM兑换GIFT，则可兑换得的GIFT数量=100,000 $GIFT-100,000 $ASM*100,000 $GIFT/(100,000+1,000)$ASM=990.09901 $GIFT

兑换后GIFT代币价格=流动性池中ASM总量/流动性池中GIFT代币总量=101,000 $ASM/99,009.901 $GIFT =1.02 ASM

假设第二笔使用10,000个ASM兑换GIFT，则可兑换得的GIFT数量=99,009.901 $GIFT-101,000 $ASM*99,009.901 $GIFT/(101,000+1,0000)$ASM=8919.80991 $GIFT

兑换后GIFT代币价格=流动性池中ASM总量/流动性池中GIFT代币总量=111,000 $ASM/90,090.09 $GIFT =1.2321 ASM

假设第三笔交易为将第一笔兑换所得的的990.09901 $GIFT兑换回ASM，则可兑换得ASM的数量=111,000 $ASM-111,000 $ASM*90,090.09 $GIFT/(90,090.09+990.09901)$GIFT=1206.639 $ASM，则第一笔兑换者的利润为206.639 $ASM，扣除兑换手续费约2000*0.3%=6 $ASM的损耗，利润约200 $ASM。

## ASM智能链DEFI讨论群 $GIFT 

Telegram进群链接https://t.me/ascdefi

币用进群链接https://0.plus/ascdefi
