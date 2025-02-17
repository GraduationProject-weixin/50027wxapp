# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50027wxapp校园二手平台的设计与实现

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 第1章  绪论
## 1.1课题开发背景
网络的普及改变了消费者的消费模式，我们国内大部分的企业从互联网刚出现时就产生了想要通过网络进行商品交易的想法。可是因为在当时人们的思想一时无法转变，而且网上的信誉并不高，网络安全在法律上也不规范，物流问题也无法解决而造成电子商务的实施非常艰难。到2005年开始，网上的电子商务平台开始建立起来，在当时，网络安全、互联网速度、物流等等问题稍有好转，但也是困难重重。大的企业家们看准电子商务的时机纷纷加入进来，使一个个问题快速被击破，电子商务开始大力发展起来。

随着科技的进步，网络给人们带来更大的好处。各种办公软件、app、小程序的出现都方便了人们的生活。特别是手机支付功能的出现，更是帮助人们改变了付款方式。新的改变可以提高生活享受。消费存在在每一个人的每一天的生活中，必不可少。现代人选择消费的方式大多采用实体店。在实体店购买物品可以看到实物，并且不需要等待就可以立即使用，但缺点也是显而易见的。需要时间的付出。现在对于二手物品而言，需要多次对比和选择。在价格方面也没办法对比，实现不了消费的透明。而且由于二手物品的特殊性，在销售和查找时需要大量的时间，实体销售更是满足不了要求。目前使用网上的购物系统的人们非常多，据不完全调查，每年在网上进行消费的人群占80%以上。加入网上商城的商家也逐年增加，有的商家自己开专属于自己的购物平台，还有一部分小商家通过拍视频、直播来进行物品的销售，销售量非常可观，更大一部分人会选择正规的购物网进行消费。现在热门的购物网有淘宝、京东、唯品会等，像去年大热的抖音也开发属于自己的网上购物商城。根据每年的统计得出到目前为止，我国在网上进行消费的用户呈直线上升趋势，网上购物系统已深入日常生活，深得消费者信任。据调查2008年为电子商务发展的高峰时间段，根据各种数据的分析得出，除了是因为人们对互联网的思想认同外，更重要的是物流、信息安全、账号隐私问题的解决。电子商务的发展为新的销售市场打开了新天地，也为消费者提供了更为现代化的消费模式。网上购物系统的出现影响了消费者的消费习惯，目前当人们有消费需求时至少三分之二的人都会考虑在网上进行交易，也都会在网上进行相关商品的了解，网上交易已成为消费者购物的重要途径，同时也为消费者是否要购物起到了决定性的作用。现如今做的好的二手物品交易平台有淘宝的闲鱼，用户可以发布商品，管理订单，可以实现闲置物品的有效利用，非常受用户好评。
## 1.2课题开发目的和意义
在多数的电子商务平台中，大多商品都集中在新手商品。想要专业的针对校园二手商品的购物系统还没有出现，这无疑是一种机会。现如今大学生生活条件提高，很多的学生购买商品但使用率不高，闲置物品越来越多，二手市场需求非常大。使用网上二手交易平台可以比传统交易模式具有更多的优势：

1. 商品更为全面，商品种类更为丰富。如果采用传统购物模式就需要去多家寻找需要的二手商品，这种方式使用户当有特定要求时，就需要浪费大量时间和体力来寻找，而且还不一定有结果，非常不便利；如果采用网上二手交易平台时就可以非常方便的坐在家里就能搜索到自己需要的商品；
1. 商品价格透明，对比方便。网上的二手交易平台所有商品价格一目了然，不需要讨价还价，更加适合当代年轻人；
1. 网上销售商品成本低、范围广，对地域要求低。在网上的销售平台最大的优点就是辐射范围广，可以更快的找到需要的用户，扩宽了销售人群。

