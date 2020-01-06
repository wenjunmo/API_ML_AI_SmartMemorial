<div align="center">
  <h1>:whale2: Project Name：想念 :whale2:</h1>
  <p>基于微信平台开发的 智能毕业纪念相册 APP</p>
  <p>Seeking True from Fact 网新人，有态度，不认输，不头秃</p>
</div>

> PRD 价值主张设计（目标：多层次多长度版本）
> 1. 一句话版本<br>
    此款 **智能毕业纪念册** APP 通过调取 **人脸融合API** 与 **语音合成API** ，用户只需将本地照片与个性化本人语音上传，APP 会直接合成含有语音的智能暂时匿名化照片，发布在“ **你合我猜** ”游戏模块，当猜对一张照片上传者名字即可解锁上传者的校园资料，秉持用游戏改变纪念形式的态度做出不一样的纪念相册。
> 2. 一分钟60s版本 (图文线上可阅读含可查连结)<br>
    这款 **智能毕业纪念册** APP 调取 **Face++** 人像处理中的 **人脸融合API** 与 **科大讯飞** 语音识别中的 **语音合成** 来实现 **你合我猜** 游戏化模块。用户只需将需要进行融合处理的照片和需要语音合成的个人语音上传至 APP，程序会依照个人喜好来合成新语音照片，可选择发布在 APP 特色功能的“ **你合我猜** ” 游戏模块。只有当对方猜对了合成后语音照片的人名后才能够解锁照片所属同学的校园资料。该 APP 抓住 **你对身边朋友的了解程度如何** 的痛点心理，推出 “**你合我猜**” 模块，并绘制 **最小可行性产品原型** ，减少同学之间 **见面不认人** 的尴尬处境。
> 3. [400 秒版本 Pecha Kucha 20x20 版本]() (线上投影片含可查连结未交！)<br>

## Product Documentation(产品需求文档)

|标题|内容|
|----|---|
|产品名称(Product Name)|想念|
|文档作者(Document Owner)|莫文俊|
|产品经理(Product Manager)|莫文俊|
|交互设计师(Interaction Designer)|莫文俊|
|软件工程师(Software Engineer)|莫文俊|
|测试运维师(Test Operation and Maintenance Division)|莫文俊|
|发布日期(Release Date)|2019.12|
|发布版本(Release Version)|v5.0|
|体验环境(Release Version)|iOS11|

- 版本修订记录

|修订版本号|迭代日期|修订内容|迭代者|
|---------|-------|--------|-----|
|v1.0|11.20-12.01|文档初稿撰写，建立基本产品文档框架，添加产品理念与技术开发项目流程|莫文俊|
|v2.0|12.01-12.08|测试可用 API 并进行可用性测试比对，进行市场调查与用户研究|莫文俊|
|v3.0|12.08-12.15|选定 API 类型并实现测试运行，产品后台代码实现可复用|莫文俊|
|v4.0|12.15-12.22|开发 APP 原型，制作低保真原型初步实现逻辑，模拟测试真实使用场景|莫文俊|
|v5.0|12.23-12.30|产品上线，不断反馈产品使用过程中的问题，对需求池功能迭代优化|莫文俊|

## Documentation Directory(文档目录)

