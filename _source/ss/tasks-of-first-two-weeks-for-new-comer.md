# 新人1-2周学习清单

## 1、前言：

#### 发展方向（需要一直要坚持做的，算是前言）：

* 1、融入团队；
* 2、养成理解产品的意识（招商平台、优供等）；
* 3、胜任工作（持续学习技术）；
* 4、养成习惯
	* （1）做事风格
	* （2）流程习惯
		* a、上线流程
		* b、分支开发流程（有待整理）
		* c、项目总结
		* d、check  list
		* e、……
	* （3）规范
		* a、代码
		* b、日报
	* （4）串讲（月度、回顾）
		* a、产品
		* b、工具
		* c、技术
		* d、收获
		* e、……

## 2、清单详情

> **week 1～2**   

> **TIPS：**

> 1、因人而异，通过以下清单安排下面的1～2周的任务

> 2、掌握程度

> 了解    ＊

> 熟悉    ＊＊＊

> 掌握    ＊＊＊＊＊


工作习惯：周报／日报／会议纪要／发邮件（年度计划／周计划／日计划）；

### 一、熟悉环境（＊＊＊＊＊）

> 目标：帮助大家尽快融入链商这个大家庭:)

**清单：**

* 1、安装QQ、微信:

	* a、增加QQ群：（链商前端技术群）519471170（入群修改马甲->真实姓名）
	* b、微信群：（入群修改马甲->前端＋真实姓名）