综合来说，网上的二手交易平台对于消费者来说可以更好的了解商品、更快的准确的找到需要的商品，并且可以随时了解商品销售状态；对于卖家来说可以扩大销售范围，减少销售成本，非常有意义。
## 1.3课题开发的目标
一个好的系统除了需要满足最基本的安全问题，其次对于操作性、反应速度、用户的操作习惯都需要注意。本系统的开发目标有：

1. 界面简洁、统一，功能按钮明确展示，功能跳转控制在2秒内，信息展示完整、灵活，数据可靠；
1. 首页展示完整商品信息，可以分不同的分类进行展示；
1. 需要设置搜索框，可以方便用户快速寻找商品；
1. 注册用户可以拥有自我修改资料的功能；
1. 设计可以网上评价的功能；
1. 用户可以管理自己的收藏信息以及商品信息；
1. 有疑问用户可以咨询客服；
1. 用户填写的每个数据可以有基本的自检的功能，可以减少出错率；
1. 系统做到最大的可维护性和可扩展性；
1. 系统要做到运行的稳定以及安全。
## 1.4论文结构安排
本论文为基于微信小程序的校园二手平台实现的详细介绍，从绪论、系统分析、系统设计、系统实现、系统测试来进行阐述。在绪论中包含课题开发背景、开发目的、意义以及开发目标；系统分析章节中主要从使用技术、可行性、流程等方面进行分析；在系统设计章节中分为功能结构设计和数据库的设计；系统实现章节中主要是界面的实现；系统测试章节是保证系统稳定和安全的重要手段。同时在绪论前面加有摘要、外文翻译和目录。在论文的最后加入总结、致谢和参考文献。