- [产品介绍](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#%E4%BA%A7%E5%93%81%E4%BB%8B%E7%BB%8D)
- [市场背景](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#%E5%B8%82%E5%9C%BA%E8%83%8C%E6%99%AF)
- [价值主张设计](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#%E4%BB%B7%E5%80%BC%E4%B8%BB%E5%BC%A0%E8%AE%BE%E8%AE%A1)
  - [加值宣言](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E5%8A%A0%E5%80%BC%E5%AE%A3%E8%A8%80)
  - [核心价值宣言](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E6%A0%B8%E5%BF%83%E4%BB%B7%E5%80%BC%E5%AE%A3%E8%A8%80)
  - [用户痛点宣言](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E7%94%A8%E6%88%B7%E7%97%9B%E7%82%B9%E5%AE%A3%E8%A8%80)
  - [人工智能概率性与用户痛点](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E6%A6%82%E7%8E%87%E6%80%A7%E4%B8%8E%E7%94%A8%E6%88%B7%E7%97%9B%E7%82%B9)
  - [需求列表与人工智能API加值](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E9%9C%80%E6%B1%82%E5%88%97%E8%A1%A8%E4%B8%8E%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BDapi%E5%8A%A0%E5%80%BC)
- [原型](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#%E5%8E%9F%E5%9E%8B)
  - [交互及界面设计](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E4%BA%A4%E4%BA%92%E5%8F%8A%E7%95%8C%E9%9D%A2%E8%AE%BE%E8%AE%A1)
  - [信息设计](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E4%BF%A1%E6%81%AF%E8%AE%BE%E8%AE%A1)
  - [原型文档](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E5%8E%9F%E5%9E%8B%E6%96%87%E6%A1%A3)
  - [口头操作说明](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E5%8F%A3%E5%A4%B4%E6%93%8D%E4%BD%9C%E8%AF%B4%E6%98%8E)
- [API 产品使用关键AI或机器学习之API的输出入展示](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#api-%E4%BA%A7%E5%93%81%E4%BD%BF%E7%94%A8%E5%85%B3%E9%94%AEai%E6%88%96%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E4%B9%8Bapi%E7%9A%84%E8%BE%93%E5%87%BA%E5%85%A5%E5%B1%95%E7%A4%BA)
  - [使用水平](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E4%BD%BF%E7%94%A8%E6%B0%B4%E5%B9%B3)
  - [使用比较分析](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E4%BD%BF%E7%94%A8%E6%AF%94%E8%BE%83%E5%88%86%E6%9E%90)
  - [使用后风险报告](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E4%BD%BF%E7%94%A8%E5%90%8E%E9%A3%8E%E9%99%A9%E6%8A%A5%E5%91%8A)
  - [加分项](https://github.com/wenjunmo/API_ML_AI_SmartMemorial#--%E5%8A%A0%E5%88%86%E9%A1%B9)


## :sparkles: 产品介绍

> “我们，重新定义毕业纪念册”<br>
> “想念，是好久不见的表达”<br>
> “想念，恋你的颜和言”<br>

本软件基于 **人脸融合** 和 **语音合成** 研发的智能毕业纪念册，适用于任何想快速生成个性化毕业纪念册图集与校友连结的通讯录用户，不再为毕业后各自分飞而找不到联系方式而苦恼，不再为电子相册保存平台过多整理繁琐以及扫码失效，游戏化模块组件 “**你合我猜**” 更是能够解决多年老友不相见而健忘的尴尬场景，主打游戏化解锁新合成语音照片，在享受猜脸乐趣同时回忆逝去的青春美好。

## :sparkles: 市场背景

通过调查研究发现，移动互联网端以及通讯设备的普及，市面上新型毕业纪念册大部分都是基于上传图片形成个人图片库，搭配个性化音乐来产出音乐纪念相册，**观赏性用大于实际联系性用**。在高速发展的信息时代，信息不再局限于文本格式，相较于传统纸质毕业纪念相册，更多的是伴随着语音信息和影像信息，**纸质媒介渐渐被人遗忘**。<br>
APP 形式无疑是一种可以涵盖更多不同信息形式的新型毕业纪念册，在进行了人脸融合和语音合成API的调取后生成，而使用 **游戏化模块** 的智能毕业纪念相册会更有实际意义。

:star: **优势**

>- 涵盖多样化信息（ 相较传统纸质纪念册），使用便捷性提高（相较于网页版）
>- 市场占比少，而大多数 APP 纪念册多为个人开发专用，忽视大多数大学生群体的市场，市场有待进一步扩张
>- 大部分产品功能设计往全社交类方向进行引导，模糊了本身的产品定位，阻碍发展

:star: **竞品分析**

>竞品一：微吾H5自助工具制作毕业纪念册<br>
优点：
>- 采用接龙的形式进行信息收集、纪念册制作。将工作量平摊到每个人，每人负责完成自己的纪念模块
>- 无需下载软件，接收链接或二维码编辑者，可个人和集体编辑，可随时随地欣赏分享
>- 更新方便及时，易于维护，可转换成电子书下载成pdf
>- 互相赠言，还有很邪恶的悄悄话功能<br>
缺点：
>- 停留在传统毕业纪念册，没有科技感，信息留存较少<br>

>竞品二：时光流影网站<br>
优点:
>- 直接上传图片进行模板个性化定制设计，有成熟模板供选择
>- 分享链接与生成二维码<br>
缺点:
>- 网页编辑不容易，没有轻便和简洁，更新慢<br>

>竞品三：微信公众号微影相册<br>
优点:
>- 直接选择手机里的照片，然后选主题模板滤镜音乐，就能做出来影集了
>- 支持一键保存在手机内存中<br>
缺点:
>- 没有分享功能，只能直接发送不够方便，没有乐趣模块只有简单的纪念留存<br>

:star: **设计用户调查问卷**

>1. 对纪念大学生生涯和同学友谊最有意义的形式是：毕业纪念册、聚餐、拍视频照片、送礼物
>2. 假如推出个性定制化毕业纪念册会买吗：很有意义，买、内容设计吸引，考虑买、不买，浪费钱
>3. 买毕业纪念册看重哪一种因素：设计新颖、内容丰富、流行
>4. 考虑的性价比有哪些因素：价格贵质量好但便于保存、价格适中质量过得去、价格便宜普遍接受没有很大需求、价格无所谓没有要求
>5. 毕业纪念册的价格多少可以接受：10-30、30-60、60-100
>6. 购买毕业纪念册的最佳时机：4月、5月、6月、7月
>7. 希望添加额外的功能：个人基本信息姓名联系方式、全体毕业照、同学留言、学院老师寄语、个人感言、校园风景、专业特色、校卡使用
>8. 你心目中理想的毕业纪念册的样式（内容、封面设计、排版）是（开放题）

:star: **产品定位**

>- 功能上还原传统纸质纪念册中的信息填写，同学寄语等，适当减少社交类的功能
>- 对各种格式信息进行保存，加入图片信息、语音信息、视频信息等

:star: **目标群体大学生**

>- 主要针对人群集中在即将毕业的大学生，对新型模式的纪念册排斥度较小，接受度较高，而且善于接受新鲜事物
>- 大学生是手机用户的一大类人群，使用手机主要表现在满足沟通、娱乐、学习等需求上，情感价值主要表现在对个性化、时尚、分享交流的追求上
>- 现代信息的多元化，信息的交流和保存不再局限于文字的格式，更多的信息是图片格式、语音格式和视频格式
>- 功能设计中加入语音和视频信息的储存交流功能既满足大学生群体沟通的需求同时也满足大学生对个性化分享交流的追求

:star: **商业模式**

根据毕业生提供的影印照片和成长资料，专门为其量身定做了毕业纪念册。
>- 针对阶段性的学习生活进行记录，并采取前期免费模式推广，使用部分匿名社交模式进行收费与互动
>- 规范制作纪念册的“生产线”，推出精装版、简装版和平装版，不同的版式有着不同的价格，并针对于”贵宾“客户推出折扣
>- 提供图文的排版设计、礼品制作，策划活动，提供聚会地安排、DV拍摄、礼物派送、纪念册制作等完整服务链
>- 除具备聊天加好友的功能之外，还加入招聘、婚恋、聚会、创业等辅助功能（有待商榷）
>- 同时提供纸质版服务，配合平面设计建立多模板，为用户提供多样性的选择空间进行个性化定制

本着满足大部分人群对 APP 形式便捷的需求，同时满足小部分人群对纸质毕业纪念册传统感的追求，同时最新颖的特点是应用了高新技术 API 的调用，**基于人脸融合与语音合成** API 场景化使用，通过对照片与语音合成处理，将用户数据上传云端并进行备份，可随时进行调取。<br>

综合分析市场研究和调查，目前市面上并没有推出一款具体的使用人工智能 API与机器学习 的智能毕业相册APP，市面上的大多数都是以链接或者是纸质版留存为准，纪念意义大于使用意义，没有后续的使用价值，没有办法通过毕业纪念册来进行产品后续的自我价值，也没有很好起到沟通的效果，与产品设计的初衷有悖，并且通过调查，使用线上的程序或者是 APPs 在移动互联网下会有更多的使用场景和可以辨别的，使用频率和次数会增加，并且用户场景会更多。<br>

## :sparkles: 价值主张设计

### :star: 加值宣言
(以机器学习或人工智能 API 对产品加值的表述是否精确丶专业及中肯 1%*3=3%)

1. **个性化定制，人脸融合与语音合成，千人千面**<br>
用户有千人千面的个性化照片与语音，基于用户画像行为为用户推荐更加精准好玩的人脸合成与语音合成的设计功能。依托人脸识别算法和深度学习引擎，快速精准地定位人脸关键点，将用户上传的照片与特定形象进行面部层面融合，使生成的图片既有用户的五官特点，也呈现出对应形象的外貌特征。同时合成语音自然流畅，近乎真人发声。
2. **游戏式功能设计，贴合匿名查看，用户好奇心理重**<br>
在娱乐为王的现代，大部分用户早已经不仅仅满足于功能的达成，美观的界面还有轻松的交互，杠杆点正在向情感体验和自我实现等需求倾斜。使用游戏式设计将人脸融合与语音合成进行包装展现在用户面前，通过猜对即可解开隐藏在匿名照片下的个人联系资料，基于用户同理心和对新技术好奇的心理，来促进更多的人际联系。
3. **互动留念方式新颖，辅助线上社交，适当提高粘连度**<br>
与传统毕业纪念册的线下耗费时间与人力填写，使用线上的 APP 会更加注重时间利用的效率，在半隐形社交的圈子内可以更好兼顾校园资源，打造不一样的社交圈子。

### :star: 核心价值宣言
(加值的表述是否找到产品核心价值，也就是最小可用产品（Minimum Viable Product，最小可用产品），而不会过份夸大价值或只是点缀性质 1%*3=3%)

>运用价值主张(Value propositions)来对商业模式(Business models)进行剖析，使用应用程序编程接口(Application Programming Interface API)来对API经济(API Economy)、API开放平台(API Open Platform)以及模块化(Modularization)来对利害关系(Stakeholder)的两方：API面向客户(API Customer)和API使用者(API Consumer)来进行资源合理配置。<br>
>利害关系图的阐述：产品设计开发人员（API客户）+ 系统整合开发人员（API使用者）+ 终端用户 + API/智能云端供货商（API提供者）这4个角色的活动流程如下：<br>
>1. API客户也就是产品经理来对智能产品的价值主张进行设计（对应到终端用户的用户需求的任务、痛点及增长点），对智能/平台/模块成本效益进行分析（对应供货商的技术及数据的价值主张）<br>
>2. API使用者也就是后台开发人员对终端用户提出的需求任务、痛点及增长点按照API客户设计的价值主张来系统整合开发APPs，基于API供货商提供的APIs开放平台以及数据库服务，<br>
>3. 从APPs-APIs-DataService的回路：<br>
>- 将已有成功的APPs或平台，用模块化设计拆出人机交互组件API、云端等等可再组合模块
>- 将已有模块化设计拆出人机交互组件，API、云端等等可再组合设计出符合用户需要的APP或交互产品<br>

```
+ 智能毕业纪念册基于 API开放平台技术的支持来对该款 APP 进行模块化设计，针对用户的不同使用场景来对该款APP的价值主张来进行补充，并且在可实际操作的商业模式下来对API客户和API使用者进行资源的合理调度。
- 用户对于身边即将毕业的同学熟悉度远远低于自身的心理预期，从期望提升用户之间黏连性出发，使用了 人脸融合和语音合成 API接入技术，来对使用场景进行模块化设计，创新使用游戏式模式推出“你合我猜”模块，让用户在互相识别的同时加深对身边同学的了解。
- API客户也就是产品设计人员基于市场调查发现智能毕业纪念册的市场空缺大，并且可复用性低，加上使用智能 API 对产品的特性加成大可为产品带来一定的用户流量
- API使用者也就是产品开发者直接使用已经封装打包好的应用程序接口可以更高效率来进行软件开发，而不是重新去写接口会大大提高识别的准确率，减少bug
- 从APPs-APIs-DataService的回路是需要来进行后台数据库的备份以及上传云端方便进行随时调取，通过使用API提供的云存储服务
```

1. **产品背景**<br>
在 API 开放平台资源丰富情况下，对毕业纪念册进行 API 的调用可以使用最前沿的科技研究成果，将开发效率有效提高，并且在产品的产出过程中使用用户画像与用户同理心来进行功能设计，有效开发出最小可行性产品。针对市面上传统毕业纪念册占比的逐渐减少，而聚合人脸融合和语音合成的新型毕业纪念册市场空缺大，没有相关产品进行有效填补 API 调用的市场空白。语音留言、影像传递很常见，但是将照片进行融合再配上一段语音合成再保存，相信比起只是文字叙述式的保存更有趣和有意义的多，以人脸融合语音猜人的形式为同学之间打开又一道交流之门，意义的价值是翻倍的。

2. **产品场景**<br>
使用最小可行性产品，通过游戏式设计“你合我猜”游戏模块来吸引用户对产品的热度，在对人脸融合和语音合成的技术上合成新语音新照片来进行游戏的同时赋予半社交功能，有效解决同学之间陌生感以及相见的尴尬感降低到最低值，帮助用户走出社交弱圈，提高同学之间的黏连性。

3. **产品目标**<br>
不断对游戏式功能进行迭代设计，并在对用户进行可用性测试与用户研究后比对功能来进行取舍。特色功能对 智能API 的使用来为本产品增加用户的留存率以及提升用户之间的粘连性。

### :star: 用户痛点宣言
(加值的表述是否明文且合理有实据地对映到用户痛点的表述。用户痛点参见 吴雪. 人工智能产品经理 1%*3=3%)

|用户痛点|解决方案|
|---------|-------|
|千篇一律的模板相册套用没有新意，没有可玩性|自主创作，个性化精准服务并提供游戏化模块进行交流互动，扭转弱社交关系|
|电子相册更多是照片的留存，信息更新不及时，实用性弱联系性弱观赏性强|提升效率和准确率，线上查看方便，更新及时，联系快捷|
|自己制作太麻烦，等待周期长|提升用户体验，个人编辑所属页面，使用标签化归属分类|
|特定时间使用，用完即卸载，重复使用率不高|强化功能设计，增加游戏式模块功能，日常激活用户兴趣|

### :star: 人工智能概率性与用户痛点
(AI 概率性考量：使用人工智能的加值的表述是否纳入判断有错的（如假阳 False Positive 假阴 False Negative）的精确概率考量，以确保判错对用户体验的负面影响不会压过正面影响的机率。概率性参见 吴雪. 人工智能产品经理 1%*3=3%)

>判断愿景：实现推断的概率无限逼近100%<br>
>判断标准：在具体的业务场景中，判断人工智能可以达到的推断概率是否能解决用户的需要，及这种概率被用户接收的最低标准是什么、能够超出用户预期的标准是什么，并判断这些判断决定对产品研发的投入策略。<br>
>判断目的：实现概率最优和成本投入（资金投入、技术投入、时间周期选择）之间的平衡<br>

|概率性|用户痛点|
|---------|-------|
|阳性 Positive|千篇一律的模板相册套用没有新意，没有可玩性|
|假阳 False Positive|电子相册更多是照片的留存，信息更新不及时，实用性弱联系性弱观赏性强|
|假阴 False Negative|自己制作太麻烦，等待周期长|
|阴性 Negative|特定时间使用，用完即卸载，重复使用率不高|

### :star: 需求列表与人工智能 API 加值
(使用人工智能的加值是否反映到需求列表（核心功能的排序上）且 PRD 列出明显有可行及可用的 API 1.5%*2=3%)

|经典使用场景|需求列表|核心功能|优先级|可用人工智能API|
|-------|-------|-------|-------|-------|
|点击“你合我猜”进入匿名游戏|对人脸/图像进行融合|你合我猜游戏模块|首要|旷世Face++人脸融合、腾讯AI开放平台人脸融合、百度AI开放平台人脸融合|
|点击“你合我猜”进入匿名游戏|对用户语音进行合成|你合我猜游戏模块|首要|科大讯飞语音合成、百度AI开放平台语音合成、腾讯AI开放平台语音合成|

## :sparkles: 原型-未完成

### :star: 交互及界面设计
(在 PRD 文件中是否有说明且原型是否有做到：交互及界面设计的某个核心交互环节使用了人工智能的加值 1*5%=5%)




1. 有界面交互
2. 有核心你合我猜的人工智能
3. 协同过滤的推荐算法交互

设计APP界面布局达到可视性从而使用户产生可记忆性，流畅的APP交互流程设计可使用户提高对产品的使用效率，增强用户对产品的可学习性

|核心功能|交互设计|界面设计|
|---------|-------|-------|
|你合我猜|上传人脸照片与在线输入语音文本|简洁大方|
|猜测推荐|协同过滤的推荐算法推荐用户界面|简洁大方|


[智能毕业纪念册](http://nfunm065.gitee.io/api_ml_ai_final/#g=1&p=%E6%99%BA%E8%83%BD%E6%AF%95%E4%B8%9A%E7%BA%AA%E5%BF%B5%E5%86%8C)

消息页
>![消息页](https://images.gitee.com/uploads/images/2019/1225/090016_aee6acc4_1831543.png "屏幕截图.png")

推荐页
>![推荐页](https://images.gitee.com/uploads/images/2019/1225/090111_350305df_1831543.png "屏幕截图.png")
>![推荐页](https://images.gitee.com/uploads/images/2019/1225/090151_73a5c46a_1831543.png "屏幕截图.png")


定制页
>![定制页](https://images.gitee.com/uploads/images/2019/1225/090317_ded787c9_1831543.png "屏幕截图.png")
>![定制页](https://images.gitee.com/uploads/images/2019/1225/090345_f7efc934_1831543.png "屏幕截图.png")


我的页
>![我的页](https://images.gitee.com/uploads/images/2019/1225/090247_d4ca2387_1831543.png "屏幕截图.png")









### :star: 信息设计
(在 PRD 文件中是否有说明且原型是否有做到：信息设计的某个核心信息或设计使用了人工智能的加值 1%*5=5%)


1. 有界面交互
2. 有核心你合我猜的人工智能
3. 协同过滤的推荐算法交互

流程图要好好写出来

>![产品前端架构](https://images.gitee.com/uploads/images/2019/1225/085733_fa83e0e8_1831543.png "屏幕截图.png")
>产品CMS后台架构


产品结构图
1 产品功能结构图
2 产品信息结构图


### :star: 原型文档
(多少程度上有提供 MVP 可交互的原型文档，供它人在 Github 上下载使用 1%*5=5%)

1. 有界面交互
2. 有核心你合我猜的人工智能
3. 协同过滤的推荐算法交互

- 最小可行性产品的交互界面可以交互的文档，
- 原型文件要上传GitHub来进行可下载

GitHub 代码下载地址：
[Fork地址](https://gitee.com/NFUNM065/API_ML_AI_final)


[智能毕业纪念册](http://nfunm065.gitee.io/api_ml_ai_final/#g=1&p=%E6%99%BA%E8%83%BD%E6%AF%95%E4%B8%9A%E7%BA%AA%E5%BF%B5%E5%86%8C)








1. 功能权限
- 功能权限分为登录/未登录两个状态
（1）登录：用户登录状态下可对APP进行所有功能操作
（2）未登录
-未登录状态可以搜索联系人活动，查看联系人部分信息，私密信息进行隐藏。。。
-但是无法查看信息，签到，打开联系人，查看我的福利，参与评论，打开个人tab等需要个人账号信息的功能

- 键盘说明
(1)点击输入手机号码、手机验证时从页面底部弹出数字键盘；
(2)点击输入其它内容时从页面底部弹出字母键盘
- 页面内交互
- 页面异常
- 页面间交互
- 更多操作

2. 主要业务逻辑流程图
登录注册
订单业务

3. 页面详细功能说明
启动页

### :star: 口头操作说明
(多少程度上在 2-3 分钟时间限制内，对听众留下了「的确这是个可行丶可用的人工智能加值产品」的印象 1%*5=5%)

2-3分钟让观众来对这个产品留下深刻的印象，这是个可以使用的人工智能产品




1. 页面逻辑&交互说明：
登录注册触发条件
- 登录
(1)页面逻辑内容
(2)页面交互说明
- 注册
(1)页面逻辑内容
(2)页面交互说明
- 首页
(1)首页交互说明
- 搜索
(1)页面逻辑内容
(2)页面交互说明
- 推荐
(1)页面逻辑内容
(2)页面交互说明
- 新品
(1)页面逻辑内容
(2)页面交互说明
- 众筹
(1)页面逻辑内容
(2)页面交互说明
- 识物
(1)页面逻辑内容
(2)页面交互说明
- 分类
(1)页面逻辑内容
(2)页面交互说明




## :sparkles: API 产品使用关键 AI 或机器学习之API的输出入展示-没有正确理解输入及输出的是什么

### :star: 使用水平
(在 PRD 文件中是否有说明且展示，核心功能所应用的 API 之输入及输出 1%*5=5%)

概要：核心功能 **你合我猜** 的代码展示—— **人脸融合与语音合成API** (同一公司平台的不同类型API) + **协同过滤推荐算法**

:computer: 1. **人脸融合**


<div align="center">
  <h3>Face++-人脸融合API</h3>
</div>

[Face++ 人脸融合 python 示例代码地址](https://github.com/wenjunmo/API_ML_AI_SmartMemorial/blob/master/API%20%E5%8F%AF%E5%A4%8D%E7%94%A8%E4%BB%A3%E7%A0%81/Face++%E4%BA%BA%E8%84%B8%E8%9E%8D%E5%90%88%20python%E7%A4%BA%E4%BE%8B.md)

jupyternotebook 截图如下

>![Face++人脸融合requests1](https://images.gitee.com/uploads/images/2019/1224/193433_4f11cb3e_1831543.png "屏幕截图.png")

>![Face++人脸融合requests2](https://images.gitee.com/uploads/images/2019/1224/193612_3e979b83_1831543.png "屏幕截图.png")


上面自动生成的 1.jpg 图片会直接生成在生成它的代码文件中并放在同一文件夹中

>![生成的1.jpg在文档中位置](https://images.gitee.com/uploads/images/2019/1224/194055_126979d3_1831543.png "屏幕截图.png")

-------


<div align="center">
  <h3>百度大脑 AI开放平台-人脸融合API</h3>
</div>

[百度 AI 人脸融合 python 示例代码地址](https://github.com/wenjunmo/API_ML_AI_SmartMemorial/blob/master/API%20%E5%8F%AF%E5%A4%8D%E7%94%A8%E4%BB%A3%E7%A0%81/%E7%99%BE%E5%BA%A6AI%20%E4%BA%BA%E8%84%B8%E8%9E%8D%E5%90%88%20python%20%E7%A4%BA%E4%BE%8B.md)

jupyternotebook 截图如下

>![百度人脸融合的token获取](https://images.gitee.com/uploads/images/2019/1224/194845_d6e00552_1831543.png "屏幕截图.png")

首先必须要拿到 access token ，拿到之后，还需要将图片进行 base64 编码后再来进行合成


```
# 这是将图片进行 base64 编码的代码，可直接调用

import base64

with open('1.jpg', 'rb') as f:  # 以二进制读取图片
    data = f.read()
    encodestr = base64.b64encode(data) # 得到 byte 编码的数据
    print(str(encodestr,'utf-8'))  # 重新编码数据
```

下面是将图片转换为 base64 输出

>![两张图片都必须是在同一个文件夹和代码放在一起](https://images.gitee.com/uploads/images/2019/1224/204058_3317173c_1831543.png "屏幕截图.png")

上面这两张图片放置的位置都必须是在同一个文件夹和将要运行的代码文件放在一起

>![2图片的储存在同一个文件下](https://images.gitee.com/uploads/images/2019/1224/204704_aa42bdcf_1831543.png "屏幕截图.png")

>![上传两张图片的base64码](https://images.gitee.com/uploads/images/2019/1224/204238_8e36c589_1831543.png "屏幕截图.png")

代码结束的最后得到 获取返回的 json 值

>![获取返回的json值](https://images.gitee.com/uploads/images/2019/1224/211001_02d60e88_1831543.png "屏幕截图.png")
 
---------

:computer: 2. **语音合成**

<div align="center">
  <h3>腾讯AI开放平台-语音合成API</h3>
</div>

[腾讯 AI 语音合成 python 示例代码地址](https://github.com/wenjunmo/API_ML_AI_SmartMemorial/blob/master/API%20%E5%8F%AF%E5%A4%8D%E7%94%A8%E4%BB%A3%E7%A0%81/%E8%85%BE%E8%AE%AF%20AI%20%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%20python%20%E7%A4%BA%E4%BE%8B.md)


jupyternotebook 截图如下

>![腾讯语音合成notebook代码截图](https://images.gitee.com/uploads/images/2019/1224/101352_71f36a7f_1831543.png "屏幕截图.png")

>![腾讯语音合成wav01.wav存储位置截图](https://images.gitee.com/uploads/images/2019/1224/101547_57bc3ec5_1831543.png "屏幕截图.png")

上面生成的文件会保存在 filepath 的上一层目录下

-------



<div align="center">
  <h3>百度大脑AI开放平台-语音合成API</h3>
</div>

jupyternotebook 截图如下

[百度 AI 语音合成 python 3种 示例代码地址](https://github.com/wenjunmo/API_ML_AI_SmartMemorial/blob/master/API%20%E5%8F%AF%E5%A4%8D%E7%94%A8%E4%BB%A3%E7%A0%81/%E7%99%BE%E5%BA%A6%20AI%20%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%20python%20%E7%A4%BA%E4%BE%8B.md)

第一种调用办法：

>![百度AI语音合成nupyternotebook运行成功](https://images.gitee.com/uploads/images/2019/1224/111344_f8a5df61_1831543.png "屏幕截图.png")

因为是用 jupyternotebook 来进行打开并且存储的，那么生成的 result.mp3 的文件就是可以保存生成在和书写这个代码的文件是放在一起的，不是jupyternotebook 的目录，而是在哪个文件里面生成它就是在哪个文件夹里面找到生成的文件就是好了

>![百度AI语音合成生成 result.mp3 生成位置](https://images.gitee.com/uploads/images/2019/1224/110947_c01f3dad_1831543.png "屏幕截图.png")

当生成的文件在文件快速访问里面没有，推荐下载 everything 但还是使用命令行来进行搜索

>dir C:\ G:\ H:\ W:\ X:\ /s /b | find "result.mp3"

>![使用命令行来搜索生成 mp3 的具体位置](https://images.gitee.com/uploads/images/2019/1224/111716_81ed72ac_1831543.png "屏幕截图.png")


第二种调用办法：

>![百度云1](https://images.gitee.com/uploads/images/2019/1224/124846_1ad9f3a3_1831543.png "屏幕截图.png")

>![百度云2](https://images.gitee.com/uploads/images/2019/1224/125014_4137f760_1831543.png "屏幕截图.png")

>![百度云3](https://images.gitee.com/uploads/images/2019/1224/125153_8fb20156_1831543.png "屏幕截图.png")

>![百度云4](https://images.gitee.com/uploads/images/2019/1224/125309_b575162a_1831543.png "屏幕截图.png")

但它不是生成在指定的文件目录而是和 result.mp3 一样都是生成和生成它的这段代码所在的文件夹中

>![百度云文件 小白.mp3 生成位置](https://images.gitee.com/uploads/images/2019/1224/125544_ed80df54_1831543.png "屏幕截图.png")


将上面的代码来进行简化就是可以得到一个不用进行交互而是直接就是可以来进行输出，其实就是已经将需要输出的文本放进去直接来用就好了


上面的代码同时是直接就是来生成了 test.mp3 在和生成它的代码文件在同一个文件夹里面，虽然没有响应显示但是是真真实实生成了并且有内容

>![百度云 test.mp3 生成](https://images.gitee.com/uploads/images/2019/1224/130950_50b6a743_1831543.png "屏幕截图.png")

>![test.mp3 生成的目录](https://images.gitee.com/uploads/images/2019/1224/131259_58e7fb59_1831543.png "屏幕截图.png")









### :star: 使用比较分析
(在 PRD 文件中是否有说明且提供连结证据，所使用的 API 是查找过最适用的（主要竞争者无或比较次），如考量其成熟度丶性价比丶等等 1%*5=5%)

可以借鉴表格，需要有链接也就是API的链接，判断最实用的，比较主要竞争者合比较次的竞争者，成熟度丶性价比等比较来做好表格


人脸融合+语音合成 可复用性代码：

- [Face++ 人脸融合 python 示例代码地址](https://github.com/wenjunmo/API_ML_AI_SmartMemorial/blob/master/API%20%E5%8F%AF%E5%A4%8D%E7%94%A8%E4%BB%A3%E7%A0%81/Face++%E4%BA%BA%E8%84%B8%E8%9E%8D%E5%90%88%20python%E7%A4%BA%E4%BE%8B.md)
- [百度 AI 人脸融合 python 示例代码地址](https://github.com/wenjunmo/API_ML_AI_SmartMemorial/blob/master/API%20%E5%8F%AF%E5%A4%8D%E7%94%A8%E4%BB%A3%E7%A0%81/%E7%99%BE%E5%BA%A6AI%20%E4%BA%BA%E8%84%B8%E8%9E%8D%E5%90%88%20python%20%E7%A4%BA%E4%BE%8B.md)
- [腾讯 AI 语音合成 python 示例代码地址](https://github.com/wenjunmo/API_ML_AI_SmartMemorial/blob/master/API%20%E5%8F%AF%E5%A4%8D%E7%94%A8%E4%BB%A3%E7%A0%81/%E8%85%BE%E8%AE%AF%20AI%20%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%20python%20%E7%A4%BA%E4%BE%8B.md)
- [百度 AI 语音合成 python 3种 示例代码地址](https://github.com/wenjunmo/API_ML_AI_SmartMemorial/blob/master/API%20%E5%8F%AF%E5%A4%8D%E7%94%A8%E4%BB%A3%E7%A0%81/%E7%99%BE%E5%BA%A6%20AI%20%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%20python%20%E7%A4%BA%E4%BE%8B.md)



<div align="center">
  <h3>人脸融合</h3>
</div>



1.1 [Face++ 人脸融合 官网实验](https://www.faceplusplus.com.cn/face-merging/)


>![Face++人脸融合](https://images.gitee.com/uploads/images/2019/1224/214239_a66bc4f5_1831543.png "屏幕截图.png")

1.2 [Face++人像处理API价格](https://www.faceplusplus.com.cn/v2/pricing-details/#api_4)

>![Face++人像处理API价格](https://images.gitee.com/uploads/images/2019/1224/214630_a1ec1836_1831543.png "屏幕截图.png")


2.1 [百度AI 人脸融合 官网实验](https://ai.baidu.com/tech/face/merge)

>![百度AI人脸融合](https://images.gitee.com/uploads/images/2019/1224/215101_62b9386f_1831543.png "屏幕截图.png")

2.2 [百度AI人像处理API价格](https://ai.baidu.com/ai-doc/FACE/Ck37c1lmj)

>![百度AI人像处理API价格](https://images.gitee.com/uploads/images/2019/1224/215533_293e7a7d_1831543.png "屏幕截图.png")


|比较分析|Face++ 人脸融合|百度AI 人脸融合|腾讯AI 人脸融合|
|-------|---------------|--------------|-------------|
|优先级  |:one:          |:two:         |未开放       |
|成熟度  | :star: :star: | :star:       |未开放       |
|性价比  |按量:0.1元/次-低|前500次免费，超出 0.04元/次-高|未开放|
|准确度  | :star: :star:  |:star:       |未开放       |
|拓展性  | :star: :star:  |:star:        |未开放      |
|优势    |人脸融合场景多样，开发文档详细，调用权限较少，不需获取 access_token ，代码实现有 python 等轻量级语言 |人脸融合高清磨合，不会很相似也不会失真很厉害|未开放      |
|劣势    |代码不够明确和完善，必须要开发者来直接进行提取不能直接上手，开发效率没有符合预期|人脸融合场景少，代码开发实现效率低下，文档不全，对新手不友好，但对有基础会比较简单|未开放      |
|最适用  | :heavy_check_mark:    | :o:            | :x:  |




<div align="center">
  <h3>语音合成</h3>
</div>


1.1 [科大讯飞 语音合成 官网实验](https://www.xfyun.cn/services/online_tts)


可以针对不同的用户来进行比较，比如说有新用户和老客户和回头客
250词
88+种的语音可以调用并且划分等级为特色发声人78人包括场景与声音年龄段筛选个性化，精品发声人5人，基础发声人5人免费
语速+音量
有背景音乐来符合词的个性，声音比腾讯好听一点，并且在换行之间不会讲的很快，可以有间隔来讲不像百度一样

>![科大讯飞语音合成](https://images.gitee.com/uploads/images/2019/1224/225930_b898a822_1831543.png "屏幕截图.png")

1.2 [科大讯飞语音合成API价格](https://www.xfyun.cn/services/online_tts)

>![科大讯飞语音合成API价格](https://images.gitee.com/uploads/images/2019/1224/230349_257ae8da_1831543.png "屏幕截图.png")




2.1 [百度云 语音合成 官网实验](https://cloud.baidu.com/product/speech/tts)

200字 4种选择声音语速+音调+音量

>![百度云语音合成](https://images.gitee.com/uploads/images/2019/1224/222758_583a75bc_1831543.png "屏幕截图.png")

2.2 [百度云语音合成API价格](https://ai.baidu.com/ai-doc/SPEECH/Nk38y8pjq)

![百度云语音合成API定价](https://images.gitee.com/uploads/images/2019/1224/223121_1b358da1_1831543.png "屏幕截图.png")


2.3 [腾讯AI 语音合成 官网实验](https://ai.qq.com/product/aaitts.shtml)

50字 两个平台腾讯AI Lab 和腾讯优图
4种声音类型
音高+音量+音色+语速
在段落之间也就是换行间比百度要慢速一点听得更加舒服，而百度是很着急直接念完 1男3女声，百度是2:2利用情感来进行分析

> ![腾讯AI语音合成](https://images.gitee.com/uploads/images/2019/1224/223739_b905660c_1831543.png "屏幕截图.png")

没有收费项目在网站上面查找到相关资讯，在开放平台没有搜索到相关收费信息

腾讯在代码层次上讲，官方压根没有合成示例文档啊 (咆哮 ing)，全自己摸索的啊 (咆哮 ing)，SDK 都开发出来了，示例代码给一下能死啊 (咆哮 ing)，怪不得没人用啊 (咆哮 ing)！在合成效果上讲，声音难听爆了有木有，语音文件还得解码再 I/O, 吃饱了撑的了啊，还是那句话：怪不得没人用，百度语音合成效果比你强多了。
网易AI开放平台语音合成并没有开放使用网页端没有，只有微信小程序体验版网易 AI 体验中心，限制50字，语速只有正常慢速快速之分，没有API可以调用




网易AI语音合成没有文档
科大讯飞的语音合成找不到文档就是按照上课来进行书写代码的调用了
Face++没有语音合成
腾讯没有语音合成的pythn代码不友好只有PHP的代码





### :star: 使用后风险报告
(在 PRD 文件中是否有说明且提供连结证据，所使用的 API 类别的现在及未来发展性，如 API 市场竞争程度丶输入输出限制丶定价丶及可替代的程序库（改用自己开发的代码及数据库而不用 API）等等 1%*5=5%)

现在及未来发展性，API 市场竞争程度丶输入输出限制丶定价丶及可替代的程序库（改用自己开发的代码及数据库而不用 API）都要写上来

准确度
响应度
价格
优点缺点

弄符号和自己实验过程中出现的展示和数据来进行说明


有调用的次数后面再来自己进行调用比较之间的区别

人脸融合


|比较|Face++API|百度云API|腾讯API|
|----|----|---|---|
|调用难易程度|----|---|---|
|调用响应程度|----|---|---|
|价格高低程度|----|---|---|
|文档完善程度|----|---|---|
|用户体验程度|----|---|---|



语音合成

|比较|百度云API|腾讯API|科大讯飞API|网易API|
|----|----|---|---|---|
|调用难易程度|----|---|---|---|
|调用响应程度|----|---|---|---|
|价格高低程度|----|---|---|---|
|文档完善程度|----|---|---|---|
|用户体验程度|----|---|---|---|






1. 人脸融合

- 旷世Face++人脸融合

- 腾讯AI开放平台人脸融合

- 百度AI开放平台人脸融合

2. 语音合成

- 科大讯飞语音合成

- 腾讯AI开放平台语音合成

- 百度AI开放平台语音合成

- 网易AI开放平台语音合成




### :star: 加分项
(使用复杂度：用了 2 个以上机器学习与人工智能的 API 之输入及输出 1%*3=3%)

最少要3个的API的测试文档和实践好的代码链接翻上来

附件加清单自己的代码下载和原型展示和下载



基于协同过滤的推荐算法，常见的包括基于用户、基于物品的协同过滤。





### :sparkles: 六、总结

附录：

- [Reveal.js：把你的 Markdown 文稿变成 PPT](https://sspai.com/post/40657)
- [Marp：用 Markdown「写」PPT 的新选择](https://sspai.com/post/55718)


我们大多数人所理解的人工智能技术可能还停留在算法本身，但实际上真正的人工智能应用针对不同的领域，不仅有各自的算法，事实上还包括其他领域知识的应用，如自动化控制理论、电子技术、通信技术、机械工程等等，因此我们所理解的人工智能，应该是一个系统工程。网络中有一张图，讲述的是人工智能的深渊，毫不夸张的说，这其中的随便挑一项技术都是科研学者花费大量时间和精力去研究的，很少有人能够全面了解所有知识领域。
市场的接受情况

产品的架构和路径是什么样的
产品的流量是如何运作的
产品的商业化是如何完成的：

产品化决定了产品的价值空间，商业化则决定了产品将价值变现的能力。

这造成了一方面产品在研发阶段投入的成本具有不确定性，另一方面技术的预期效果也比较难评估。

制定产品的定价策略，而是需要站在用户角度考虑产品定价策略，深入理解场景和用户的痛点在哪里。

马上完成
