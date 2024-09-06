# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0021springboot蜗牛兼职网的设计与实现

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV16ia6epENY?p=22)


# 第1章 绪论
## 1.1背景及意义
随着社会的快速发展，计算机的影响是全面且深入的。人们生活水平的不断提高，日常生活中人们对蜗牛兼职网方面的要求也在不断提高，需要兼职工作的人数更是不断增加，使得蜗牛兼职网的开发成为必需而且紧迫的事情。蜗牛兼职网主要是借助计算机，通过对蜗牛兼职网所需的信息管理，增加用户的选择，同时也方便对广大蜗牛兼职网的及时查询、修改以及对蜗牛兼职网的及时了解。蜗牛兼职网对用户带来了更多的便利，该系统通过和数据库管理系统软件协作来满足用户和企业的需求。计算机技术在现代管理中的应用，使计算机成为人们应用现代技术的重要工具。能够有效的解决获取信息便捷化、全面化的问题，提高效率。

本蜗牛兼职网主要牵扯到程序，数据库与计算机技术等。覆盖知识面大，可以大大的提高系统人员工作效率。
## 1.2 国内外研究概况
随着国内经济形势的不断发展，中国互联网进入了一个难得的高峰发展时期，这使得中外资本家纷纷转向互联网市场。然而，许多管理领域的不合理结构，人员不足以及管理需求的增加使得更多的人具备了互联网管理的意识。

在当今高度发达的信息中，信息管理改革已成为一种更加广泛和全面的趋势。“蜗牛兼职网”是基于Mysql数据库，在springboot框架程序设计的基础上实现的。为确保中国经济的持续发展，信息时代日益更新，更是蓬勃发展。同时，随着信息社会的快速发展，蜗牛兼职网面临着越来越多的信息，因此很难获得他们对高效信息的需求，如何使用方便快捷的方式使查询者在广阔的蜗牛兼职网信息中查询，存储，管理和共享信息方面有效，对我们的学习，工作和生活具有重要的现实意义。因此，国内外学术界对此进行了深入而广泛的研究，一个新的研究领域——蜗牛兼职网诞生了。
## 1.3 研究的内容
目前许多人仍将传统的纸质工具作为信息管理的主要工具，而网络技术的应用只是起到辅助作用。在对网络工具的认知程度上，较为传统的office软件等仍是人们使用的主要工具，而相对全面且专业的蜗牛兼职网的信息管理软件仍没有得到大多数人的了解或认可。本选题宗旨在通过标签分类管理等方式，实现管理员：首页、个人中心、用户管理、企业管理、兼职信息管理、职位申请管理、留言板管理、系统管理，用户：首页、个人中心、职位申请管理，前台首页：首页、兼职信息、留言反馈、个人中心、后台管理，企业：首页、个人中心、兼职信息管理、职位申请管理等功能。从而达到对蜗牛兼职网信息的高效管理。 

2. # 相关技术
### 2.1  B/S架构 
B/S结构的特点也非常多，例如在很多浏览器中都可以做出信号请求。并且可以适当的减轻用户的工作量，通过对客户端安装或者是配置少量的运行软件就能够逐步减少用户的工作量，这些功能的操作主要是由服务器来进行控制的，由于该软件的技术不断成熟，最主要的特点就是与浏览器相互配合为软件开发带来了极大的便利，不仅能够减少开发成本，还能够不断加强系统的软件功能，层层相互独立和展现层是该B/S结构完成相互连接的主要特性。
### 2.2  Java技术介绍 
Java语言擅长开发互联网类应用和企业级应用，现在已经相当的成熟，而且也是目前使用最多的编程语言之一。Java语言具有很好的面向对象性，可以符合人的思维模式进行设计，封装是将对象的属性和方法尽可能地隐藏起来，使得外界并不知道是如何实现的，外界能通过接口进行访问，继承是指每个类都会有一个父类，所有的子类都有父类的方法，可以进行继承，但是只有final修饰的类不能被继承，通过继承可以使得代码得到重新利用，能够提高软件的开发效率，也是多态的前提。

Java就像C语言、C#语言等，也是一种程序开发语言，而它的特点就是面向对象。作为一种程序开发与设计的语言，它有很多特性，主要特性就是面向对象、夸平台以及可以分布式运行。Java语言项目不但安全性高、稳定性强，而且可以并发运行。