# `  `第2章 系统分析
## 2.1系统使用相关开发技术分析
### 2.1.1Java语言介绍
Java语言是一种开发动态网页的web技术，相当于就是servle技术类似一样，主要是结合html和css使用，应用在代码编写技术里，java是可以编写所需要的动态技术，通过java编写的动态内容，通过html进行在前台编译展现，从而实现动态效果。实现逻辑就是当用户访问java文件内容时，可以通过html文本的静态数据进行预处理，然后进一步转换成java动态代码，工作原理是非常简单直接的，对于html文本数据只需要进行包装起来就行。通过java生成的文件动态代码会自动进行编译分类，生成servlet类文件，对于服务器来说，会把生成的类文件自动存放在文件目录里。Java语言是一种动态编程语言，最开始是由c++改善而来的。Java语言具有功能强大但使用非常简单的特点。Java语言可以封装，把需要再次使用的代码进行封装，就可以直接移到需要的地方进行直接使用，不需要再次编写，这样可以提高编程人员的开发时间。并且java语言的代码非常健壮和安全，可以在多个平台中移植使用。非常适合新手。Java语言可以编写b/s框架的项目也可以开发c/s框架的项目，支持范围非常广，深入编程人员的喜爱。然后当用户有文件访问需求时，生成的类文件通过html进行页面响应。Java语言主要是在动态项目中进行使用的，它主要有几个显著的特征，首先他可以跨平台使用，然后可以进行代码分离，可以将html界面和后台代码进行单独分离，当有访问请求时，又可以自动执行结果返回，java运行必须结合服务器才可以，通过服务器进行代码调取，既可以编写html代码，也可以直接编写java所需要的代码，所以说采用java编写的代码性能更加有优势，而且服务器更方便调取数据，而且是直接编译好的数据文件，直接就可以通过html在浏览器进行展示，方便用户的查看。
### 2.1.2myeclipse介绍
myeclipse是一个具有完整的编码和调试的集成环境，丰富了java的所有开发需求，他是属于eclipse和idea的一个功能扩展，属于企业级开发平台。通过myeclipse可以进行java的开发和测试等，对各方面服务数据进行了有效整合，使编程技术更加的方便快捷，而且支持各种开发技术。myeclipse集成了java的所有框架，而且额外支持最新插件，有很多吸引人的特点，最突出的就是支持更多的java框架。对于使用人员来说，对于环境的配置部署和代码的调试更加的方便。myeclipse采用了最新的编辑器，可以对代码进行更好的支持和标记，而且还支持图形在线编辑，增加了程序服务器，支持更多的应用程序，通过myeclipse编译的代码文件可以直接生成软件包，然后通过tomcat服务器进行部署，然后进行在线浏览。
### 2.1.3 b/s架构
b/s架构主要是指通过internet进行数据访问的web服务器，主要是通过浏览器进行数据访问，通过web进行访问的服务器主要有tomcat和apache，通过b/s架构的程序可以可以为用户提供各种服务，比如wwww.FTP等各种网络在线服务，b/s架构主要是借助web服务器进行运行，工作原理就是当有客户通过网上浏览器进行数据访问时，服务器会自动把数据进行反馈，通过http协议进行信息交互，从而进行信息展示，而且可以直接通过web服务器进行脚本运行和代码编译，最主要的特征就是通过html文本格式进行编译。采用b/s架构开发的程序，有很大的兼容性，用户只需要通过最直接简单的方法，直接通过浏览器网址模式的搜索，就可以获取自己需要的各种资料信息，不需要对技术细节进行详细的研究了解，更加的简单直观。b/s框架为利用浏览器进行运行的框架，使用b/s框架设计的项目可以省掉固定客户端，直接把项目放到服务器中。这样可以使更多的用户使用，不需要固定的客户端。在项目的升级和扩展上也只有修改服务器中的项目就可以。B/s框架设计的项目为网页项目，用户凭借账号和密码进行项目的操作，所以本系统更适合采用b/s框架。b/s架构模式主要是采用现有的internet技术进行的，对于传统的c/s架构来说是一个很大的变革，传统的c/s模式主要是指单机系统采用客户端形式运行，数据全部存储在客户端，最大的缺点就是使用范围受限，只能局域网之间访问，而且用户必须安装必须的客户端才能使用，而b/s最大的不同就是把数据存储于网络服务器之中，可以实现实时共享，简化了系统的开发和后期维护，电脑只需要安装浏览器就可以对数据进行有效的访问和进行有效的数据交互。而且还可以直接把数据存储到网上，可以实现不同的的用户同时访问，实时交互，而且售后维护方便，只需要升级服务器就可以了，减少了客户的使用难度。
## 2.2系统需求分析
二手交易系统已成为消费者不可缺少的生活辅助工具，二手交易系统也是二手市场长远发展不可缺少的销售平台。从消费者角度来讲，网上二手交易系统解决了购物需要出门的问题，解决了地域、时间的限制，可以随时购物；从卖家角度来讲，网上二手交易系统解决了销售商品需要大量宣传的要求，解决了商品销售范围窄、时间要求高的问题，同时可以为卖家提供更为广泛的宣传途径。所以网上二手交易系统是非常需要的必须品。本系统是针对校园的二手交易系统，二手物品近几年成为校园生活中最多的资源，如果可以把二手物品换成其它需要的商品或者变现将会节省成本。
## 2.3系统可行性分析
系统的可行性分析主要从技术方面、经济方面和系统的操作性方面进行分析，对系统可行性进行分析是保证系统开发是否有价值的重要保障，只有通过可行性分析的系统才可以保证其生命性。
### 2.3.1技术可行性分析
开发系统的同时，会尽量保证系统的简单易操作性，这对于一个网站来说是非常重要的，因为开发网站的受众群体是普通消费者，他们大多是没有任何专业技术的，必须可以简单易操作才能更好的吸引用户，而且开发的方向还有有一定的针对性和实用性。目前大多的公司大多都是跟风操作，没有更直接的针对性消费群体，所以开发投资巨大，却没有更好的回报，所以开发本系统一定不能跟风操作，要跟市场上的同类系统具有一定的差异性，这样才能在市场竞争中占得先机。
### 2.3.2经济可行性分析
开发本系统只需要购置最基本的网络硬件设备和相应的编程软件，就可以具备本系统的开发，而且后期的售后维护也有专业的研发人员进行售后支持和维护。投资金额相对很小，而回报率非常高，可以很好实现投资效益。本系统在开发时所使用的语言、技术、软件都为免费的，不需要经济的付出。本系统在实现在需要电脑，电脑已成为家庭的必备品，不需要额外采购。本系统在后期的维护中也只需要一人就可以完成。
### 2.3.3 操作可行性分析
本系统采用b/s架构模式，用户可以直接通过微信访问的模式进行，非常的简单直接，而且界面简单明了，可以一目了然的查看系统的所有功能和操作介绍，而且还有各种文字介绍和指引，不管你是不是专业的技术人员，都可以轻松使用。采用了大量的提示词，并且在设计中采用了大众的操作习惯。所有的功能和操作流程都是所见即所得，非常简单。界面设计也非常友好，不管是什么文化层次的用户都可以顺利的使用本系统，不需要进行专业的学习
## 2.4系统开发背景的问题分析
根据目前的二手交易网的情况分析，本人认为缺少沟通。不是用户与用户之间缺少沟通，而是平台与用户之间缺少沟通。虽然一些平台上有沟通的途径，但这些途径要不需要长时间排队，要不处理人员专业性不够强，解决不了用户的真实问题。本系统加入在线留言的功能。所有用户在平台上都可以看到用户的问题，也可以看到平台管理人员的回复信息。用户可以先自行解决自己的问题，如果不能解决问题也可以自己留言，留言后，平台管理员可以在后台查看到用户的问题，可以及时的进行回复。所有的过程都在所有用户面前进行，透明性更强，对平台可以起到监督作用。
## 2.5系统设计问题分析
在系统设计中需要考虑全部的问题并想出解决办法才可以保证系统可以顺利的进行下去。不会半途而废，造成工作白做。通过研究相关资料和相关的网站，本人认为本系统在开发中会出现的问题有：

