# Project Name：想念

## Product Documentation(产品需求文档)

|标题|内容|
|----|---|
|产品名称(product name)|想念|
|产品全栈(Product Full Stack)|莫文俊|
|文档所有者(Document owner)|莫文俊|
|发布日期(Release date)|2019.12|

- 版本修订记录

|修订版本号|迭代日期|修订内容|迭代者|
|---------|-------|--------|-----|
|v1.0|2019.11.20|文档初稿撰写，建立基本产品文档框架，添加重要关键词|莫文俊|
|v1.1|2019.11.26|-------|莫文俊|
|v2.0|2019.11.27|-------|莫文俊|
|v2.1|2019.11.28|-------|莫文俊|
|v2.2|2019.12.01|-------|莫文俊|
|v2.3|2019.12.04|-------|莫文俊|
|v2.4|2019.12.10|-------|莫文俊|

- 文档输出环境

|文档名称|版本号|体验环境|撰写时间|撰写人|
|---------|-------|--------|-----|----|
|想念智能APP|v3.1|Andrio10|2019.1.26|莫文俊|

## Documentation Directory(文档目录)

- [产品介绍]()
- [市场背景]()
- [价值主张设计]()
  - [加值宣言]()
  - [核心价值宣言]()
  - [用户痛点宣言]()
  - [人工智能概率性与用户痛点]()
  - [需求列表与人工智能API加值]()
- [原型]()
  - [交互及界面设计]()
  - [信息设计]()
  - [原型文档]()
  - [口头操作说明]()
- [API 产品使用关键AI或机器学习之API的输出入展示]()
  - [使用水平]()
  - [使用比较分析]()
  - [使用后风险报告]()
  - [加分项]()



## 产品介绍

“我们，重新定义毕业纪念册”
“想念，是好久不见的表达”

本软件基于人脸识别和语音识别开发的智能毕业纪念册，适用于任何想快速生成个性化毕业纪念册图集与校友连结的通讯录用户，不再为毕业后各自分飞而找不到联系方式而苦恼，不再为电子相册保存平台过多整理繁琐以及扫码失效，利用人脸识别进行照片比对以及语音识别进行语音留存来留住青春的容颜与声音。

## 市场背景

通过调查研究发现，市面上做毕业纪念册的方式都基于图片上传做成音乐相册，只有观赏性而没有联系的实用性。

在高速发展的信息时代，信息不再局限于文本格式，更多伴随着语音信息和影像信息，而纸质媒介渐渐被人遗忘。毕业纪念册也面临着相同的转变，APP形式无疑是一种可以涵盖更多不同信息形式的新型毕业纪念册，在进行了人脸识别和语音识别API的调取后会更加注重用户体验与同理心设计。

### 为什么使用APP纪念册：

- 可涵盖多样化信息（ 相较传统纸质纪念册），满足信息多元化的同时在使用时便捷性提高（相较于网页版）
- 市场上占比并不多可以说是微乎其微，而大多数APP纪念册多为自己学校开发专用，忽视了大多数大学生群体的市场，没有进一步扩展市场
- 在功能的设计上，很多将APP往全社交类的方向进行引导，将纪念册APP定位成全社交类，反而模糊了本身的产品定位，阻碍发展

### APP纪念册竞品分析

### APP纪念册用户调查问卷

1. 对纪念大学生生涯和同学友谊最有意义的形式是：毕业纪念册、聚餐、拍视频照片、送礼物
2. 假如推出个性定制化毕业纪念册会买吗：很有意义，买、内容设计吸引，考虑买、不买，浪费钱
3. 买毕业纪念册看重哪一种因素：设计新颖、内容丰富、流行
4. 考虑的性价比有哪些因素：价格贵质量好但便于保存、价格适中质量过得去、价格便宜普遍接受没有很大需求、价格无所谓没有要求
5. 毕业纪念册的价格多少可以接受：10-30、30-60、60-100
6. 购买毕业纪念册的最佳时机：4月、5月、6月、7月
7. 希望添加额外的功能：个人基本信息姓名联系方式、全体毕业照、同学留言、学院老师寄语、个人感言、校园风景、专业特色、校卡使用
8. 你心目中理想的毕业纪念册的样式（内容、封面设计、排版）是（开放题）

### 纪念册APP明确的产品定位

- 功能上还原传统纸质纪念册中的信息填写，同学寄语等，适当减少社交类的功能
- 对各种格式信息进行保存，加入图片信息、语音信息、视频信息等

### 纪念册APP目标群体大学生