为了提高开发的速度及效率，必须做到代码的重复使用和简化程序的复杂度，要达到上述的要求java语言通过封装、继承与多态等方式实现，这样可以很大程度上达到信息的封装，提高代码复用率，减少冗余度，提高效率。它使得以往程序中大量存在的内存泄漏的问题得到了较好的缓解。所谓的内存泄漏就是程序向操作系统申请了一块存储空间，比如定义了一个变量，但是由于某种原因，这个变量一直没有使用，但是仍然占用着系统的内存空间，可能一两个这样的变量对程序和操作系统造不成什么大的影响，但是试想如果这样的变量定义的多了系统的内存空间就会一步步减少，从而造成机器的性能降低甚至宕机。但是在Java中有垃圾回收机制的存在，这种机制极大地避免了内存泄漏的出现，在Java虚拟机中，垃圾回收机制会对长时间没有引用变量指向的对象实施垃圾回收，简单的说就是将这个对象销毁，以避免内存泄漏的情况出现。
### ` `2.3 mysql数据库介绍 
MySQL是一款Relational Database Management System，直译过来的意思就是关系型数据库管理系统，MySQL有着它独特的特点，这些特点使他成为目前最流行的RDBMS之一，MySQL想比与其他数据库如ORACLE、DB2等，它属于一款体积小、速度快的数据库，重点是它符合本次毕业设计的真实租赁环境，拥有成本低，开发源码这些特点，这也是选择它的主要原因。

本系统使用了MySQL数据库，建立了多张数据库表来存储租赁以及汽车租赁平台相关数据。系统中主要应用查询（select），修改（update），删除（delete）以及增加（insert）等语句来实现系统功能。
## 2.4 Spring Boot框架
Spring Boot是Pivotal团队的一个新框架，旨在简化新Spring应用程序的初始设置和开发。该框架使用特定的配置方法，无需开发人员定义样板配置。通过这种方式，Spring Boot旨在成为蓬勃发展的快速应用程序开发领域的领导者。
Spring Boot特点：
1、创建一个单独的Spring应用程序；
2、嵌入式Tomcat，无需部署WAR文件；
3、简化Maven配置；
4、自动配置Spring；
5、提供生产就绪功能，如指标，健康检查和外部配置；
6、绝对没有代码生成和XML的配置要求；
`  `安装步骤：
`   `最基本的是，Spring Boot是一个可以被任何项目的构建系统使用的库集合。 为简单起见，该框架还提供了一个命令行界面，可用于运行和测试Boot应用程序。 可以从Spring存储库手动下载和安装框架的已发布版本，包括集成的CLI（命令行界面）。 更简单的方法是使用Groovy enVironment Manager（GVM），它负责处理Boot版本的安装和管理。 可以从GVM命令行GVM install springboot安装Boot及其CLI。 在OS X上安装Boot时可以使用Homebrew包管理器。要完成安装，首先使用brew tap pivotal / tap切换到pivotal存储库，然后执行brew install springboot命令。

# 第3章 系统分析
## 3.1 需求分析
蜗牛兼职网主要是为了提高工作人员的工作效率和更方便快捷的满足用户和企业，更好存储所有数据信息及快速方便的检索功能，对系统的各个模块是通过许多今天的发达系统做出合理的分析来确定考虑用户和企业的可操作性，遵循开发的系统优化的原则，经过全面的调查和研究。

系统所要实现的功能分析，对于现在网络方便的管理，系统要实现用户可以直接在平台上进行查看所有数据信息，根据需求可以进行在线添加，删除或修改蜗牛兼职网信息，这样既能节省时间，不用再像传统的方式耽误时间，真的很难去满足用户和企业的各种需求。所以蜗牛兼职网的开发不仅仅是能满足用户和企业的需求，还能提高管理员的工作效率，减少原有不必要的工作量。
## 3.2 系统可行性分析
### 3.2.1技术可行性：技术背景
本企业网站在Windows操作系统中进行开发，并且目前PC机的性能已经可以胜任普通网站的web服务器。系统开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，系统使用springboot框架开发工具，使用比较成熟的Mysql数据库进行对系统前台及后台的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得网站运行更具有稳定性和安全性，从而完成实现网站的开发。

硬件可行性分析