1. 因为使用本系统的人员不可能都是经过专业学习的人员，所以在设计时要考虑到不同文化层次的操作问题；
1. 对使用本系统需要的条件，想要使用本系统需要电脑，但考虑到现在电脑已成为家庭必备品，而且价格已非常贫民。所以本系统的使用条件并不严格；
1. 本次设计的系统不仅仅是面对消费者，更是面对商家、平台管理员，所以在设计时也要充分考虑到商家、平台管理员的需求。通过研究发现，现在商家也一直在寻求新的销售途径，所以本系统在本问题上可以进行；
1. 由于本系统涉及到网上交易的问题，所以安全性非常重要，要保证用户的财产安全，更要保证商家的财产安全。本系统采用审核的方式进行用户的甄别，对于资金的保护也采用了一定的安全手段。

## 2.6业务流程分析
根据用户购买商品和使用二手交易系统的习惯，本系统的流程设计为，用户先以游客的身份点开本系统，在系统的前台可以看到商品信息，商品可以按照不同类别进行排名；当用户点击喜欢的商品后可以看到商品的详情，包括价格、新旧程度等；用户想要评价或者加收藏时就需要先进行登录，也可以先进行注册，用户可以管理商品和商品配送。管理员的流程为先在登录界面进行登录，然后进行商品信息、用户信息、密码信息等的管理。本系统的业务流程图如下图2.1所示：

![](/md/blog.001.png)

图2.1系统业务流程图

登录功能是验证身份的手段，登录的流程也是数据验证的流程，用户登录流程如下图2.2所示：

![](/md/blog.002.png)

图2.2用户登录流程图

用户最基本的功能就是商品管理与浏览、发布，当用户选择喜欢的商品时可以进行加入收藏，加入收藏的流程如下图2.3所示：

![](/md/blog.003.png)

图2.3加入收藏流程图
### 2.4.1数据流程分析
对数据的来源、经过、处理到去处的分析可以称为数据流程分析，本系统中主要的数据为商品信息、收藏信息、评价信息、用户信息。从这些信息的管理员和用户的关系进行分析，关系着本系统的数据流程。本系统的数据流程图如下图2.4所示：