- 主要针对的人群集中在即将毕业的大学生，对新型模式的纪念册排斥度会较小，接受度较高，而且善于接受新鲜事物
- 大学生是手机用户的一大类人群，使用手机主要表现在满足沟通、娱乐、学习等需求上，情感价值主要表现在对个性化、时尚、分享交流的追求上
- 现代信息的多元化，信息的交流和保存不再局限于文字的格式，更多的信息是图片格式、语音格式和视频格式
- 功能设计中加入语音和视频信息的储存交流功能既满足大学生群体沟通的需求同时也满足大学生对个性化分享交流的追求

### 商业模式

据毕业生提供的影印照片和成长资料，专门为其量身定做了毕业纪念册。

- 针对阶段性的学习生活进行记录，并采取前期免费模式推广，使用部分匿名社交模式进行收费与互动
- 规范制作纪念册的“生产线”，推出精装版、简装版和平装版，不同的版式有着不同的价格，并针对于”贵宾“客户推出折扣
- 提供图文的排版设计、礼品制作，策划活动，提供聚会地安排、DV拍摄、礼物派送、纪念册制作等完整服务链
- 除具备聊天加好友的功能之外，还加入招聘、婚恋、聚会、创业等辅助功能（有待商榷）
- 同时提供纸质版服务，配合平面设计建立多模板，为用户提供多样性的选择空间进行个性化定制

本着满足大部分人群对APP形式便捷的需求，同时满足小部分人群对纸质毕业纪念册传统感的追求，同时最新颖的特点是应用了高新技术API的调用，基于人脸识别与语音识别API的场景化使用，通过对照片的分析和语音处理，将用户数据上传云端并进行备份，并随时进行调取


## 价值主张设计

### - 加值宣言

智能毕业纪念册的价值主张：

- 个性化定制，展示个性
单独写给某一位同学的留言和班级上完全公开的校友录等不同，能够更多地说出真心话，也可以写更私密的东西，比如道歉、表白等。
网络上统一的字体和符号完全比不上一本全部由同学亲笔填写的小册子，每个人的笔迹本身就是有纪念价值的，多年以后再翻看，感觉一定很温馨。
毕业纪念册能体现时代特色，能够看出当年毕业生关注的热点。

个人的喜好来制作，每个留言的人想要填写的内容和表现形式也很随意，可以增加个人小档案等，也能够画画、折纸，能够更好
语音留言、影像传递

将照片配上一段语音再保存，相信比起只是文字叙述式的保存更有趣和有意义的多，以语音留言的格式为同学留下一段祝福寄语，并能永久保存的话，意义的价值是翻倍的。
### - 核心价值宣言

背景
目的
目标

运用价值主张(Value propositions)来对商业模式(Business models)进行剖析，使用应用程序编程接口(Application Programming Interface API)来对API经济(API Economy)、API开放平台(API Open Platform)以及模块化(Modularization)来对利害关系(Stakeholder)的两方：API面向客户(API Customer)和API使用者(API Consumer)来进行资源合理配置。
智能毕业纪念册基于API开放平台技术的支持来对该款APP进行模块化设计，针对用户的不同使用场景来对该款APP的价值主张来进行补充，并且在可实际操作的商业模式下来对API客户和API使用者进行资源的合理调度。

利害关系图的阐述：

产品设计开发人员（API客户）
系统整合开发人员（API使用者）
终端用户
API/智能云端供货商（API提供者）

上面是四个角色，但是活动的流程是这样子：

API客户也就是产品经理来对智能产品的价值主张进行设计（对应到终端用户的用户需求的任务、痛点及增长点），对智能/平台/模块成本效益进行分析（对应供货商的技术及数据的价值主张）
API使用者也就是后台开发人员对终端用户提出的需求任务、痛点及增长点按照API客户设计的价值主张来系统整合开发APPs，基于API供货商提供的APIs开放平台以及数据库服务，

从APPs-APIs-DataService
将已有成功的APPs或平台，用模块化设计拆出人机交互组件API、云端等等可再组合模块
将已有模块化设计拆出人机交互组件，API、云端等等可再组合设计出符合用户需要的APP或交互产品



### - 用户痛点宣言

传统的电子纪念册有3大需要2大缺陷

1.3大需要：
- 需要下载软件；
- 需要完成所有同学信息的收集
- 需要特定的同学制作班级的毕业纪念册

2. 2大缺陷
- 信息更新不及时，维护成本高
- 欣赏不方便，分享难上加难