系统管理及信息分析的设计对于所使用的计算机没有什么硬性的要求，计算机只要可以正常的使用进行代码的编写及页面设计就可行，主要是对于服务器有些要求，对于平台搭建完成要上传的服务器是有一定的要求的，服务器必须选择安全性比较高的，然后就是在打开网站必须顺畅，不能停顿太长时间；性价比高；安全性高。

因此，我们从这个方面进行了可行性研究，可以看出系统的开发没有问题。
### 3.2.2经济可行性
在蜗牛兼职网开发之前所做的市场调研及其他的相关的管理系统，都是没有任何费用的，都是通过开发者自己的努力，所有的工作的都是自己亲力亲为，在碰到自己比较难以解决的问题，大多是通过同学和指导老师的帮助进行相关信息的解决，所以对于蜗牛兼职网的开发在经济上是完全可行的，没有任何费用支出的。

使用比较成熟的技术，系统是基于Java技术的开发，采用Mysql数据库。所以系统在开发人力、财力要求不高，具有经济可行性。
### 3.2.3操作可行性： 
可操作性主要是对蜗牛兼职网设计完成后，用户的使用体验度，以及管理员可以通过系统随时管理相关的数据信息，并且对于管理员、用户、企业三个权限角色，都可以简单明了的进入到自己的系统界面，通过界面导航菜单可以简单明了地操作功能模块，方便蜗牛兼职网的操作需求和管理员管理数据信息，对于系统的操作，不需要专业人员都可以直接进行功能模块的操作管理，所以在系统的可操作性是完全可以的。本系统的操作使用的也是界面窗口进行登录，所以操作人员只要会简单的电脑操作就完全可以的。
## 3.3 项目设计目标与原则
1、关于蜗牛兼职网的基本要求

（1）功能要求：可以管理首页、个人中心、用户管理、企业管理、兼职信息管理、职位申请管理、留言板管理、系统管理等功能模块。

（2）性能：在不同操作系统上均能无差错实现在不同类型的用户和企业登入相应界面后能不出差错、方便地进行预期操作。

（3）安全与保密要求：用户和企业都必须通过身份验证才能进入系统，并且用户的权限也需要根据用户的类型进行限定。

（4）环境要求：支持多种平台，可在Windows系列、Vista系统等多种操作系统下使用。

2、开发目标

蜗牛兼职网的主要开发目标如下：

（1）实现管理系统信息关系的系统化、规范化和自动化；

（2）减少维护人员的工作量以及实现用户对信息的控制和管理。

（3）方便查询信息及管理信息等；

（4）通过网络操作，改善处理问题的效率，提高操作人员利用率；

（5）考虑到用户多样性特点，要求界面简单，操作简便。

3、设计原则

本蜗牛兼职网采用Java技术，Mysql数据库开发，充分保证了系统稳定性、完整性。 

蜗牛兼职网的设计与实现的设计思想如下： 

1. 操作简单方便、系统界面安全良好、简单明了的页面布局、方便查询相关信息。

2、即时可见：对蜗牛兼职网信息的处理将立马在对应地点可以查询到，从而实现“即时发布、即时见效”的系统功能。 

## 3.4系统流程分析
### 3.4.1操作流程
系统登录流程图，如图所示：![](/md/blog.001.png)

图3-1登录流程图
### 3.4.2添加信息流程
添加信息流程图，如图所示：

![](/md/blog.002.png) 

图3-2添加信息流程图
### 3.4.3删除信息流程
删除信息流程图，如图所示：

![](/md/blog.003.png)

图3-3删除信息流程图



# 第4章 系统设计
## 4.1 系统体系结构
蜗牛兼职网的结构图4-1所示：

网

络

管理员

服务器和程序

企业

用户

![](/md/blog.004.png)

图4-1 系统结构

登录系统结构图，如图4-2所示：

蜗牛兼职网登录界面

用户登录

密码正确

管理员界面

企业界面

用户界面

![](/md/blog.005.png)

图4-2 登录结构图

蜗牛兼职网结构图，如图4-3所示。

![](/md/blog.006.png)

图4-3 蜗牛兼职网结构图
## 4.2开发流程设计
系统流程的分析是通过调查系统所涉及问题的识别、可行性、可操作性、系统分析处理能力等具体环节来调节、整理系统的设计方案以确保系统能达到理想的状态。这些操作都要从注册、登录处着眼进行一系列的流程测试保证数据库的完整，从而把控系统所涉及信息管理的安全、保证信息输入、输出正常转换。然后，通过实际操作完成流程图的绘制工作。

