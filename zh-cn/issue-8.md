# 无聊科技正经事周刊（第8期）：让子弹飞一会儿，用长期的眼光看中国开源

> 作者: 潘深练
>
> 日期: 2022年5月25日

这里记录每周值得分享的科技内容，周三发布。

本刊开源（GitHub: [senlypan/weekly](https://github.com/senlypan/weekly)），欢迎投稿，推荐或自荐文章/软件/资源，请[提交 issue](https://github.com/senlypan/weekly/issues) 。

## 封面图

![封面图](https://weekly.panshenlian.com/_media/images/2022/issue-8/cover.jpg) 

位于墨尔本北菲茨罗伊的一处草屋建筑。（[via](https://thedesignfiles.net/2022/05/architecture-we-should-be-so-lucky-multiplicity/)）

## 本周话题：让子弹飞一会儿，用长期的眼光看中国开源

![topic](https://weekly.panshenlian.com/_media/images/2022/issue-8/topic-001.jpg) 

**突然闭源，沸沸扬扬**

5月18日，中国开源代码托管平台 Gitee 上的开源仓库（项目），在访客访问时提示仅限仓库成员可见，并声明需要仓库管理员提交公开仓库访问申请，经平台人工审核通过后，才可再次公开访问。简而言之，以前公开的开源代码仓库，现在需要先审后开。

此举瞬间在网上掀起一阵热议，其中不乏激昂者，觉得此举荒唐！与开源理念相悖！也不乏调侃者，认为这是在自己掐自己，雪上加霜！更不乏玻璃心，断定中国开源已死！

显然，大家在宣泄情绪，这是人类对抗新变化/维持现状的一种体内平衡方式，带有感性标签。本质上许多人都能看懂，此举并没有多大玄机，但同时又有许多人看不明白，至于吗？

![topic](https://weekly.panshenlian.com/_media/images/2022/issue-8/topic-002.jpg) 

**开源越界，没有法外之地**

在好奇心驱使下，我们像极了一个翻石头的孩子，开始猜测 Gitee 行为背后的可能性：

- 有人提交了不恰当言论，甚至造谣..
- 有人破坏了公平规则，公开抢菜、抢票、抢苗代码..
- 有人公开了某些特殊词库、某些非法影音资料..
- 有人发布了危害未成年的相关代码，造成不良影响..
- 有人把企业私有代码公开于众..
- More...

总之，大概率是有人越了界，侵了权，违了规，过去平台野蛮放任的作风，如今需要适度往回收一收，需要卡个小口，把这群害码筛查过滤一遍，让恶人无处作恶，甚者追究责任。

内容平台就必然存在违规风险，所以审核是一种必不可少的监管方式。短期一看，平台和用户都有点小难受，但从长远的角度分析，既保障了开源软件事业长远稳健可控，又夯实了开源平台持续良性向好。

![topic](https://weekly.panshenlian.com/_media/images/2022/issue-8/topic-003.jpg) 

**开源危机，卡脖子的事**

此前俄罗斯在 Github 上被卡脖子的事实，让国人更加坚信：开源虽无边界，但平台有国界。其中，无论是大面上的开源还是具体至于芯片，国际多方的激烈竞争都加速了这一事实，所以国家层面的大力推进支持自然不必说，在这样的背景下，Gitee 纵使有千万种理由可以吐槽，也始终作为我们国人开源事业的砥砺者，现阶段毫无疑问似个婴儿，学步之初难免磕碰跌倒、甚至做出愚蠢之事，因此更需要外部的支持力量，譬如你我，去额外呵护、耐心栽培，促使他茁壮成长、补质补短、寻求突破，甚至超越，社区起来了，人才进来了，质量拔高了，依赖消减了，我们才有可能翻盘，才有赢面。

![topic](https://weekly.panshenlian.com/_media/images/2022/issue-8/topic-004.jpg) 

**别急，让子弹飞一会儿**

从18日至今，不到一周时间，今早（25日）我看 Gitee 上的项目基本已正常可见。

Gitee 做出的无奈最优解，自始至终冷静从容，反过来作为开源社区的一份力量，你我显然需要更加成熟，同样秉持这份心态，让子弹飞一会儿，莫着急，给点过程，不能说立刻见效，这也是一种心态，懂了，我们这一代代人，才有谱。

毫无疑问，Gitee 此次审核事件，很可能会成为一段争议的历史，在后人口中传开议论，而置于事件旋涡中心的你我，到底是义愤填膺、冷嘲热讽、还是心平气和...

## 科技动态

1、[iPhone 14 将配备内置自动对焦的“高端”前置摄像头](https://appleinsider.com/articles/22/05/23/iphone-14-to-get-high-end-front-camera-with-built-in-autofocus)（英文）

![iPhone](https://weekly.panshenlian.com/_media/images/2022/issue-8/keji-001.jpg) 

（据称）即将面世的iPhone 14和 iPhone 14 Pro 可能配备内置自动对焦功能的高端自拍相机，该相机配置将交由韩国 LG Innotek 组装。

![iPhone](https://weekly.panshenlian.com/_media/images/2022/issue-8/keji-002.jpg) 

据ET News 报道，这一变化是由于苹果将前置摄像头归类为 “高端” 组件而不是 “低端” 组件，因此供应商从中国换为韩国。

iPhone 14 升级前置摄像头，支持自动对焦功能，以增强 FaceTime 通话和自拍功能，而且可能采用更大的光圈，可以为 iPhone 机型提供更好的人脸识别功能。

2、[人们正在接受美容语音手术以改变他们的发声方式](https://www.odditycentral.com/news/people-are-getting-cosmetic-voice-surgery-to-change-the-way-they-sound.html)（英文）

何曾几时你希望自己拥有一副深沉嗓音，如今这是一个可实现的目标，土耳其的外科医生 Kursat Yelken 可以提供帮助。

![美容语音手术](https://weekly.panshenlian.com/_media/images/2022/issue-8/keji-006.jpg) 

([via](https://pixabay.com/ro/photos/%c5%a3ip%c4%83t-strig%c4%83t-femeie-fric%c4%83-furie-4751647/))

Kursat Yelken 博士从事声音加深手术 15 年，并称该手术的需求一直在增加。目前，他每年为 100 至 150 人服务，从希望听起来更自信的高管到希望让自己的声音与新性别相匹配的跨性别者。

这位在哈佛医学院接受过培训的土耳其医生可以根据患者的喜好调整患者的音调和语调，使他们的声音更深或更高。

Yelken 博士用外行的术语解释了这个过程，他说它首先在颈部下部切开一个切口，然后在甲状腺软骨上创建一个“软骨岛”，该软骨岛也被推回以发出声音更深。该操作是在局部麻醉期间进行的，因此患者可以通过尝试他们的新声音来选择希望的音调和音色。

3、[武汉 Apple Store 开业，开设中国首个 Apple Pickup 到店取货区域的零售店](https://appleinsider.com/articles/22/05/21/apple-store-opens-in-wuhan-with-chinas-first-apple-pickup-area)（英文）

![Store](https://weekly.panshenlian.com/_media/images/2022/issue-8/keji-003.jpg) 

Apple 武汉零售店于 5 月 21 日 (周六) 在湖北正式开幕，位于武汉国际广场购物中心 C 座 2F 。

![Store](https://weekly.panshenlian.com/_media/images/2022/issue-8/keji-004.jpg) 

这是中国首个设立专属 Apple Pickup 到店取货区域的零售店。至此，苹果大中华区 Apple Store 零售店总数达到 54 家。店内拥有 128 人组成的零售店团队，可以通过多种语言与顾客交流，包括中文手语和英文手语。

![Store](https://weekly.panshenlian.com/_media/images/2022/issue-8/keji-005.jpg) 

该商店是中国第一家设有专门的 Apple Pickup 区域的商店，因此客户可以快速轻松地获得在线订单。Today at Apple 课程也将在场地提供，涵盖的主题包括摄影、摄像、艺术与设计、音乐和编程。

4、[月球火山可能喷出 18 万亿磅的火山水](https://interestingengineering.com/moon-volcanoes-volcanic-water)（英文）

![月球火山](https://weekly.panshenlian.com/_media/images/2022/issue-8/keji-007.jpg) 

月球过去猛烈的火山活动可能为宇航员在未来的任务中提供重要的生命续航。

月球上那些特征性的黑色斑点，也称为月海，起源于数十亿年前，当时月球表面发生了一系列火山爆发。

现在，加拿大大学博尔德分校（CUBoulder）研究人员的一篇新论文预测，这些火山可能还留下了冰盖，部分冰盖的厚度可能高达数百英尺，这些冰盖可以用于饮用水和火箭推进剂。

![月球火山](https://weekly.panshenlian.com/_media/images/2022/issue-8/keji-008.jpg) 

美国宇航局的阿尔特弥斯计划旨在建立人类在月球上的存在，这可以作为未来火星任务的垫脚石，自 1972 年以来的首次载人登月预计将在 2025 年左右进行。

## 灵感

1、[排名：前 10 名电动汽车电池制造商](https://elements.visualcapitalist.com/ranked-top-10-ev-battery-makers/)（英文）

![电动汽车电池制造商](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-001.jpg) 

▲ 统计数据早于 2021年 10 月

随着消费者对电动汽车 (EV) 的兴趣日益浓厚，锂离子 EV 电池市场现在是每年约 270 亿美元的业务。

业内专家表示，高需求提振了电池制造商的利润，给市场带来了激烈的竞争。到 2027 年，随着消费者接受更实惠的电动汽车，市场可能进一步增长到 1270 亿美元。

作为汽车零部件的制造强国之外，亚洲正迅速成为电池领域创新的温床。

市场份额排名前 10 的电动汽车电池制造商都将总部设在亚洲国家，集中在**中国、日本和韩国**。

![电动汽车电池制造商](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-002.jpg)

▲ 前三大电池制造商——CATL（**宁德时代**）、LG 和松下——占据了电动汽车电池制造市场近 70% 的份额。

**电动汽车的巅峰可能已经过去，但是全面电动化趋势却是必然**，基本有几点原因：

- 推广政策（环境与清洁能源）
- 消费意识（认知与诉求）
- 多元型号（制造商与受众）
- 电池价格（创新与竞争优势）
- more

当然，电动化趋势的阻碍原因也同时存在：

- 电池金属供应（大环境与局部紧张）
- 充电基础设备（普及与便利）
- 充电时间（技术突破）
- 续航里程（焦虑与改进）
- more

2、[可视化图解机械表工作原理](https://ciechanow.ski/mechanical-watch/)（英文）

![机械表](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-003.jpg)

在现代便携式设备的世界中，很难相信仅仅在几十年前，最方便的计时方式是**机械表**。

与石英表和智能表不同，机械表**无需**使用任何电池或其他电子元件即可运行。

![机械表](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-004.jpg)

![机械表](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-005.jpg)

![机械表](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-006.jpg)

![机械表](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-007.jpg)

![机械表](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-008.jpg)

![机械表](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-009.jpg)

![机械表](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-010.jpg)

文章使用可交互的 **3D 动画**效果演示了机械表工作原理、零部件组装过程等。

特别是你可以拖动动画来改变你的**视角**，并且使用滑块来查看内部运行机制，动画设计得无比到位。

3、[CSS 太阳光线穿过窗户](https://codepen.io/kaz_hashimoto/pen/KKQdMrY)

![CSS](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-011.jpg)

工程师 Kazuhiro Hashimoto 编写了一个令人惊叹的、可定制的动画场景——太阳光线穿过窗户。

![CSS](https://weekly.panshenlian.com/_media/images/2022/issue-8/linggan-012.jpg)

当然，如果你喜欢这套效果，可直接复制 HTML、CSS、JS ，可能对你的设计有些许启发。

## 文章

1、[35岁从大厂裸辞，我该何去何从](https://mp.weixin.qq.com/s/Oo9JNMTMNzaIWizOdYXGkw)（中文）

![大厂裸辞](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-001.jpg)

最近从陈成老师那看到一位阿里的12年老兵裸辞，可以简单看看、听听，可能不适合大部分人。

2、[Raft 共识算法介绍（极致内容）](https://raft.github.io/)（英文）

![Raft](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-004.jpg)

相信设计分布式系统的工程师们都了解共识的核心作用，网络间通信的服务只要涉及多节点，并希望对外提供统一的能力，那各节点间必然需要达成一种共识，而达成共识就需要有一种普遍任何的共识机制，所以共识算法，支撑这一切。

不仅仅是分布式系统，区块链等领域的实现，都基于共识。

▼ 其中，你可能了解过 NWR、Gossip、Paxos、Zab 等协议/算法，但在这里如果你详细了解以下关于 Raft 的介绍、可视化过程以及相关论文之后，无论是原始的 Gossip 还是其它共识变种，你都会融通，基本大差不差，不过是边界差异。

![Raft](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-002.jpg)

![Raft](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-005.jpg)

![Raft](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-003.jpg)

▲ Raft 算法可视化动画设计得简单明了，建议你尝试体验，有助于了解主观下线、选举等共识达成过程。

3、[评分和排名算法 (Rating & Ranking Algorithms)](https://leovan.me/cn/2022/05/rating-and-ranking-algorithms/)（中文）

![评分和排名算法](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-006.jpg)

投票是对不同选项或个体的排序，在投票中我们关注更多是**相对位置**这样定性的结论，例如：积分前三名的同学才能进入下一环节。但有的时候我们不光想知道不同选项之间的先后顺序，还想了解不同选项之间的**差异大小**，这时我们就需要**设计更精细的方法**进行定量分析。

范叶亮划分出四种具体的评分排名，并分别罗列典型网站案例：

- 基础评分和排名
- 考虑时间的评分和排名
- 不考虑时间的评分和排名
- 比赛评分和排名

![评分和排名算法](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-007.jpg)

▲ 其中，个人对于考虑时间的评分和排名类目中的 **Hacker News** 计算公式极为好奇。

Hacker News 是一个可以发布帖子的网络社区，每个帖子前面有一个向上的三角形，如果用户觉得这个内容好，点击一下即可投票。根据得票数，系统自动统计出热门文章排行榜。

Hacker News 使用分数计算公式如下：

![评分和排名算法](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-008.jpg)

其中，**P** 表示帖子的得票数，减去 **1** 表示忽略发帖人的投票；**T** 表示当前距离发帖的时间（单位为小时），加上 **2** 是为了防止最新的帖子分母过小；**G** 为重力因子，即将帖子排名被往下拉的力量，默认值为 **1.8**。

在其他条件不变的情况下，更多的票数可以获得更高的分数，如果不希望“高票数”帖子和“低票数”帖子之间差距过大，可以在式 **(1)** 的分子中添加小于 **1** 的指数，例如： (P-1)^0.8 。在其他条件不变的情况下，随着时间不断流逝，帖子的分数会不断降低，经过 **24 小时** 后，几乎所有帖子的分数都将小于 **1**。重力因子对于分数的影响如下图所示：

![评分和排名算法](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-009.jpg)

不难看出， **G** 值越大，曲线越陡峭，排名下降的速度越快，意味着排行榜的更新速度越快。

4、[关于证书,这里有你想知道的一切](http://ifeve.com/%E5%85%B3%E4%BA%8E%E8%AF%81%E4%B9%A6%E8%BF%99%E9%87%8C%E6%9C%89%E4%BD%A0%E6%83%B3%E7%9F%A5%E9%81%93%E7%9A%84%E4%B8%80%E5%88%87-md/)（中文）

![关于证书](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-010.jpg)

在HTTPS开发中，你是否被各种证书搞得晕头转向？

.pem证书?
.der证书?
X.509证书？

本文带你理清这些证书叫法背后的含义。

5、[如何搭建一个漂亮的网站，即使你不会设计](https://hackernoon.com/how-to-make-a-great-looking-website-even-if-you-cant-design)（英文）

![网站](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-012.jpg)

本指南介绍了用于设计网站的工具、技术和资源，100% 免费，帮你快速搭建一个有趣/有创意的网站。

6、[一个相当优秀的开发者的孤独感](https://news.ycombinator.com/item?id=31438426)（英文）

![10x](https://weekly.panshenlian.com/_media/images/2022/issue-8/article-013.jpg)

一个 “相当优秀” 的10x 开发者的孤独自述，33 岁才入行，目前 42 岁。

## 工具

1、[uiverse.io：精美的免费开源 UI 组件库](https://uiverse.io/)

![uiverse](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-001.jpg)

uiverse.io，一款精美的 UI 组件库，免费开源

![uiverse](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-002.jpg)

▲ 平台有很多顶级设计师，你也可以设计组件

![uiverse](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-003.jpg)

▲ 看到喜欢合适的组件，可直接复制使用 HTML 和 CSS 代码

2、[Shrink.media：极致压缩图像大小的在线工具](https://www.shrink.media/upload)

![Shrink](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-004.jpg)

Shrink.media，一款免费压缩图像大小的在线工具，通过智能压缩和缩小尺寸来减小图像的文件大小，并支持免费下载压缩后的图像

![Shrink](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-005.jpg)

▲ 压缩前后对比，从360kb至12.35kb，效果满意

3、[TypeLit.io：一个练习打字的网站](https://www.typelit.io/)（英文）

![TypeLit](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-006.jpg)

通过练习你最喜欢的文学作品来提高你的打字速度。支持：英语/荷兰语/芬兰/法语/德语/意大利语/葡萄牙语/俄语/西班牙语。

![TypeLit](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-007.jpg)

除了网站提供的经典文学作品，目前发布了最新功能，支持**自带书籍**，其实就是允许你导入未加密的 EPUB、PDF 和 TXT 文件，然后开始你的打字练习。

当然，这个功能收费，5 刀/月，如果你只是练习打字（字母/单词），那其实免费版本足够使用了。

4、[beautify-github-profile：美化你的 GitHub 个人资料](https://github.com/rzashakeri/beautify-github-profile)（英文）

![beautify](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-008.jpg)

beautify-github-profile 仓库提供了一整套工具和指南，帮助你设计出一个更漂亮、更有吸引力的 github 个人资料展示页。

5、[API Tracker：一个API的追踪器](https://apitracker.io/)（英文）

![apitracker](https://weekly.panshenlian.com/_media/images/2022/issue-8/tools-009.jpg)

apitracker.io ，可以发现最好的 API 和开发者资源，包括跟踪 API 规范、开发人员体验、API 文档、SDK、开发人员文档、IDE 支持、平台强度、身份验证和 API 样式。

## 资源

1、[我的第一个NFT](https://myfirstnft.info/)（中文/英文）

![NFT](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-005.jpg)

如果你想：理解 NFT 的价值、了解 web3、制作一个免费的 NFT..建议你先Mark为敬。

![NFT](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-006.jpg)

教程体验极致，舒适度五星。

2、[书栈网](https://www.bookstack.cn/)

![书栈网](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-001.jpg)

书栈网，汇集了众多 IT 程序员互联网开源编程书籍，囊括小程序、前端、后端、移动端、云计算、大数据、区块链、机器学习、人工智能和面试笔试等相关书籍。

![书栈网](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-002.jpg)

特别你所希望看到的面经算法、编程电子书。

3、[佳能相机博物馆](https://global.canon/zh/c-museum/camera-series.html)

![佳能](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-003.jpg)

佳能相机博物馆，从 30 年代的胶片相机到目前的数码相机，一应俱全。

![佳能](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-004.jpg)

支持搜索，排序，相机种类极多。

4、[Side Project 指南](https://sideproject.guide/)（中文）

工作之余，很多程序员喜欢用代码建造一些小工具。有时候是为了解决一些自己或者朋友遇到的小问题，有时候是为了好玩儿。我们这行，通常称之为 Side Project。 

不过可不能小看这些小工具。许多伟大的产品诞生于程序员的 Side Project。比如 GitHub, Unsplash, Instagram, 等等等等。

每次开启一个项目，虽然是 Side Project, 但内心其实隐隐也在期待着，这个 Side Project 或许可以帮到除自己以外的人？或许可能，这个产品价值足够高，甚至带来经济回报？然而现实是，99% 的 Side Project 都永远停留在自娱自乐的情况。

经历三个阶段：从 热情满满 到 无人问津 最后 弃坑。

Side Project 指南详细介绍了如何提升 Side Project 的存活概率、每次开启一个新项目都应该问自己下面四个问题：

- 如何判断一个点子的好坏？
- 如何快速把 Side Project 做出来？
- 如何让更多人知道这个 Side Project？
- 如何把 Side Project 变成能为自己带来收入的产品？

5、[CNCF（云原生计算基金会）全景一览](https://landscape.cncf.io/)（英文）

![CNCF](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-007.jpg)

▲ CNCF 全景一览

![CNCF](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-008.jpg)

▲ CNCF 成员

本资源不做介绍，懂的都懂，不懂的不懂，仅列为自己收藏的一副星辰大海图。

6、[Awesome Indie，一个发现独立开发者产品的网站](https://awesomeindie.com/)（英文）

![Awesome](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-009.jpg)

一个发现独立开发者产品的网站，上周上榜 ProductHunt #1 的一个产品。

7、[DevDum - 200多个面向 Web 开发人员的资源导航网站](https://www.devdum.com/)（英文）

![Awesome](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-010.jpg)

像素风格，挺特别。

8、[黑客说](https://hackertalk.net/)（中文）

![黑客说](https://weekly.panshenlian.com/_media/images/2022/issue-8/source-011.jpg)

国产技术交流社区，有点 Twitter 风格，试运营中，暂时没看到有吸引我的点，如果想达到优质技术交流水平，很难很难。

## 播客

1、[什么是 DAO？与创始人和资深参与者聊聊 DAO](https://www.ximalaya.com/sound/531293360)（中文）

![DAO](https://weekly.panshenlian.com/_media/images/2022/issue-8/boke-001.jpg)

有人说 **DAO** 是 **公司制度的未来**，也有人对此不屑一顾。可究竟什么是 DAO，仍然众说纷纭。

本期节目我们请到了 DAOrayaki 的创始人 Wendy 与 Bankless、fwb、Seed Club 等 DAO 的资深参与者王超来一起来聊聊 DAO 背后的故事。

本期节目我们聊到了：

- 1. DAORayiki 的来龙去脉；王超为什么加入这些 DAO
- 2. 为什么选择 DAO 的形式、什么是 DAO？DAO 究竟是怎么运作的？
- 3. 汉洋是做开源的，我们之前的开源项目和 DAO 有哪些区别呢？它是一个老的事情套上了新的名词，还是一件全新的事情？
- 4. 如何加入一个 DAO？
- 5. DAO 怎么挣钱？

2、[CCTV记录片《码农的异想世界》](http://tv.cctv.com/2022/04/25/VIDAtlLjsM5mDyjKGNMcNTPZ220425.shtml)（中文）

![码农的异想世界](https://weekly.panshenlian.com/_media/images/2022/issue-8/boke-002.jpg)

在外人眼中，程序员们（自嘲码农）仿佛永远穿着格子衫、大裤衩，捋着堪忧的发量、不善与人言辞。本片通过采访不同岗位的码农，听他们讲述自己与字符相作、乏善可陈的生活和闪闪发光的科学梦想。

![码农的异想世界](https://weekly.panshenlian.com/_media/images/2022/issue-8/boke-003.jpg)

**目前已播出剧集**：

- 《码农的异想世界》 第1集

本集主要内容： 这些行色匆匆的脚步，奔忙在中国互联网行业最密集的地方——西二旗，脚步的主人们有一个共同的代号——码农，他们肩上并未扛着锄头，头脑却耕耘在数码的田野里。每天的高峰时刻，6万多码农，进出于这个北京最繁忙的地铁站。

- 《码农的异想世界》 第2集

本集主要内容： 肖玮，一名音频算法工程师，也就是我们俗称的“码农”、“程序员”。他正在研发的AI降噪算法，如果技术可行，将为听力衰减的老人提供辅听，从而提升声音的清晰度和可懂度。

- 《码农的异想世界》 第3集

本集主要内容： 每一位码农都有两个身份：现实世界的程序员、异想世界中的造物者。程序员专注于编写代码，而造物者负责构建起一个虚幻的世界，这个虚幻的世界可以很小，可以很大，也可以无穷大。他们在现实与异想世界间穿梭，凭借一行行代码，实现内心最深处的愿望。

## 文摘

1、[我花了 2 年时间启动的小型项目](https://tinyprojects.dev/posts/i_spent_two_years_launching_tiny_projects)（英文）

![i_spent_two_years_launching_tiny_projects](https://weekly.panshenlian.com/_media/images/2022/issue-8/post-001.jpg)

![i_spent_two_years_launching_tiny_projects](https://weekly.panshenlian.com/_media/images/2022/issue-8/post-002.jpg)

作者介绍自己两年间落地八个想法，其中部分项目持续盈利，特别是分享了自己在构建这些小型互联网项目方面所学到的知识以及成果。

这是他的小项目，例如：

- 个人网站 tinyprojects.dev
- 收集购入大厂域名，例如 netflix.soy
- Android 版大逃杀游戏
-  小型电子商务商店 oneitem.store
- 一个非常正常的社交网络平台 Snormal
- 稀有用户名 Earlyname
- emoji 域名电子邮件服务
- 纸质网站 Paper Website

特别羡慕这种生活工作方式，这也是为何我希望成为ZY职业者的初心。

## 图片

1、[DALL-E 可以让奇幻小说栩栩如生](https://twitter.com/wenquai/status/1527312285152452608)（英文）

OpenAI 前不久公开的 DALL-E，可以为每个段落都动态生成一组独特生动的图像。

![DALL-E](https://weekly.panshenlian.com/_media/images/2022/issue-8/photo-001.jpg)

![DALL-E](https://weekly.panshenlian.com/_media/images/2022/issue-8/photo-002.jpg)

![DALL-E](https://weekly.panshenlian.com/_media/images/2022/issue-8/photo-003.jpg)

2、[帕米尔高原天空公路](https://www.odditycentral.com/travel/car-sickness-hell-a-winding-mountain-road-with-600-hairpin-turns.html)（英文）

![帕米尔高原天空公路](https://weekly.panshenlian.com/_media/images/2022/issue-8/cover1.jpg) 

帕米尔高原天空公路最高点海拔4269m。它最初长 36 公里（22 英里），但后来延长到 75 公里。

## 言论

1、

中国发展太快了，随着全球格局的变化，未来面临的发展机会和挑战都会越来越多。对于我们这一代技术人来说，只要顺应时代的变化，未来的机会只会更多。

对于新一代的开发者来说，我认为未来的领域会更加集中在用技术和算法进一步改造各种传统的行业，例如：汽车、物联网，以及用技术将人类社会朝着数字化的虚拟世界发展。所以，我推荐大家关注自动驾驶、人工智能、产业互联网、推荐系统、虚拟现实等领域，可能会有新的行业红利出现。

-- [《我的移动开发程序人生 - 写在创业十周年》](https://blog.devtang.com/2022/05/22/startup-10th-year-summary/)

2、

面向未来不一定是软件开发的目标，而是影响设计的众多 “能力” 之一。

在这个范围内过度纠正可能会导致不必要的工作、技术债务和令人困惑的抽象。

不过，找到最佳点可以节省你的时间和精力。

-- [《水晶球和千里眼：在万变的世界中面向未来》](https://stackoverflow.blog/2022/05/19/crystal-balls-and-clairvoyance-future-proofing-in-a-world-of-inevitable-change/)

3、

如果某种语言的某个特性有时会出现问题，并且可以用另一个更可靠的特性来替换它，那么请始终使用更可靠的特性。

-- [Douglas Crockford（道格拉斯·克罗克福德）](https://baike.baidu.com/item/Douglas%20Crockford/5960317)

## 首发订阅

这里记录每周值得分享的科技内容，周三发布，首发在

- [潘深练个人网站](https://www.panshenlian.com)
- 微信公众号：潘潘和他的朋友们

本刊开源（GitHub: [senlypan/weekly](https://github.com/senlypan/weekly)），欢迎投稿，推荐或自荐文章/软件/资源，请[提交 issue](https://github.com/senlypan/weekly/issues) 。

（完）