![](/md/blog.004.png)　　　　　　　　　　　　图2.4系统总数据流程图
# 第3章 总体设计
## 3.1系统模块总体设计
一般对系统的模块总体设计采用层次图来设计，层次图属于一种树形图，也就是利用一层一层的图形来表达不同的关系。可以由一些特定的线条和矩形来表达不同的意思。下一层为上一层的子集，可以根据实际情况进行不同的分割，一般都为三层结构。

本系统分为用户和管理员两个角色，用户的操作主要为微信端，管理员的操作为服务端。用户在微信端可以根据不同的分类浏览商品，可以把商品加入收藏、进行评价，管理自己的商品、商品配送以及个人信息等；管理员可以管理商品信息、用户信息和评价信息等。用户和管理员的功能相互串连形成完整的基于微信小程序的校园二手平台。

根据用户和管理员的功能可以分为微信端和服务端两个界面，在微信端中主要的功能为：

1. 商品展示功能，根据不同类别来进行商品的展示；
1. 商品查询功能，用户可以根据不同的字段来进行特定商品的搜索，本功能是一个网站最基本的功能；
1. 收藏功能，在商品的详情里可以把商品加入收藏，也可以进行直接购买；
1. 用户管理功能，包括注册用户和对用户资料的信息进行管理；
1. 商品购买功能，管理自己购买的商品；
1. 商品配送功能，可以进行商品的配送；
1. 商品评价功能，管理自己的评价；
1. 客服功能，可以进行交流和提问；
1. 商品资讯功能，可以浏览商品的资讯信息。

本系统的服务端功能包括：

1. 二手商品信息管理功能，对商品进行审核、删除、编辑；
1. 用户管理功能，对注册用户信息进行审核、管理；
1. 商品评价管理功能，可以回复用户评价；
1. 商品资讯信息管理，可以发布商品资讯；
1. 商品分类信息管理，可以发布分类和管理分类；
1. 商品购买功能，查看用户的购买信息。

本系统的功能模块结构图如下图3.1所示：

![](/md/blog.005.png)图3.1系统功能模块结构图
## 3.2数据库设计
本系统采用mysql数据库做为数据的存储工具，想要系统中的数据安全、稳定就需要良好的数据库设计。为了能够准确的设计数据库，在数据分析时不单从数据的增、改、查、删中分析，还要从数据的隐性要求中进行分析。
### 3.2.1数据ER图设计
`	`本系统的实体包括用户、商品、收藏、商品分类、评价。系统的ER关系图如下图3.3所示：

![](/md/blog.006.png)

图3.3系统ER关系图

1. 用户信息包括编号、密码、账号、性别等，用户信息ER图如下图3.4所示：

![](/md/blog.007.png)

图3.4用户信息ER图

1. 管理员信息包括账户、密码、权限三个，管理员ER图如下图3.5所示：

![](/md/blog.008.png)

图3.5管理员信息ER图

1. 收藏信息包括商品编号、用户编号、用户名和收藏时间，收藏信息ER图如下图3.6所示：

![](/md/blog.009.png)

图3.6收藏信息ER图

1. 商品信息包括编号、名称、价格等，商品信息ER图如下图3.7所示：

![](/md/blog.010.png)

图3.6商品信息ER图
### 3.2.2数据库表设计
数据库表包括商品信息表、用户信息表、管理员信息表、评价信息表、分类信息表等，本系统的数据库表如下表3.1－3.13所示：

表3.1 chat

![](/md/blog.011.png)

表3.2 config

![](/md/blog.012.png)








表3.3 dingdantuikuan

![](/md/blog.013.png)

表3.4 discussmaijia

![](/md/blog.014.png)


表3.5 discussshangpinxinxi

![](/md/blog.015.png)

表3.6 forum

![](/md/blog.016.png)

表3.7 maijia

![](/md/blog.017.png)

表3.8 messages

![](/md/blog.018.png)

表3.9 news

![](/md/blog.019.png)

表3.10 shangpindingdan

![](/md/blog.020.png)

表3.11 shangpinleixing

![](/md/blog.021.png)

表3.12 shangpinxinxi