蜗牛兼职网的开发对管理模块和系统使用的数据库进行分析，编写代码，系统测试，如图4-4所示。

![](/md/blog.007.png)

图4-4开发系统流程图
## 4.3 数据库设计原则
学习编程，我们都知道数据库设计是基于需要设计的系统功能，我们需要建立一个数据库关系模型，用于存储数据信息，这样当我们在程序中时，就没有必要为程序页面添加数据，从而提高系统的效率。数据库存储了很多信息，可以说是信息管理系统的核心和基础，数据库还提供了添加、删除、修改和检查，使系统能够快速找到自己想要的信息，而不是在程序代码中找到。数据库中信息表的每个部分根据一定的关系精确地组合，排列和组合成数据表。 

通过蜗牛兼职网的功能进行规划分成几个实体信息，实体信息将通过ER图进行说明，本系统的主要实体图如下：

用户信息属性图如图4-5所示。

![](/md/blog.008.png)

图4-5 用户信息实体属性图

企业信息实体属性图如图4-6所示。

![](/md/blog.009.png)

`      `图4-6企业信息属性图

兼职信息属性图如图4-7所示。

![](/md/blog.010.png)

`     `图4-7兼职信息实体属性图

留言板信息实体属性图如图4-8所示。

![](/md/blog.011.png)

`   `图4-8留言板信息实体属性图
## 4.4 数据表
将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

表名：jianzhixinxi

功能：兼职信息表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhiweimingcheng|bigint|100|职位名称|||
|tupian|bigint|100|图片|||
|zhaopinrenshu|bigint|100|招聘人数|||
|xinzidaiyu|bigint||薪资待遇|||
|zhiweijianjie|bigint|100|职位简介|||
|gongzuoneirong|bigint|100|工作内容|||
|faburiqi|bigint|100|发布日期|||
|qiyehao|bigint|100|企业号|||
|qiyemingcheng|bigint||企业名称|||
|lianxiren|bigint|100|联系人|||
|lianxifangshi|bigint|100|联系方式|||
|dizhi|bigint|100|地址|||


表名：qiye

功能：企业表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|varchar|100|创建时间|||
|qiyehao|varchar|100|企业号|||
|mima|varchar|100|密码|||
|qiyemingcheng|timestamp||企业名称||CURRENT\_TIMESTAMP|
|tupian|varchar|100|图片|||
|lianxiren|varchar|100|联系人|||
|lianxifangshi|varchar|100|联系方式|||
|youxiang|varchar|100|邮箱|||
|dizhi|varchar|100|地址|||


表名：yonghu

功能：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuming|varchar|200|用户名|||
|mima|bigint||密码|||
|yonghuxingming|bigint||用户姓名|||
|touxiang|varchar|200|头像|||
|xingbie|varchar|200|性别|||
|shoujihaoma|int||手机号码|||
|youxiang|float||邮箱|||


表名：zhiweishenqing

功能：职位申请表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|`
   `主键
||
|addtime|bigint||创建时间|||
|zhiweimingcheng|varchar|100|职位名称|||
|zhaopinrenshu|varchar|200|招聘人数|||
|xinzidaiyu|timestamp||薪资待遇||CURRENT\_TIMESTAMP|
|zhiweijianjie|timestamp||职位简介||CURRENT\_TIMESTAMP|
|gongzuoneirong|varchar|200|工作内容|||
|qiyehao|varchar|200|企业号|||
|qiyemingcheng|varchar|200|企业名称|||
|shenqingriqi|varchar|200|申请日期|||
|jianli|varchar|200|简历|||
|yonghuming|varchar|200|用户名|||
|yonghuxingming|varchar|200|用户姓名|||
|shoujihaoma|varchar|200|手机号码|||
|sfsh|varchar|200|是否审核|||
|shhf|varchar|200|审核回复|||






# 第5章 系统详细设计

## 5.1管理员功能模块
管理员登录，通过填写输入用户名、密码、角色进行登录，如图5-1所示。

![](/md/blog.012.png)

图5-1管理员登录界面图

管理员登录进入蜗牛兼职网可以查看首页、个人中心、用户管理、企业管理、兼职信息管理、职位申请管理、留言板管理、系统管理等信息。