* 2、配置企业邮箱

	* [邮箱配置的坑记录.pdf](http://gavin-yyc.github.io/lsh-doc/hy/setup-mail.html)


* 3、注册gitHub帐号

* 4、手机安装滴滴打车app，加班以及公务出差可以享受企业支付

> 以下软件根据自身情况安装使用：

> 5、一款非常实用的商业思维导图软件：[Xmind](http://rj.baidu.com/soft/detail/25727.html?ald)

> 6、云笔记（Evernote、有道云笔记app store里有）

> 7、常用输入法

### 二、linux基本操作（＊＊＊）

> 目标：作为前端开发人员，需要熟练使用基本的linux操作命令，因为在项目中，会经常碰到使用命令行的情况，比如：fis的安装与启用、通过brew来安装软件、git操作等等，一下是一些常用的linux命令，更多命令可自由学习。

**常用命令：**

文件以及目录（高频）：

	cd、ls、pwd、mkdir、rmdir、touch、rm、cp、mv、ln、find、diff、cat、grep

系统管理目录（高频）：

	ifconfig、ping、man、kill

权限管理命令（高频）：

	sudo、su

参考链接：[linux 如何改变文件属性与权限](http://www.cnblogs.com/yangjinjin/p/3165076.html)

> 拓展提高：

> 书籍：《鸟哥的linux私房菜》

> 网址：[Linux入门教程](http://www.92csz.com/study/linux/)

### 三、搭建环境

> 目标：FIS是专为解决前端开发中自动化工具、性能优化、模块化框架、开发规范、代码部署、开发流程等问题的前端工程化构建工具。目前我们以FIS作为主要的前端开发工具，工欲善其事必先利其事所以我们要进行开发环境的搭建。

如果你已经掌握Linux的基本操作，那么就让我们开始安装吧:-D～～


**基础工具清单（＊＊＊＊＊）：**

#### 1.iterm2

由于fis开发需要用到终端，所以这里给大家推荐一款好用的终端软件：iterm2

地址：http://www.iterm2.com/

#### 2.brew

简化安装工作，通过终端安装应用，只需一行终端代码，高端、大气、上档次～～终端软件包管理工具：brew

地址：http://brew.sh/

#### 3.node

`node`对前端工程师有着非常强的亲和力，有各种基于`Node.js`的压缩、优化、校验工具，有着极高的运行性能，有`npm`这样强大的包管理工具……简直就是为自动化和辅助开发工具量身定做的平台。fis也是基于`node`搭建的，这一步我们需要安装`node`。（因为我们只需要配置node环境，并不需要对`node`进行学习，`node`部分的学习不在1~2周的任务清单上。）

地址：

* 可以直接通过brew安装
* [nodeJS](https://nodejs.org/)

安装node后包涵npm包管理工具。

#### 4.Git

版本管理界的当红炸子鸡，非`github`莫属，我们正在使用的版本管理工具就是`gitHub`,在熟悉环境阶段我们已经拥有了`gitHub`的帐号，现在就让我们进一步玩起来。
我们就需要安装他--->免费、开源的分布式版本控制系统：`git`

安装：可以直接通过brew安装

	brew install git

#### 5.fis

我们目前使用的前端工程构建工具：fis

地址：[fis文档](http://fex.baidu.com/fis-site/docs/beginning/getting-started.html)

#### 6.fis-plus

讲到这里可能会有疑惑--->已经安装了fis，fis－plus是什么鬼？？？
--->扩展自FIS的前端集成解决方案：fis－plus

安装：[安装流程](http://oak.baidu.com/fis-plus/document.html)

#### 7.编辑器：

[hpStorm（推荐）](http://www.jetbrains.com/phpstorm/) --> [注册码](http://idea.lanyus.com/)

#### 8.虚拟机

浏览器里面的～--->IE系列浏览器,为了测试IE系列，我们需要进行下面的一系列安装：
--->虚拟机--->win--->IE浏览器**（在公司优盘中）**

#### 9.Photoshop

图片处理，这个有mac版的当然也可以在虚拟机中安装win版的：**photoshop**

#### 10.浏览器

添加常用浏览器

* chrome
* firefox
* ……

#### 11.axure

 简介：是一个专业的快速原型设计工具，让负责定义需求和规格、设计功能和界面的专家能够快速创建应用软件或Web网站的线框图、流程图、原型和规格说明文档。作为专业的原型设计工具，它能快速、高效的创建原型，同时支持多人协作设计和版本控制管理

地址：[快速原型设计工具：axure](http://www.axure.com.cn/1896/)

### 四、学习开发工具

> 目标：熟悉开发工具，使我们更快的融入团队开发\^_^/~~~

#### 4.1 基础工具清单：

* 1、[fis](http://fex.baidu.com/fis-site/docs/beginning/getting-started.html)（＊＊＊＊＊）
* 2、[fis-plus(简称fisp)](http://oak.baidu.com/fis-plus/document.html) （＊＊＊＊＊）
* 3、[学习git指令](http://note.youdao.com/share/?id=81969b26c742a765bc277e96fccd7cb0&type=note)（＊＊＊）
* 4、[注册gitHub帐号](https://github.com/) （＊＊＊）

#### 4.2 扩展提高：

* 1、`jquery`（熟练使用）
* 2、`smarty`（详见代码规范9. smarty函数使用建议，熟悉函数、插件使用方式）
* 3、`less`（掌握最基本的语法：变量、嵌套、混合）
* 4、`bootstrap`（掌握基本的页面布局）

### 五、熟悉招商平台业务（＊＊＊＊＊）

> TIPS：如果已经进行到第五阶段，可以到QQ群@坤哥，开gitHub中的项目权限并且本地浏览项目代码

熟悉招商平台业务是工作重点，要花更多的时间用于理解业务。可以先以招商平台的业务为主，要深入到业务的每个环节进行测试了解

#### 5.1 招商平台网址

 需要绑定hosts，不清楚的同学参考文档有详细流程

> 115.182.215.48 wmdev.lsh123.com

供货商帐号：

>  ne ne 123456

物美帐号：

> admin wumart 123456

链商审核网址：

> 115.182.215.48 wmdev.approve.lsh123.com

供应商审核：

> admin  123456

物美审核：

> wumart1  123456

#### 5.2 VRM测试地址

VRM结算管理平台:
> 115.182.215.48 vrm.wmdev.lsh123.com


### 六、参考文档（排名不分先后）

1、[代码规范](http://note.youdao.com/share/?id=6dea7a098f30417c099fad9aa67ed4e6&type=note)      

2、[fis](http://fex.baidu.com/fis-site/docs/beginning/getting-started.html) 以及 [对工具fis的一些认识.pdf](http://note.youdao.com/yws/public/resource/aea6c12cadc7ee7e53b5b0bf17303787/WEBRESOURCEe75e8d2a7fba43625b63311aab35a624)

3、fisp

* [用户文档](http://oak.baidu.com/fis-plus/document.html)
* [丹妮的fis学习笔记](https://github.com/brambledn/lsh-learner-dn/blob/master/fisp--googleIndexStep.md)

4、git

* [git - 简易指南](http://www.bootcss.com/p/git-guide/)
* [书籍：《Pro Git》](http://git-scm.com/book/en/v2)
* [廖雪峰：Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

5、[linux命令行](http://blog.csdn.net/xiaoguaihai/article/details/8705992)

6、[邮箱配置的坑记录.pdf](http://gavin-yyc.github.io/lsh-doc/hy/setup-mail.html)

7、进阶新人的年度计划参考文档

* [百度技术学院前端.pdf](http://note.youdao.com/yws/public/resource/aea6c12cadc7ee7e53b5b0bf17303787/WEBRESOURCEd8ed45ba27e11aa9407aa7e5d0b7e4de)

8、[环境搭建参考文档](http://youthol.top/2016/01/05/%E6%80%BB%E7%BB%93%EF%BC%9A%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83%E7%9A%84%E9%83%A8%E7%BD%B2/#wpMenuAt14)

9、如何访问招商平台测试地址：

地址：wmdev.lsh123.com

> 需要添加host才能访问

> tips：看流程前，同学们最好了解vim的基础操作

> 流程