![](/md/blog.022.png)

表3.13 storeup

![](/md/blog.023.png)

# 第4章  系统详细设计与实现
## 4.1系统运行平台设置
想要本系统运行，需要微信端和客户端两个环境的支持。本系统的客户端环境为电脑一台，软件环境为windows操作系统和myeclipse软件以及mysql数据库。微信端为手机一台和微信开发者工具。
## 4.2系统首页界面的设计实现
系统的首页可以看到标题、功能导航栏、搜索框、商品信息，在首页的下方可以看到二手商品、商品资讯、我的功能按钮。系统首页的功能设计效果如下图4.1所示：

![](/md/blog.024.png)

图4.1系统首页界面的运行效果图
## 4.3用户注册功能的设计实现
为了保证系统的安全性和满足用户的交易要求，用户需要先进行注册才可以进行操作，用户注册时需要注意表单信息的填写，在表单信息填写完成后，系统可以实现对表单信息进行自我检测，当检测为正确时，可以实现注册成功，当有信息检测为错误时会提示重新填写。用户注册成功后系统会把填写的表单保存到数据库中。用户注册的实现界面如下图4.2所示：

![](/md/blog.025.png)

图4.2用户注册功能的界面实现
## 4.4用户登录功能的设计实现
用户注册完成后，可以点击登录功能进行登录，在登录时会进行账号和密码的数据验证，账号和密码验证正确则登录成功，账号和密码验证错误则登录失败，需要重新登录。用户登录功能的实现界面如下图4.3所示：

![](/md/blog.026.png)

图4.3用户登录功能实现界面效果
## 4.5用户发布商品功能的设计实现
用户登录后可以对需要销售的商品进行发布，商品需要填写简单介绍和图片、价格等信息。用户发布商品功能的实现界面如下图4.4所示：

![](/md/blog.027.png)

图4.4用户发布商品信息实现界面
## 4.6商品信息展示功能的设计实现
商品信息为基本的功能，商品信息可以分为不同的分类进行展示，对于商品信息的展示以图片展示为主，可以使用户更加的一目了然，商品信息展示的实现界面如下图4.5所示：

![](/md/blog.028.png)

图4.5商品信息展示实现运行效果界面
## 4.7商品收藏功能的设计实现
在商品详情功能里，用户可以把商品进行收藏，收藏时会提示“是否收藏”。商品收藏功能的设计界面如下图4.6所示：

![](/md/blog.029.png)

图4.6商品收藏功能的运行效果界面
## 4.8商品购买功能的设计实现
用户购买商品后可以查询购买信息，可以进行付款。商品购买管理功能的界面实现如下图4.7所示：

![](/md/blog.030.png)

图4.7商品购买功能的运行效果界面
## 4.9商品评价功能模块的设计实现
本功能的设计可以帮助用户评价商品，在线评价功能的实现界面如下图4.8所示：

![](/md/blog.031.png)

图4.8用户在线评价功能运行效果界面
## 4.10客服功能的界面实现
用户可以咨询客服，实现界面如下图4.9所示：

![](/md/blog.032.png)

图4.9客服功能的实现界面
## 4.11管理员用户管理功能的设计实现
本功能为管理员所负责的功能，主要是对注册用户的信息进行审核管理，可以对恶性用户进行删除账号，使其不能再进行使用本系统。用户管理功能实现界面如下图4.10所示：

![](/md/blog.033.png)

图4.10用户管理功能的实现界面效果
## 4.12管理员二手商品管理功能的设计实现
管理员在收到用户发布的商品时可以进行审核和删除，管理员管理二手商品信息的实现界面如下图4.11所示：

![](/md/blog.034.png)

图4.11管理员二手商品信息管理功能的实现界面
## 4.13商品资讯管理功能的界面设计实现
本功能可以实现发布商品资讯的目的。输入标题和内容就可以实现商品资讯的更换。商品资讯管理功能的实现界面如下图4.12所示：

![](/md/blog.035.png)

图4.12商品资讯管理功能实现界面

# 