用户管理，在用户管理页面中可以通过填写用户名、密码、用户姓名、头像、性别、手机号码、邮箱等信息进行详情、修改、删除等操作，如图5-2所示。还可以根据需要对企业管理进行详情、修改或删除等详细操作，如图5-3所示。

![](/md/blog.013.png)

图5-2用户管理界面图

![](/md/blog.014.png)

图5-3企业管理界面图

兼职信息管理，在兼职信息管理页面中可以查看职位名称、图片、招聘人数、薪资待遇、职位简介、工作内容、发布日期、企业号、企业名称、联系人、联系方式等信息，并可根据需要对兼职信息管理进行详情、修改或删除等操作，如图5-4所示。

![](/md/blog.015.png)

图5-4兼职信息管理界面图

职位申请管理，在职位申请管理页面中可以查看职位名称、招聘人数、薪资待遇、职位简介、工作内容、企业号、企业名称、申请日期、简历、用户名、用户姓名、手机号码、审核回复、审核状态等信息，并可根据需要对职位申请管理进行详情、修改或删除等详细操作，如图5-5所示。

![](/md/blog.016.png)

图5-5职位申请管理界面图

留言板管理，在留言板管理页面中可以查看用户名、留言内容、回复内容等内容，并且根据需要对留言板管理进行详情、回复、修改或删除等详细操作，如图5-6所示。

![](/md/blog.017.png)

图5-6留言板管理界面图

轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作，如图5-7所示。

![](/md/blog.018.png)

图5-7轮播图管理界面图



## 5.2用户功能模块
用户登录，通过填写用户名、密码、角色进行登录，如图5-8所示。

用户登录进入蜗牛兼职网可以查看首页、个人中心、职位申请管理等功能。如图5-9所示

![](/md/blog.019.png)

图5-8用户登录界面图


![](/md/blog.020.png)

图5-9用户功能界面图



职位申请管理，在职位申请管理页面中可以查看职位名称、招聘人数、薪资待遇、职位简介、工作内容、企业号、企业名称、申请日期、简历、用户名、用户姓名、手机号码、审核回复、审核状态等信息内容，并且根据需要对职位申请管理进行详情、修改或删除等其他详细操作，如图5-10所示。

![](/md/blog.021.png)

图5-10职位申请管理界面图



## 5.3前台首页功能模块
蜗牛兼职网，在蜗牛兼职网可以查看首页、兼职信息、留言反馈、个人中心、后台管理等内容，如图5-11所示。

![](/md/blog.022.png)

图5-11前台首页界面图



用户登录，通过填写用户名、密码进行登录，如图5-12所示。


![](/md/blog.023.png)

图5-12用户登录界面图


兼职信息，在兼职信息页面可以填写职位名称、图片、招聘人数、薪资待遇、职位简介、工作内容、发布日期、企业号、企业名称、联系人、联系方式等信息进行点击下载，如图5-13所示。 

![](/md/blog.024.png)

图5-13兼职信息界面图

留言反馈，在留言反馈页面可以填写留言内容等进行立即提交或重置等操作，如图5-14所示。

![](/md/blog.025.png)

图5-14留言反馈界面图

## 5.4企业功能模块
企业登录进入蜗牛兼职网可以查看首页、个人中心、兼职信息管理、职位申请管理等内容。企业登录，通过填写用户名、密码、角色进行登录，如图5-15所示。

![](/md/blog.026.png)

图5-15企业登录界面图

个人信息，在个人信息页面中通过填写企业号、企业名称、图片、联系人、联系方式、邮箱、地址等信息还可以根据需要对个人信息进行修改，如图5-16所示。

![](/md/blog.027.png)

图5-16个人信息界面图


兼职信息管理，在兼职信息管理页面中通过填写职位名称、图片、招聘人数、薪资待遇、职位简介、工作内容、发布日期、企业号、企业名称、联系人、联系方式等内容进行详情、修改、删除等操作，如图5-17所示。

![](/md/blog.028.png)

图5-17兼职信息管理界面图



职位申请管理，在职位申请管理页面中通过填写职位名称、招聘人数、薪资待遇、职位简介、工作内容、企业号、企业名称、申请日期、简历、用户名、用户姓名、手机号码、审核回复、审核状态等内容进行详情、修改等操作，如图5-18所示。

![](/md/blog.029.png)

图5-18职位申请管理界面图









# 










