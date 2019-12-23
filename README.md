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
> 3. 400 秒版本 Pecha Kucha 20x20 版本 (线上投影片含可查连结)<br>

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
|v1.0|11.20-12.01|文档初稿撰写，建立基本产品文档框架，添加重要产品理念与技术开发项目流程|莫文俊|
|v2.0|12.01-12.08|测试可用 API 并进行可用性测试比对，进行市场回访调查|莫文俊|
|v3.0|12.08-12.15|选定 API 类型并实现测试运行，产品后台代码实现可用|莫文俊|
|v4.0|12.15-12.22|开发 APP 原型，制作低保真原型初步实现逻辑|莫文俊|
|v5.0|12.23-     |产品上线并进行不断功能反馈|莫文俊|

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
> “想念，是好久不见的表达”

本软件基于人脸融合和语音合成研发的智能毕业纪念册，适用于任何想快速生成个性化毕业纪念册图集与校友连结的通讯录用户，不再为毕业后各自分飞而找不到联系方式而苦恼，不再为电子相册保存平台过多整理繁琐以及扫码失效，游戏化模块组件 “**你合我猜**” 更是能够解决多年老友不相见而健忘的尴尬场景，主打游戏化解锁新合成语音照片，在享受猜脸乐趣同时回忆逝去的青春美好。

## :sparkles: 市场背景

通过调查研究发现，移动互联网端以及通讯设备的普及，市面上新型毕业纪念册大部分都是基于上传图片形成个人图片库，搭配个性化音乐来产出音乐纪念相册，观赏性用大于实际联系性用。在高速发展的信息时代，信息不再局限于文本格式，相较于传统纸质毕业纪念相册，更多的是伴随着语音信息和影像信息，纸质媒介渐渐被人遗忘。<br>
APP 形式无疑是一种可以涵盖更多不同信息形式的新型毕业纪念册，在进行了人脸融合和语音合成API的调取后生成，而使用游戏化模块的智能毕业纪念相册会更有实际意义。

:star: **优势**

>- 涵盖多样化信息（ 相较传统纸质纪念册），使用便捷性提高（相较于网页版）
>- 市场上占比少可忽略，而大多数 APP 纪念册多为个人开发专用，忽视大多数大学生群体的市场，市场有待进一步扩张
>- 大部分产品功能设计往全社交类方向进行引导，模糊了本身的产品定位，阻碍发展

:star: **竞品分析**

>1. 竞品一：微吾H5自助工具制作毕业纪念册<br>
>优点：<br>
>- 采用接龙的形式进行信息收集、纪念册制作。将工作量平摊到每个人，每人负责完成自己的纪念模块
>- 无需下载软件，接收链接或二维码编辑者，可个人和集体编辑，可随时随地欣赏分享
>- 更新方便及时，易于维护，可转换成电子书下载成pdf
>- 互相赠言，还有很邪恶的悄悄话功能<br>
>缺点：<br>
- 停留在传统毕业纪念册，没有科技感，信息留存较少<br>

>2. 竞品二：时光流影网站<br>
>优点:<br>
>- 直接上传图片进行模板个性化定制设计，有成熟模板供选择
>- 分享链接与生成二维码<br>
>缺点:<br>
- 网页编辑不容易，没有轻便和简洁，更新慢<br>

>3. 竞品三：微信公众号微影相册<br>
>优点:<br>
>- 直接选择手机里的照片，然后选主题模板滤镜音乐，就能做出来影集了
>- 支持一键保存在手机内存中<br>
>缺点:<br>
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
>- 主要针对的人群集中在即将毕业的大学生，对新型模式的纪念册排斥度会较小，接受度较高，而且善于接受新鲜事物
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

本着满足大部分人群对 APP 形式便捷的需求，同时满足小部分人群对纸质毕业纪念册传统感的追求，同时最新颖的特点是应用了高新技术 API 的调用，基于人脸融合与语音合成 API 场景化使用，通过对照片与语音合成处理，将用户数据上传云端并进行备份，可随时进行调取<br>

