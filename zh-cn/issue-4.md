# 无聊科技正经事（第4期）：理性囤货与人工智能预测

> 作者: 潘深练
>
> 日期: 2022年4月27日

这里记录每周值得分享的科技内容，周三发布。

本刊开源（GitHub: [senlypan/weekly](https://github.com/senlypan/weekly)），欢迎投稿，推荐或自荐文章/软件/资源，请[提交 issue](https://github.com/senlypan/weekly/issues) 。

## 封面图

![封面图](https://weekly.panshenlian.com/_media/images/2022/issue-4/cover.jpg)

位于曼哈顿的 84 层豪华公寓楼施坦威大厦的高宽比为 24:1，正式成为世界上最薄的摩天大楼，大楼如此 “瘦”，可能会在空中摇摆。([via](https://www.odditycentral.com/architecture/worlds-thinnest-skyscraper-is-so-skinny-it-may-sway-in-the-air.html))

## 本周话题：理性囤货与人工智能预测

这两天，周围有一些囤货的声音。

![话题](https://weekly.panshenlian.com/_media/images/2022/issue-4/topic-001.jpg)

而在声音之外，我对恐慌式囤货，有一些猜想：

- 其一，是部分人对供应链的不信任
- 其二，是不实消息肆无忌惮的传播

换而言之，要消除非理性囤货的恐慌，我们可能需要解决两个问题：

- 第一，保障供应链
- 第二，阻断谣言

这样一来，问题好像就变成：

- 如何了解供求关系？
- 如何识别谣言？

而最终面对的这两个问题，对于 **人工智能** 来说，好像是有解的。我们先来了解两个研究报告：

![话题](https://weekly.panshenlian.com/_media/images/2022/issue-4/topic-002.jpg)

（1）[《使用推文预测实时粮食短缺》](https://www.psu.edu/news/agricultural-sciences/story/using-tweets-predict-real-time-food-shortages/)

宾夕法尼亚州大学公园——宾夕法尼亚州立大学和宾夕法尼亚州立大学的研究人员表示，推特上的推文所表达的 **情绪和情感** 可以被实时用来 **评估** 大流行病、战争或自然灾害 **供应链中断** 可能导致的粮食短缺。 

六个月时间，研究人员通过分析约 120 万条密切相关的推文，使用所谓的上下文语言模型来提取每条推文中的情绪和情感，包括愤怒、厌恶、恐惧、喜悦、悲伤、惊讶、兴奋等。

他们发现，在 COVID-19 大流行初期，表达愤怒、厌恶和恐惧情绪的推文与官方报告的实际地区粮食不足率密切相关。研究人员表示，这些发现有可能用于开发低成本的早期 **预警系统**，以确定最需要粮食安全干预措施的地方。 

![话题](https://weekly.panshenlian.com/_media/images/2022/issue-4/topic-003.jpg)

（2）[《使用递归神经网络从微博中检测谣言》](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5633&context=sis_research) 与 [《使用双向图卷积网络在社交媒体上进行谣言检测》](https://ojs.aaai.org/index.php/AAAI/article/view/5393)

社交媒体是散布谣言的理想场所，因其传播新信息的性质而在公共领域迅速发展，导致谣言四处流传，**自动辟谣** 是一个关键问题，从社交媒体的海量信息中发现谣言正成为一项艰巨的挑战。

因此，一些深度学习方法被用于检测谣言，两篇论文中使用了两种不同的检测模型，例如 **递归神经网络（RvNN）** 、 **双向图卷积网络（Bi-GCN）** ，根据社交平台的数据集和谣言特征，从谣言的传播方式和传播模式等方面，快速、准确地检测谣言。

![话题](https://weekly.panshenlian.com/_media/images/2022/issue-4/topic-004.jpg)

（[via](https://zhuanlan.zhihu.com/p/342413803)）

总之，人工智能可以在很多方面发挥作用，有助于早期预警干预供应链，一定程度上缓解囤货恐慌，但问题的发展往往是复杂的。因此，我们应该结合实际，科学分析。

## 科技动态

1、[马斯克440亿美元收购推特](http://mp.weixin.qq.com/s?__biz=MjM5OTYyNzAyMA==&mid=2650210031&idx=2&sn=888465c3ef2ce87b64c9af92afdf0c1e&chksm=bf3ace8c884d479a1564604309753fddd86346cf823f5400aa9969983d8ae2e3ede81da97100&scene=27#wechat_redirect)（中文）

![马斯克](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-017.jpg)

([via](https://www.tmz.com/2022/04/25/elon-musk-new-owner-twitter-43-billion-offer-accepted/?adid=social-twa))

当地时间 4 月 25 日，社交媒体平台推特公司接受了埃隆·马斯克的收购协议。根据协议，马斯克将以每股 54.2 美元，总计约 440 亿美元的价格收购推特。

![马斯克](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-016.jpg)

多年来，Twitter 一直在努力实现有意义的业务增长，但其股价几乎与 2013 年持平，该公司最近的价值约 350 亿美元，而马斯克总约 2600 亿美元。

![马斯克](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-015.jpg)

([via](https://twitter.com/Saagarshinde8/status/1518823733171003393/photo/1))

马斯克表示他希望将 Twitter 私有化，他认为这将使该平台能够通过替代方案和 **开源算法** 更好地服务于言论的 “社会需求” 。

2、[日本研究人员研制出电动筷子以增强咸味](https://www.reuters.com/lifestyle/science/japan-researchers-develop-electric-chopsticks-enhance-salty-taste-2022-04-19/)（英文）

![日本研究人员研制出电动筷子以增强咸味](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-002.jpg)

日本研究人员研发出可增强咸味的电脑筷子，可能有助于那些需要减少饮食中钠含量的人。

这款筷子由明治大学教授 Homei Miyashita 和饮料制造商 Kirin Holdings Co. (2503.T) 共同研发，通过电刺激和佩戴在腕带上的迷你电脑来提升口味。

![日本研究人员研制出电动筷子以增强咸味](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-001.jpg)
![日本研究人员研制出电动筷子以增强咸味](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-003.jpg)

Miyashita 说，该设备使用 **微弱的电流** 将食物中的 **钠离子** 通过筷子传输到嘴巴，在那里它们会产生咸味。

3、[一辆特斯拉在智能召唤模式下撞上价值高达 350 万美元的私人飞机](https://www.theverge.com/2022/4/22/23037654/tesla-crash-private-jet-reddit-video-smart-summon)（英文）

![特斯拉](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-004.jpg)
![特斯拉](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-005.jpg)
![特斯拉](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-005-1.jpg)

上周五，一辆特斯拉似乎在其自动驾驶智能召唤模式下撞上了一架价值 300 万至 350 万美元的私人飞机（**尾翼**），致使飞机原地旋转了 90 度。

![特斯拉](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-006.jpg)

([Model Y](https://www.tesla.com/modely))

Smart Summon（[智能召唤](https://www.tesla.com/ownersmanual/modely/is_is/GUID-6B9A1AEA-579C-400E-A7A6-E4916BCD5DED.html)）是通过使用手机 GPS 作为目标目的地，用户可以定位或选择指定位置，让 Model Y 根据需要进行行驶和停车，这确实在需要移出狭窄的停车位、穿过水坑或其他简单移动的场景下很有帮助。

![特斯拉](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-007.jpg)

当然，特斯拉也列举了很多注意项和警告项，并且强调 “智能召唤” 是 BETA feature （测试版功能），在使用期间需要自己密切监视车辆和周围环境。

总之，购买 Model Y 的伙伴，值得一试。

4、[JDK 19 将于 9 月发布](https://www.infoworld.com/article/3653331/jdk-19-the-features-targeted-for-java-19.html)（英文）

![JDK19](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-008.jpg)

Java Development Kit 19 将于今年 9 月发布，现在正式提出了第二个针对它的特性：用于表达向量计算的 Vector API ，它将在下一个 Java 版本中进行第四次孵化。另一个提议的功能是将 JDK 移植到开源 Linux/RISC-V 指令集架构 (ISA)。

最近关于开源 Linux/RISC-V 指令集架构 (ISA) 的热度不低，值得持续关注。

5、[“过时”的 iphone 应用即将被 App Store 踢出/下架](https://www.theverge.com/2022/4/23/23038870/apple-app-store-widely-remove-outdated-apps-developers)（英文）

![iphone](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-009.jpg)

最近，部分开发者收到标题为 “应用程序改进通知” 的邮箱：

![iphone](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-012.jpg)

苹果警告称，它将从 App Store 中删除 “在很长一段时间内没有更新” 的应用程序，并给开发者 30 天的时间来更新它们。

但是，该强制通知引起一些争论。

![iphone](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-010.jpg)

▲ 许多应用程序制造商，如 Protopop Games 开发商 Robert Kabwe，表达了他们对这一变化的担忧，Kabwe在 Twitter 上表示，苹果威胁要删除他的全功能游戏 Motivoto，因为它自 2019 年 3 月以来一直没有更新。

![iphone](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-011.jpg)

▲ 与此同时，FlickType Apple Watch 键盘的开发者 Kosta Eleftheriou 表示，由于两年没有更新，Apple 取消了他专为视障人士设计的应用程序版本。正如 Eleftheriou 在他的推文中指出的那样，曾经超级流行的 Pocket God 应用程序仍然保留在 App Store 中，尽管它在 2015 年获得了最后一次更新。开发人员 Emilia Lazer-Walker 还报告称苹果正在删除她的 “一些” 来自 App Store 的旧游戏。其他几位开发人员也有同样的经历，并指出他们只是没有时间更新他们的应用程序。

![iphone](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-013.jpg)

▲ 我发现在苹果官方的 [App Store 改进页面上](https://developer.apple.com/support/app-store-improvements/)，苹果公司表示：“我们正在实施评估应用程序的持续流程，删除不再按预期运行、不遵循当前审查指南或已过时的应用程序。” 页面上由于没有发布日期，因此无法清楚苹果是何时发布的，或者上次更新该帖子是什么时间。

但无论如何，苹果的这个强制通知，我个人觉得有利有弊，对于苹果市场来说是一个淘汰、激活和升级推动，但对于部分开发者来说，可能会直接断送应用，毕竟有些应用根本就没有规划新功能。

6、[英国率先推出“无人驾驶”巴士，开始在爱丁堡公园电车和火车换乘路线上进行测试](https://www.edinburghnews.scotsman.com/lifestyle/travel/uk-first-as-driverless-bus-begins-testing-on-edinburgh-park-tram-and-train-interchange-route-3666306) 

![无人驾驶](https://weekly.panshenlian.com/_media/images/2022/issue-4/keji-014.jpg)

▲ 苏格兰最新的公共汽车将自动驾驶，成为英国第一辆上路的全尺寸自动驾驶汽车。

巴士集团 Stagecoach 将从周一开始对其自动驾驶巴士进行道路测试，为今年夏天晚些时候上车的乘客做好准备。该公司在苏格兰的区域总监 Sam Greet 认为：“ 这是一个非常令人兴奋的项目，是我们在全面推出英国首个全尺寸自动驾驶巴士服务的过程中向前迈出的重要一步，并将提供前往苏格兰中心全新巴士路线的便捷通道。”

## 灵感

1、[Google Docs 自动生成摘要](https://ai.googleblog.com/2022/03/auto-generated-summaries-in-google-docs.html)（英文）

![Google Docs 自动生成摘要](https://weekly.panshenlian.com/_media/images/2022/issue-4/linggan-001.jpg)

[Google AI](https://ai.googleblog.com/) 最近宣布，Google Docs 现在会自动生成建议，在文档编写者有需要的时候帮助他们创建内容摘要。

简单来说，就像我们以前学语文的时候，老师让我们总结中心思想。

我个人觉得这个 AI 技能有点恐怖，这个可不像机器翻译只是简单的根据文本信息然后通过 AI 模型做自然语言处理，而是要通读全文，理解读者场景语义特征等等（我猜的），最终提炼出全文的中心思想创建成一段核心概要，这过程极其复杂，但是人工智能和大数据，毕竟在 Google 这里一直就很前沿，所以正常。

我试了很久，没有试出来这个功能，而且我怀疑目前仅仅支持英文，毕竟不同语言差异性很大。当然，如果有小伙伴试出来了，欢迎分享一下过程。 

2、[东京一家特别的 "写稿咖啡馆"](https://www.odditycentral.com/travel/unique-tokyo-cafe-only-serves-struggling-writers-working-on-tight-deadlines.html)（英文）

![一家只为赶稿作家提供服务的东京咖啡馆](https://weekly.panshenlian.com/_media/images/2022/issue-4/linggan-002.jpg) 

店主河合拓哉发推文：“手稿写作咖啡馆，只允许有写作期限的人光临！这是为了在咖啡馆保持一定程度的专注和紧张的气氛！谢谢你的理解。”

![一家只为赶稿作家提供服务的东京咖啡馆](https://weekly.panshenlian.com/_media/images/2022/issue-4/linggan-003.jpg) 

这家咖啡馆仅在几天前开业，按使用时间向顾客收费（每 30 分钟收费 150 日元或 1.32 美元），并配备 USB 端口、电脑支架和免费 Wi-Fi。苦苦挣扎的作家也可以自己带食物和饮料，或者因为咖啡和水是唯一可用的东西，所以将它们送到那里，但在实际写作方面非常严格。

![一家只为赶稿作家提供服务的东京咖啡馆](https://weekly.panshenlian.com/_media/images/2022/issue-4/linggan-004.jpg) 

Manuscript Writing Cafe （手稿写作咖啡馆）所在的空间实际上是一个名为 Koenji Sankakuchitai的录音和广播工作室。咖啡馆本身只有在工作室不营业的时候才开放，所以你不可能每天都去。然而，河合拓哉保证会经常宣布咖啡厅的下一个营业日期。比如本月，手稿写作咖啡厅将在下一个20号开放。

![一家只为赶稿作家提供服务的东京咖啡馆](https://weekly.panshenlian.com/_media/images/2022/issue-4/linggan-005.jpg) 

日本对有时会激发全球潮流的另类咖啡馆并不陌生。还记得猫（主题）咖啡馆吗？这种流行趋势起源于亚洲国家，女仆咖啡馆、猫头鹰咖啡馆、爬行动物咖啡馆，甚至还有专门针对女性大腿的咖啡馆。这些只是少数几个例子，实际上，日本已经提出了许多有趣的咖啡馆概念，并且不知何故不断提出新的概念，本文就是最新的例子：东京高圆寺社区的手稿写作咖啡馆，特点是只欢迎努力赶稿的作家。 

## 文章

1、[关于工程师写作这件事](https://www.heinrichhartmann.com/posts/writing)（英文）

![关于工程师写作这件事](https://weekly.panshenlian.com/_media/images/2022/issue-4/article-002.jpg)

([via](https://zhuanlan.zhihu.com/p/85484159))

写作是高级软件工程师职业发展所需的一项重要技能。本文包含有关如何成为更好、更有生产力的作家的技巧。它涵盖了写作前要考虑的事情，如何写好，以及如何练习写作。

写作很难，但在大型组织中可能会是产生影响的关键。作为一名高级软件工程师，写作是你必须掌握的最重要的技能，以扩大你在团队之外的影响力，并推进你的职业生涯。

2、[如何在 Java 中生成特定范围内的随机整数？](https://stackoverflow.com/questions/363681/how-do-i-generate-random-integers-within-a-specific-range-in-java)（英文）

![生成特定范围内的随机整数](https://weekly.panshenlian.com/_media/images/2022/issue-4/article-001.jpg)

这是一个 stackoverflow 上一个高赞问答，提问者想知道如何在 Java 中生成特定范围内的 int 类型随机值，他尝试了几种方法，但都出现错误。

**尝试1：**

```java
randomNum = minimum + (int)(Math.random() * maximum);
```

错误：随机结果会出现 **大于** maximum 的情况！

**尝试2：**

```java
Random rn = new Random();
int n = maximum - minimum + 1;
int i = rn.nextInt() % n;
randomNum =  minimum + i;
```

错误：随机结果会出现 **小于** minimum 的情况！

**最后，** 有位高赞网友解释，在  Java 1.7 或更高版本中，使用 [ThreadLocalRandom.current().nextInt](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/concurrent/ThreadLocalRandom.html#nextInt(int,int)) : 

```java
import java.util.concurrent.ThreadLocalRandom;
int randomNum = ThreadLocalRandom.current().nextInt(min, max + 1);
```

而在 Java 1.7 之前，建议仍使用 [java.util.Random.nextInt](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Random.html#nextInt(int)) ，特别是在实践中，java.util.Random 类通常比 java.lang.Math.random() 更可取：

```java
import java.util.Random;
public static int randInt(int min, int max) { 
    Random rand;
    int randomNum = rand.nextInt((max - min) + 1) + min;
    return randomNum;
}
```

当然，这个问答下面还有其他一些网友也提供了很多不同的方案，例如有位网友提出实现一种标准方案，使用了 Java Math 库中的函数 Math.random()：

```java
Min + (int)(Math.random() * ((Max - Min) + 1))
```

或许你也可以看看，关于各种方案对单精度、双精度的讨论中，是否有一种是你平时使用的方案？你的方案是否也存在精度错误问题？

3、[Googel AI 推出一个用于目标检测的语言建模框架——Pix2Seq](https://ai.googleblog.com/2022/04/pix2seq-new-language-interface-for.html)（英文，附论文）

![Googel](https://weekly.panshenlian.com/_media/images/2022/issue-4/article-003.gif)

最近，Googel AI 研究科学家提出了一种简单通用的方法，可以从完全不同的角度处理目标检测。研究结果发表在 [ICLR 2022](https://iclr.cc/) 。

![Googel](https://weekly.panshenlian.com/_media/images/2022/issue-4/article-004.jpg)

▲ 详见论文 [《 Pix2Seq: A Language Modeling Framework for Object Detection 》](https://arxiv.org/pdf/2109.10852.pdf)。

![Googel](https://weekly.panshenlian.com/_media/images/2022/issue-4/article-005.jpg)

▲ Pix2Seq 可以检测人口密集和复杂场景中的目标对象。相比现有的 [Faster R-CNN](https://arxiv.org/abs/1506.01497) 和 [DETR](https://alcinos.github.io/detr_page/) ，Pix2Seq 在大规模目标检测 [COCO](https://cocodataset.org/#home) 数据集上取得了有竞争力的结果，并且可以通过在更大的目标检测数据集上预训练模型来进一步提高其性能。

4、[Java加密漏洞PoC代码公开，受影响的版本需尽快升级](https://www.freebuf.com/news/330953.html)（中文）

![Googel](https://weekly.panshenlian.com/_media/images/2022/issue-4/article-006.jpg)

Security affairs 网站消息，4月21日，安全研究人员 Khaled Nassar 在 Github 上公开了 Java 中新披露的数字签名绕过漏洞的 PoC 码，该漏洞被追踪为 CVE-2022-21449（CVSS 分数：7.5）。

漏洞的影响范围主要涉及 Java SE 和 Oracle GraalVM 企业版的以下版本 ：

- Oracle Java SE：7u331、8u321、11.0.14、17.0.2、18
- Oracle GraalVM 企业版：20.3.5、21.3.1、22.0.0.2

目前，甲骨文已在 4 月 19 日最新发布的 4 月补丁中修复了该漏洞，但由于 PoC 代码的公布，建议在其环境中使用 Java 15、Java 16、Java 17 或  Java 18 的系统组织尽快修复。

## 工具

1、[secrets：防止将密码提交到源代码中的命令行工具](https://github.com/sirwart/secrets)

![secrets](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-001.jpg)
([via](https://www.sohu.com/a/280490064_100051639))

secrets 是 github 上一款开源的命令行工具，用于防止将密码提交到您的源代码中，secrets 有一些区别于其他密码扫描工具的特点：

- **专注预提交**
基本目前大部分扫描代码的工具都是在预提交阶段检查的，属于常见做法。

- **极快**
github 上声称比其他工具快 95 倍或更多，扫描速度通常是我们提交代码时很关心的一个问题。

- **本地执行**
这个是安全性的保障，有些扫描工具可能会将源代码自动发送到第三方服务做检查。

- **误报率低**
github 上声称使用了基于概率论的方法，实际会比其他工具更准确地检测密钥。

- **无依赖**
这点很关键，在安装和升级方面很便利。

我认为代码检查很有必要，无论是在代码质量检查方面，还是在防止密码泄露方面，因此推荐使用其一工具，如果您觉得 secrets 不适合，这里还提供了几款 Github 上的替代工具：

- [detect-secrets](https://github.com/Yelp/detect-secrets) , Star 2.3k
- [trufflehog](https://github.com/trufflesecurity/trufflehog), Star 8.1k
- [gitleaks](https://github.com/zricethezav/gitleaks)，Star 9.6k

2、[skyline：生成 GitHub 贡献图的 3D 模型](https://skyline.github.com/)

![skyline](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-002.gif)

查看 GitHub 贡献图的 3D 模型，支持分享、打印等等。

![senlypan](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-003.jpg)

目前只支持到 2021 年，我简单试了一下[自己的 Github(@senlypan) 仓库](https://github.com/senlypan)，好家伙，2021 年基本在划水... 零星几栋楼。

3、[SpaceTime：轻量级时区库](http://spacetime.how/)

![SpaceTime](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-004.jpg)

![SpaceTime](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-005.jpg)

SpaceTime：轻量级时区库，差不多 40 KB。使用它来计算其他时区的时间。具有类似 Moment 的 API，但它是不可变的，并且没有依赖关系。

4、[HyperFormula 2.0.0：类似电子表格的计算引擎](https://handsontable.com/blog/articles/2022/4/whats-new-in-hyperformula-2.0.0)

![HyperFormula](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-006.jpg)

HyperFormula 是一个强大的 Excel 启发的电子表格系统（不仅仅是一个控件）。请注意，它是开源的，但具有双重许可。

5、[PicMo：一个简单的 JavaScript 表情符号选择器](https://picmojs.com/)

![HyperFormula](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-007.jpg)

PicMo：一个简单的 JavaScript 表情符号选择器。

![HyperFormula](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-008.jpg)

让您可以选择使用平台原生表情符号或通过 Twemoji 跨平台的表情符号，您甚至可以添加自己的自定义表情符号。

6、[Loaders：一款美化网页加载效果的工具](https://uiball.com/loaders/)

![HyperFormula](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-009.jpg)

Loaders 是一款美化网页加载效果的工具，使用简单。

![Loaders](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-010.jpg)

官网上包含一系列免费的加载效果和调试指导，这些组件是用 HTML、CSS 和 SVG 构建的，相关组件代码可以很容易地从官网上复制使用。

7、[Triangle 2.0：一款可以把图像转换为三角形艺术效果的工具](https://github.com/esimov/triangle)

![Triangle](https://weekly.panshenlian.com/_media/images/2022/issue-4/tools-011.jpg)

Triangle 2.0 ，使用 [Delaunay 三角剖分算法](https://baike.baidu.com/item/Delaunay%E4%B8%89%E8%A7%92%E5%89%96%E5%88%86%E7%AE%97%E6%B3%95/3779918) 将图像转换为三角形艺术效果。

## 资源

1、[非技术人员词汇表](https://hackernoon.com/glossary-for-non-technies)（英文）

![非技术人员词汇表](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-001.jpg)

大部分非技术人员，对 “服务器”、“调试” 、“开源” 、“编译” 、“前端” 、“库” 、“Docker” 、“MySQL” 等名词不太了解，这篇文章收集了很多简而易懂的技术名词解释。

2、[Apache IoTDB（物联网数据库）](https://iotdb.apache.org/)（英文）

![IoTDB](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-003.jpg)

![IoTDB](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-004.jpg)

Apache IoTDB（物联网数据库）是一个物联网原生数据库，具有高性能的数据管理和分析功能，可部署在边缘和云端。Apache IoTDB 由于其轻量级架构、高性能和丰富的特性集以及与 Apache Hadoop、Spark 和 Flink 的深度集成，可以满足物联网中海量数据存储、高速数据摄取和复杂数据分析的需求工业领域。

[Github 仓库](https://github.com/apache/iotdb) : https://github.com/apache/iotdb

3、[2022 年最受欢迎的 Node.js 框架](https://stackdiary.com/node-js-frameworks/)

![Node.js](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-005.jpg)

经过多年的稳定统治，Node.js 仍然是最受欢迎的 JavaScript 运行环境。但在最近的历史中，Node.js 框架的格局发生了巨大变化。越来越多的框架被构建为混合（元）解决方案，不仅迎合后端，也迎合全栈开发人员。

![Node.js](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-006.jpg)

![Node.js](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-007.jpg)

![Node.js](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-008.jpg)

文章中探讨了当前趋势，并探索最流行的 Node.js 框架，包括但不限于：

- Next.js
- Nest
- Strapi
- Remix
- Nuxt
- SvelteKit
- Fastify
- Redwood
- Express
- Adonis
- Keystone

你是否在使用以上的 Node.js 框架，体验如何？

4、[古腾堡计划——超过 6 万本免费电子书的图书馆](https://www.gutenberg.org/)

![古腾堡计划](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-009.jpg)

古腾堡计划是一个拥有 60,000 多本免费电子书的图书馆，用户可以选择免费的 epub 和 Kindle 电子书，进行下载或在线阅读，特别是可以找到世界上最伟大的 **文学作品**，古腾堡计划重点关注美国版权已过期的旧作品，成千上万的志愿者将电子书数字化并认真校对，供您欣赏。

![古腾堡计划](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-010.jpg)

网站提供了一些热门电子书的下载排名情况，如果碰巧你也喜欢阅读文学电子书，这个网站绝对适合你。

5、[LinkedIn开源了一个企业级的高性能功能商店（机器学习）](https://engineering.linkedin.com/blog/2022/open-sourcing-feathr---linkedin-s-feature-store-for-productive-m)

![Feathr](https://weekly.panshenlian.com/_media/images/2022/issue-4/source-011.jpg)

最近 LinkedIn 宣布了一个新的开源项目，以简化机器学习 (ML) 功能管理和提高开发人员生产力。

## 图片

1、[DALL-E、元宇宙和零边际内容](https://stratechery.com/2022/dall-e-the-metaverse-and-zero-marginal-content/)（英文）

最近， [OpenAI 发布了 DALL-E 2](https://www.theverge.com/2022/4/6/23012123/openai-clip-dalle-2-ai-text-to-image-generator-testing)，Dall-E 2 是来自 OpenAI 的新 AI 系统，DALL-E 是通过在图像及其文本描述上训练神经网络而创建的，通过深度学习，它不仅可以理解像考拉熊和摩托车这样的单个物体，还可以从物体之间的关系中学习，当你向 DALL-E 索要 “考拉骑摩托车” 的图像时，它知道如何创建那个或任何东西与另一个对象或动作的关系。

简而言之，Dall-E 2 能根据文本提示生成（或编辑）图像，来自 [@BecomingCritter](https://twitter.com/BecomingCritter/status/1511808277490896903) 的这条推特帖子发布了很多有意思的 AI 图示。

![DALL-E、元宇宙和零边际内容](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-001.jpg)

▲ 泰迪熊在 1980 年代在月球上进行新的人工智能研究。

![DALL-E、元宇宙和零边际内容](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-002.jpg)

▲ 一个沐浴在 AGI 乌托邦阳光下的人类。

![DALL-E、元宇宙和零边际内容](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-003.jpg)

▲ 戴贝雷帽和黑色高领毛衣的柴犬狗。

![DALL-E、元宇宙和零边际内容](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-004.jpg)

▲ 一只在喜马拉雅山冥想寻求启蒙的聪明猫。

![DALL-E、元宇宙和零边际内容](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-005.jpg)

▲ 火星上的一座城市。 

关于 DALL-E 和 GPT 以及类似的机器学习模型，未来我们可能有几个值得思考的点：

- 极大补充丰满了元宇宙的未来，推动了社交、游戏、视频以及媒体等内容快速进化
- 互联网生产成本几乎为零，让消费的边际成本降到了零

延伸推荐阅读：[《互联网与第三产业》](https://stratechery.com/2019/the-internet-and-the-third-estate/)

2、[1982年日本精工电视手表，当时的技术非常惊人](https://twitter.com/stem_feed/status/1518206411481575424)

![seiko](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-006.jpg)

▲ 最近推上有个热门的帖子，网友 @stem_feed 发了一个推 “The Seiko TV watch, 1982. Pretty amazing tech for its days.”

内容是 Seiko（日本精工）在 40 年前推出的一款带有显示屏、可交互娱乐的手表，也就是 SEIKO 精工在 1982 年发明的 “TV WATCH” 电视手表，可想而知当时的技术非常惊人。

Seiko TV Watch 的手表部分乍一看和普通的不锈钢电子表没有太大的区别，不同的是，它除了手表还附带了一堆其他装备——这是世界上第一个有调谐钮、耳机插孔，随时随地可以看节目的手表。

![seiko](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-007.jpg)

表身有上下两个独立屏幕：上屏幕是普通电子表的屏幕，可以看时间、设置闹铃、日历、秒表等；下屏幕尺寸是 16.8×25.2mm，是个 31920 像素（210×152）的液晶屏，用于视频输出，配备 VHF&UHF 调谐器，同时可收听 FM 广播。看电视的话，电池续航能力为 5 小时。

![seiko](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-008.jpg)

这在当时绝对是款划时代的产品，当时的 SEIKO 精工光光研发就用了三年的时间，投入数亿日元。

当然，这款表还在 1983 年登陆美国，在 007 系列电影等电影中带过货，以下列举部分场景。

![seiko](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-013.jpg)

▲ 在 1983 年罗杰·摩尔主演的电影《007 之八爪女》

![seiko](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-009.jpg)

![seiko](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-010.jpg)

▲ 在 1984 年的《捉鬼敢死队》

![seiko](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-011.jpg)

▲ 在 1986 年电影《怒月冲天》中出现的 UC-2000

![seiko](https://weekly.panshenlian.com/_media/images/2022/issue-4/photo-012.jpg)

▲ 在 1987 年汤姆·汉克斯主演的电影《天罗地网》

## 播客

1、[自然语言处理的前世、今生以及广泛应用](https://www.ximalaya.com/sound/318975914)（中文）

![自然语言处理的前世、今生以及广泛应用](https://weekly.panshenlian.com/_media/images/2022/issue-4/boke-001.jpg)

([via](https://voi.id/zh/technology-zh/81256/read))

自然语言处理是让计算机和人类用“人话”交流的领域。如其他人工智能领域一样，自然语言处理也经历了早期的规则、信号处理、统计机器学习和深度学习时代。自然语言处理在近些年取得长足的突破之后，打开了广泛的应用场景，也面临着一些挑战。本期节目特别介绍了很多的自然语言处理的应用，让大家大开眼界。

**嘉宾**：崔安颀（[薄言RSVP.ai](https://www.rsvp.ai/cn) 联合创始人、AI负责人，《大数据智能：数据驱动的自然语言处理技术》一书编著者）

**主持**：Sean Wang、斯图亚特

**剪辑**：斯图亚特

本期内容包括：

- 什么是自然语言处理、自然语言的边界
- 自然语言处理的历史：起源、基于规则的翻译、信号处理、统计机器学习、深度学习
- BERT为什么这么灵？
- 机器阅读理解
- 自然语言处理遇到的挑战
- 自然语言处理的多种应用
- 计算机真的懂了吗?
- 语义的理解
- 推荐图书 

**推荐读物**：  

![推荐读物](https://weekly.panshenlian.com/_media/images/2022/issue-4/boke-002.jpg)

▲  [《数学之美》](https://book.douban.com/subject/35033507/)  

![推荐读物](https://weekly.panshenlian.com/_media/images/2022/issue-4/boke-003.jpg)

▲  [《大数据智能：数据驱动的自然语言处理技术》 ](https://book.douban.com/subject/34907320/)

![推荐读物](https://weekly.panshenlian.com/_media/images/2022/issue-4/boke-004.jpg)

▲  [《统计自然语言处理》 ](https://book.douban.com/subject/25746399/)

![推荐读物](https://weekly.panshenlian.com/_media/images/2022/issue-4/boke-005.jpg)

▲  [《Representation Learning for Natural Language Processing》 ](https://book.douban.com/subject/35139910/)

## 文摘

1、[超越库和框架的创新](https://nilsnh.no/2022/04/09/innovating-beyond-libraries-and-frameworks/)（英文）

![超越库和框架的创新](https://weekly.panshenlian.com/_media/images/2022/issue-4/post-001.jpg)

Netlife Bergen 的首席技术官 Nils Norman Haukås 提醒我们不要过分沉迷于最新的 **框架** 和 **库**，也许最好专注于 **原则** 和 **模式**。

文章的主要观点是：

- 框架与库很显然简化了我们的应用开发，并且做了很多抽象和优化，使用者完全不必关注底层实现。但是存在维护性和安全性等问题，例如很多开源框架软件没有及时更新升级，甚至是停止维护了，另外在安全性方面，最近的 log4j 和 spring 框架严重漏洞，也让很多企业和个体陷入危险之中甚至造成损失。

- 但如果我们能专注于 **原则** 和 **模式** 并自我设计，那么会避免遇到维护性和安全性等问题，并且能更好的构建项目以及适应未来的变化。

总之，以我个人的经验，我是赞同作者观点的，模式和原则，是软件工程设计的基石，肯定是高于库和框架，只不过我们普通企业或个人，自我设计框架和库不太现实，而且也需要从成本方面考虑，当然像 BAT 或者一些一线大厂，自己会设计很多框架和库。

因此，道理浅显易懂，但往往需要考虑实际场景。

2、[谷歌、Meta 和其他公司将不得不根据新的欧盟立法解释他们的算法](https://www.theverge.com/2022/4/23/23036976/eu-digital-services-act-finalized-algorithms-targeted-advertising)（英文）

![算法](https://weekly.panshenlian.com/_media/images/2022/issue-4/post-002.jpg)

2022 年 4 月 23 日，经过数小时的谈判，欧盟同意了《数字服务法》（DSA）的广泛条款，这将迫使科技公司对其平台上出现的内容承担更大的责任。新的义务包括更快地删除非法内容和商品，向用户和研究人员解释他们的算法是如何工作的，并对错误信息的传播采取更严格的行动。

公司如果违规，最高面临年营业额 6% 的罚款！

在上一期周刊 [《无聊科技正经事周刊（第3期）：美团的推荐算法，是在玩火吗？》](https://www.panshenlian.com/2022/04/20/weekly-3/) ，我简单说过美团等互联网平台的算法问题，以及国内的一些网络监管情况，感兴趣的可以看看。

总之，未来无论是国内外，线下有法律监管，线上也应该有法律监管，数字服务法案将重塑网络世界、监管网络世界。

## 言论

1、

1985年，媒体评论家尼尔·波斯特曼写了一本书，名为《自娱自乐至死》。波斯特曼认为，**媒体不强调信息的质量，而过分强调了我们对娱乐的渴望**。 

我们不再被价值观、道德、忠诚或家庭所驱动，我们被媒体所强调的东西所驱动。所有媒体的首要主题是什么？关注富人和名人，这是唯一重要的事情。

--  [《“为什么我不富有和出名？” 我们时代的错觉》](https://dariusforoux.com/rich-and-famous/)

2、

我听过很多人谈论工作与生活的平衡，我认为这种情绪是善意的，但它忽略了一个关键的机会。经营一家公司真是太难了。即使在好的时候，它也可能是一种磨难。

腾出个人时间绝对是至关重要的，但你也应该考虑如何 **将更多的生活融入到你的工作中**，我喜欢将其视为工作与生活的融合。

--  [在创业时管理你的心理健康](https://future.a16z.com/managing-your-mental-health-while-running-a-startup/)

## 首发订阅

这里记录每周值得分享的科技内容，周三发布，首发在

- [潘深练个人网站](http://www.panshenlian.com/weekly)
- 微信公众号：潘潘和他的朋友们

本刊开源（GitHub: [senlypan/weekly](https://github.com/senlypan/weekly)），欢迎投稿，推荐或自荐文章/软件/资源，请[提交 issue](https://github.com/senlypan/weekly/issues) 。

（完）