竞品分析：
竞品一：微吾H5自助工具制作毕业纪念册
优点：
1. 采用接龙的形式进行信息收集、纪念册制作。将工作量平摊到每个人，每人负责完成自己的纪念模块。
2. 无需下载软件，电脑和手机均可制作，由组织者发起后，将编辑链接以网址或二维码形式分享给其他编辑者即可。
3. 相册可随时随地欣赏和分享，其中，分享方式多样，提供了二维码和链接供分享。
4. 更新方便及时，每个编辑者可以修改自己的相册内容，易于毕业册的更新和维护。

产品设计的原型是封面封底：接龙制作形式：单人信息展示的排版软件是InDesign拾柒拾柒解决了“导出”的问题，可以把文字、图片、视频内容排版成电子书，可以下载成pdf，并且印制成纸质书时光鸡，可以集体编辑，每个人只需要编辑自己的资料和图片就行了，还可以大家互相赠言，还有很邪恶的悄悄话功能，

竞品二：印刷质量还可以有个网站叫时光流影
竞品三、有个产品就叫毕业纪念册微信公众号微影相册
通过市场研究和调查，目前市面上并没有推出一款具体的使用人工智能API与机器学习的智能毕业相册APP，市面上的大多数都是以链接或者是纸质版留存为准，纪念意义大于使用意义，没有后续的使用价值，没有办法通过毕业纪念册来进行产品后续的自我价值，也没有很好起到沟通的效果，与产品设计的初衷又被，并且通过调查，使用线上的程序或者是PPs在移动互联网下会有更多的使用场景和可以辨别的，使用频率和次数会增加并且会使用一定的用户场景研究来使用

制作毕业纪念册的手机软件 VCore 美册，是专门用来做影集的。只要用软件选择手机里的照片，然后选主题模板，滤镜、音乐，就能做出来影集了，越来越轻，就是容易携带，保存在手机QQ、微信、随意一个网址、一个入口，都可以存储我们的友谊。微吾H5自助工具-想你所想，念你所念


“想念”以及slogan“想你所想，念你所念”一句新颖话语道出了用户主要痛点
- 在大学毕业后大家各奔东西，奔赴天涯海角，同学情谊想念却难以联系，联系的频次大幅降低，渴望增强同学之间之间的活力
- 缺乏聚合信息的平台来对相册已经联系信息的时事更新有一定的愿望和需求
- 定位为毕业后专门留存资讯与联系方式的智能毕业纪念册，扭转弱社交关系




|用户痛点|解决方案|
|-------|-------|
|纸质版相册贵留存会受不可控因素遗失或损坏|在云端对用户信息进行永久留存|
|联系渠道狭窄并且极易过时，可复用性程度不大|联系方式查看方便，更新及时，联系快捷|
|固定一段时间后只剩下一纸照片怀念，没有办法对实际联系产生任何帮助，可联系性差且效用性低|v3.1.0|

### - 人工智能概率性与用户痛点


概率性
用户痛点





### - 需求列表与人工智能API加值

需求列表
人工智能API



## 原型

### - 交互及界面设计

设计APP界面布局达到可视性从而使用户产生可记忆性，流畅的APP交互流程设计可使用户提高对产品的使用效率，增强用户对产品的可学习性


### - 信息设计
产品结构图
1 产品功能结构图
2 产品信息结构图


### - 原型文档
全局说明
1 功能权限


1. 功能权限分为登录/未登录两个状态

（1）登录：用户登录状态下可对APP进行所有功能操作

（2）未登录：

-未登录状态可以搜索联系人活动，查看联系人部分信息，私密信息进行隐藏。。。
-但是无法查看信息，签到，打开联系人，查看我的福利，参与评论，打开个人tab等需要个人账号信息的功能

 键盘说明
(1)点击输入手机号码、手机验证时从页面底部弹出数字键盘；
(2)点击输入其它内容时从页面底部弹出字母键盘

页面内交互

页面异常

页面间交互

更多操作


主要业务逻辑流程图
登录注册


订单业务

页面详细功能说明

启动页





### - 口头操作说明

页面逻辑&交互说明：

登录注册
触发条件
登录
(1)页面逻辑内容
(2)页面交互说明
注册
(1)页面逻辑内容
(2)页面交互说明
首页
(1)首页交互说明
 搜索
(1)页面逻辑内容
(2)页面交互说明
推荐
(1)页面逻辑内容
(2)页面交互说明
新品
(1)页面逻辑内容
(2)页面交互说明
众筹
(1)页面逻辑内容
(2)页面交互说明
识物
(1)页面逻辑内容
(2)页面交互说明

分类
(1)页面逻辑内容
(2)页面交互说明





## API 产品使用关键AI或机器学习之API的输出入展示


### - 使用水平

### - 使用比较分析


### - 使用后风险报告


### - 加分项

















### 六、总结