综合分析市场研究和调查，目前市面上并没有推出一款具体的使用人工智能 API与机器学习 的智能毕业相册APP，市面上的大多数都是以链接或者是纸质版留存为准，纪念意义大于使用意义，没有后续的使用价值，没有办法通过毕业纪念册来进行产品后续的自我价值，也没有很好起到沟通的效果，与产品设计的初衷有悖，并且通过调查，使用线上的程序或者是 APPs 在移动互联网下会有更多的使用场景和可以辨别的，使用频率和次数会增加，并且用户场景会更多<br>

## :sparkles: 价值主张设计

### :star: 加值宣言

智能毕业纪念册的价值主张：

- 个性化定制，展示个性，千人千面
根据个人的喜好来制作，每个留言的人想要填写的内容和表现形式也很随意，可以增加个人小档案等，每位用户的纪念册都是不一样。在基于用户画像为用户推荐更加精准的设计功能
- 功能贴合生活，适应技术需要，符合时代发展潮流
在人工智能时代，API开放的平台使越来越多的设计交互者更容易设计针对不同用户场景的产品功能，在基于用户同理心和对新技术好奇的心理上会增加更多的人际联系
- 留念方式新颖，辅助社交，适当提高粘连度
与传统毕业纪念册的线下耗费时间与人力填写，使用线上会更加注重时间利用的效率，在半隐形社交的圈子内可以更好兼顾校园资源，打造不一样的社交圈子

### :star: 核心价值宣言

#### :star2: 背景

在API开放平台资源丰富情况下，对毕业纪念册进行API的调用可以使用最前沿的科技研究成果，将开发效率有效提高，并且在产品的产出过程中使用用户画像与用户同理心来进行功能设计，有效开发出最小可行性产品。针对市面上传统毕业纪念册占比的逐渐减少，而聚合人脸识别和语音识别的新型毕业纪念册市场空缺大，没有相关产品进行有效填补API调用的市场空白。语音留言、影像传递很常见，但是将照片配上一段语音再保存，相信比起只是文字叙述式的保存更有趣和有意义的多，以语音留言的格式为同学留下一段祝福寄语，并能永久保存的话，意义的价值是翻倍的。毕业纪念册能体现时代特色，能够看出当年毕业生关注的热点。

#### :star2: 目的
在对人脸图像进行识别以及语音识别留存，保存在校生活的宝贵瞬间，有效留存时光的印记，并且不易丢失可随时调取查看。同时赋予半社交功能，有效整合校园资源并且将有限校园资源与社会资源有效联通

#### :star2: 目标
先使用最小可行性产品进行功能迭代设计，在进行用户可用性测试与用户研究后对功能进行取舍。在提供毕业纪念册完整产品链服务的同时对毕业后联系方式以及动态进行记录，有效对用户留存度以及用户粘连度进行提高


> 运用价值主张(Value propositions)来对商业模式(Business models)进行剖析，使用应用程序编程接口(Application Programming Interface API)来对API经济(API Economy)、API开放平台(API Open Platform)以及模块化(Modularization)来对利害关系(Stakeholder)的两方：API面向客户(API Customer)和API使用者(API Consumer)来进行资源合理配置。

> 智能毕业纪念册基于API开放平台技术的支持来对该款APP进行模块化设计，针对用户的不同使用场景来对该款APP的价值主张来进行补充，并且在可实际操作的商业模式下来对API客户和API使用者进行资源的合理调度。

> 利害关系图的阐述：产品设计开发人员（API客户）+ 系统整合开发人员（API使用者）+ 终端用户 + API/智能云端供货商（API提供者）

> 上面是四个角色，但是活动的流程是这样子：
> 1. API客户也就是产品经理来对智能产品的价值主张进行设计（对应到终端用户的用户需求的任务、痛点及增长点），对智能/平台/模块成本效益进行分析（对应供货商的技术及数据的价值主张）
> 2. API使用者也就是后台开发人员对终端用户提出的需求任务、痛点及增长点按照API客户设计的价值主张来系统整合开发APPs，基于API供货商提供的APIs开放平台以及数据库服务，

> 从APPs-APIs-DataService的回路：
1. 将已有成功的APPs或平台，用模块化设计拆出人机交互组件API、云端等等可再组合模块
2. 将已有模块化设计拆出人机交互组件，API、云端等等可再组合设计出符合用户需要的APP或交互产品


### :star: 用户痛点宣言

|用户痛点|解决方案|
|-------|-------|
|纸质版相册贵留存会受不可控因素遗失或损坏|在云端对用户信息进行永久留存|
|联系渠道狭窄并且极易过时，可复用性程度不大|联系方式查看方便，更新及时，联系快捷|
|固定一段时间后只剩下一纸照片怀念，没有办法对实际联系产生任何帮助，可联系性差且效用性低|对半社交进行定义|


- 传统的电子纪念册的3需2缺
1. 3大需要
- 需要下载软件
- 需要完成所有同学信息的收集
- 需要特定的同学制作班级的毕业纪念册
2. 2大缺陷
- 信息更新不及时，维护成本高
- 欣赏不方便，分享难上加难


“想念”以及slogan“想念，恋你的颜和言”一句新颖话语道出了用户主要痛点
- 在大学毕业后大家各奔东西，奔赴天涯海角，同学情谊想念却难以联系，联系的频次大幅降低，渴望增强同学之间之间的活力
- 缺乏聚合信息的平台来对相册已经联系信息的时事更新有一定的愿望和需求
- 定位为毕业后专门留存资讯与联系方式的智能毕业纪念册，扭转弱社交关系
- 主打人脸与语音API识别场景化应用，有效贴合生活实际


### :star: 人工智能概率性与用户痛点

|概率性|用户痛点|
|-------|-------|
|大|怎么将照片可以永久留念|
|大|怎么将语音永久留存|


### :star: 需求列表与人工智能API加值

|需求列表|人工智能API|
|-------|-------|
|对人脸/图像进行识别|旷世Face++人脸识别、腾讯AI开放平台人脸识别、Axure人脸识别、百度AI开放平台人脸识别|
|对用户语音进行识别|科大讯飞语音识别、百度AI开放平台语音识别、腾讯AI开放平台语音识别|

## :sparkles: 原型

### :star: 交互及界面设计

设计APP界面布局达到可视性从而使用户产生可记忆性，流畅的APP交互流程设计可使用户提高对产品的使用效率，增强用户对产品的可学习性


### :star: 信息设计
产品结构图
1 产品功能结构图
2 产品信息结构图


### :star: 原型文档
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

## :sparkles: API 产品使用关键AI或机器学习之API的输出入展示

### :star: 使用水平

1. 人脸识别

- 旷世Face++人脸识别
- 腾讯AI开放平台人脸识别
- Axure人脸识别
- 百度AI开放平台人脸识别

2. 语音识别
- 科大讯飞语音识别
- 腾讯AI开放平台语音识别
- 百度AI开放平台语音识别



### :star: 使用比较分析


1. 人脸识别-人脸检测与属性分析

- 旷世Face++人脸识别



![Face++Face](https://images.gitee.com/uploads/images/2019/1211/083658_bc4cf548_1831543.png "屏幕截图.png")


- 腾讯AI开放平台人脸识别

![TencentFace](https://images.gitee.com/uploads/images/2019/1211/083940_ef1ea3b9_1831543.png "屏幕截图.png")

- Axure人脸识别

- 百度AI开放平台人脸识别

![baiduFace](https://images.gitee.com/uploads/images/2019/1211/084319_597fac32_1831543.png "屏幕截图.png")


2. 语音识别

- 科大讯飞语音识别

![XunfeiVoice](https://images.gitee.com/uploads/images/2019/1211/084823_cbe441aa_1831543.png "屏幕截图.png")

- 腾讯AI开放平台语音识别

![TencentVoicelab](https://images.gitee.com/uploads/images/2019/1211/085133_7012276f_1831543.png "屏幕截图.png")
![TencentVoiceChat](https://images.gitee.com/uploads/images/2019/1211/085308_712c8375_1831543.png "屏幕截图.png")

- 百度AI开放平台语音识别








### :star: 使用后风险报告


1. 人脸识别

- 旷世Face++人脸识别

- 腾讯AI开放平台人脸识别

- Axure人脸识别

- 百度AI开放平台人脸识别

2. 语音识别

- 科大讯飞语音识别

- 腾讯AI开放平台语音识别

- 百度AI开放平台语音识别




### :star: 加分项






### :sparkles: 六、总结

先来船传江



附录：

[Reveal.js：把你的 Markdown 文稿变成 PPT](https://sspai.com/post/40657)
[Marp：用 Markdown「写」PPT 的新选择](https://sspai.com/post/55718)



