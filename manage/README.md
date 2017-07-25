### 项目管理

#### [Repo](https://code.google.com/archive/p/git-repo)
> repo是Android项目团队为了方便管理Android项目及组成Android项目的几百个项目的Git库而开发的一套Python脚本，需翻墙。

#### [Submodule](https://git-scm.com/docs/git-submodule)
> Git 1.5.3中加入了git submodule这个命令。Git子模块允许你将一个Git仓库作为另一个Git仓库的子目录。它能让你将另一个仓库克隆到自己的项目中，同时还保持独立的提交。

#### [git-subtree](https://github.com/apenwarr/git-subtree/)
> Git在1.8.0版本引入了git subtree这个命令，它使用Git的subtree merge策略来得到类似git submodule的结果，使用git subtree，你不仅可以将其他项目合并为父项目的一个子目录，而且可以从父项目提取某个子目录的全部历史作为一个单独的项目。

#### [gitslave](http://gitslave.sourceforge.net/)
> GitSlave用于管理相关的一个父项目和多个Slave项目。通常，它会将你要执行的Git常规操作顺序在父项目和Slave项目中执行一遍，所以当你执行pull操作，项目中的所有仓库会顺序执行pull操作。GitSlave是对Git命令的封装，是被设计用于简化多仓库的Git操作，而不是要取代Git。

#### [Git多项目管理](http://www.jianshu.com/p/284ded3d191b)
> 介绍Git Submodule，Git Subtree，GitSlave和Google Repo这四种方式来管理多个Git项目

### 工作流

#### [Git工作流指南：集中式工作流](http://blog.jobbole.com/76847/)

#### [Git工作流指南：功能分支工作流](http://blog.jobbole.com/76857/)

#### [Git工作流指南：Gitflow工作流](http://blog.jobbole.com/76867/)

#### [Git工作流指南：Forking工作流](http://blog.jobbole.com/76861/)

#### [Git工作流指南：Pull Request工作流](http://blog.jobbole.com/76854/)

#### [Git工作流指南总结](http://blog.jobbole.com/76843/)

#### [Git工作流指南比较英文原文](https://www.atlassian.com/git/tutorials/comparing-workflows)

#### [Gitlab Gitflow总结](http://blog.csdn.net/uxyheaven/article/details/50373076)

#### [GitFlow](http://nvie.com/posts/a-successful-git-branching-model/)
>  一种借助Git分支来完成项目开发的工作流程，附上[GitHub地址](https://github.com/nvie/gitflow)。

#### [改进合作 Git 工作流：自动提取、合并提交](http://tech.meituan.com/improving-git-flow_squashing-commits.html)
> Git工作流

### 团队协作

#### [slack群组](http://slack.com/)
> Slack 是聊天群组 + 大规模工具集成 + 文件整合 + 统一搜索集为一体，是团队项目开发沟通的首选。

####  [teambition](https://www.teambition.com/)
> 国内一家工作做得一个高效而稳定的项目协作平台，它基于云服务的协作化项目管理平台，用户可以通过【任务板】【分享墙】【文件库】等功能来实现项目知识的分享、沟通，项目任务的安排及进度监督，以及相关项目的文档存储和分享。

#### [tower](https://tower.im/)
> 一款团队协作工具，可以让团队在 Tower.im 里在线讨论、任务指派管理、文件共享、日程安排、查看在线文档。

####  [trello](https://trello.com/)
> 国外一个方便的团队协作工具。它拥有足够的灵活度，来应对不同团队的需求，也通过详细的设置和安排，方便团队或项目负责人查看项目进度。

####  [worktile](https://worktile.com/)
> 一个团队协同办公工具，通过简单的协作、沟通和分享，实现团队交互与任务管理的轻松协作。工作随身带，多平台、云数据，随时随地与团队一起工作，项目、任务、文件、讨论、文档、事件、活动流、通知和日历，一个都不能少。

#### [ZenHub](https://www.zenhub.io/)
> 一款项目管理工具，嵌入到GitHub中，作为插件，与GitHub做到无缝结合

### 持续集成

#### [Jenkins](https://jenkins.io/)
> 一个用Java编写的开源的持续集成工具

#### [TravisCI](https://travis-ci.org/)
> 持续集成，用于自动化的单元测试和自动化部署，可以设定通过测试自动部署上线

#### [CircleCI](https://circleci.com/)
> 持续集成，用于自动化构建、测试、部署。

#### [Gitlab-CI](https://about.gitlab.com/features/gitlab-ci-cd/)
> 与Gitlab集成，无缝结合

### 代码审查

#### [Gerrit](https://www.gerritcodereview.com/)
> 一个开源的code review代码审查软件，Android源代码就是用该软件进行代码审查的

#### [Reviewable](https://reviewable.io/)
> 代码Review工具，可以与GitHub无缝结合，当你提交一个PR时，在你的PR中，会在评论框中嵌入这样的一个按钮：点击进入Reviewable的页面对应的PR进行review，并且一个PR没有完成Review之前，是会一直被警告，让你警惕进行合并。


#### [Code Reviewer](https://codereview.appspot.com/)
> Code Reviewer是一款免费的、简单的又易于部署和使用的代码审查工具，由SmartBear开发——也是Collaborator的发明者，业界第一家推出商用代码审查工具的公司。

#### [Peer Review Plugin](http://trac-hacks.org/wiki/PeerReviewPlugin)
> 此款插件通过提供基于Web的友好的审查环境，来节省开发人员在代码审查会议上所需要浪费的时间。

#### [Review Board](https://www.reviewboard.org/)
> Review Board是程序员节约时间、资金和精力的代码审查好工具。语法高亮的代码，可便于更快读取。

#### [Code Review Tool](http://codereviewtool.com/)
> Code Review Tool允许团队成员通过一种简单而有效的方式来协作审查代码。它提供了正式代码检查的所有优势，而且相比而言，所需的精力和时间更少。它既支持正式，也支持轻量级的代码审查进程。

#### [Crucible](https://www.atlassian.com/software/crucible/overview)
> Crucible是另一款超级受开发人员欢迎的代码审查工具，可以审查代码、讨论修改，通过Crucible灵敏的审阅流程来确定缺陷。Crucible能够使得Subversion、CVS、Perforce等版本控制软件的代码审查变得简单起来。

#### [Codifferous](https://codifferous.com/)
> Codifferous是一款免费的代码审查工具，能为我们提供更快的代码审查服务。无论你在何时何地，Codifferous能让你的团队协作审查工作变得更容易。你忘记了一个pull请求？没事。Codifferous允许你检查任意分支上的代码，无论何时你都可以留下注释、获得反馈。

#### [RhodeCode](https://rhodecode.com/)
> RhodeCode是另一款非常棒的代码审查工具，能让你发现代码中的bug和问题，并在检查过后删除它们。

#### [Codebrag](http://codebrag.com/)
> Codebrag是一款简单轻巧，提高进程作为的代码审查工具。它能帮助我们解决不少问题，如非阻塞代码审查、智能邮件通知、联机注释等等。

#### [Coveralls](https://coveralls.io/)
> 代码覆盖率测试工具，结合TravisCI的自动化测试单元，提高你对项目的信心

### 文档管理

#### [DokuWiki](https://www.dokuwiki.org/dokuwiki#)
> 一款开源的wiki管理软件

#### [Raneto](http://raneto.com/)
> 利用 Markdown进行文档管理的系统

#### [MkDocs](http://www.mkdocs.org/)
> 项目文档生成器

#### [Notion](https://www.notion.so/)
> 在线的Docs、Wikis、Tasks管理工具，团队协作的利器。

#### [ShowDoc](https://www.showdoc.cc/)
> 一个适合IT团队的在线API文档、技术文档工具,支持离线部署。

#### [RAP](https://github.com/thx/RAP)
> Web接口管理工具，开源免费，接口自动化，MOCK数据自动生成，自动化测试，企业级管理。阿里妈妈MUX团队出品！

#### [EasyAPI](http://www.easyapi.com/)
> EasyAPI是一个为您提供API管理、API测试、API监控、API文档的综合性API服务平台。

#### [slate](https://github.com/lord/slate)
> 一个精美的API静态文档生成工具

#### [SosoApi](http://www.sosoapi.com/)
> 专注于API接口文档管理及线上线下测试的API服务平台

#### [ApiManager](https://github.com/gongwalker/ApiManager)
> 一个PHP开源项目，接口文档管理平台

#### [APIDOC](http://apidocjs.com/)
> 在线接口文档

#### [apiary](https://apiary.io/)
> 能够快速启动和运行文档，包括GitHub集成和I/O验证

#### [swagger](http://swagger.io/)
> Swagger框架可以通过代码生成漂亮的在线API，甚至可以提供运行示例。支持Scala、Java、Javascript、Ruby、PHP甚至 Actionscript 3。

#### [I/O Docs](https://github.com/mashery/iodocs)
> I/O Docs是一个用于RESTful Web APIs的交互式文档系统。使用 JSON 模型根据资源、方法和参数定义 APIs。I/O Docs 将生成 JavaScript 客户端接口，可通过这些接口来调用系统。服务器端基于 Node.js 开发。

#### [JSONDoc](http://jsondoc.org/)
> easily generate docs and playground for your RESTful API

#### [Docco](http://jashkenas.github.io/docco/)
> Docco是一个快速而随意、hundred-line-long、迭代程序风格的文档生成器。它会以HTML的方式显示评论和代码。

#### [Dexy](http://www.dexy.it/)
> 非常灵活的一款文档工具，支持任何语言编写的API。

#### [Doxygen](http://www.stack.nl/~dimitri/doxygen/)
> Doxgen可以从一套归档源文件开始，生成HTML格式的在线类浏览器，或离线的LATEX、RTF参考手册。对于未归档的源文件，也可以通过配置Doxygen来提取代码结构。

#### [TurnAPI](http://turnapi.com/)
> 是一款付费的文档API工具。里面包含了智能WIKI编辑器、基于标准的Markdown、文档分支、还可以与Git、SVN、Mercurial同步、整洁的主题、友好的界面。

### 自动化测试

#### [STF](http://openstf.io/)
> 移动端开源的利用web来管理终端设备的解决方案

### 经验分享

#### [团队技术信息流建设](https://juejin.im/post/5955cd0e6fb9a06bc23a853e)

#### [Travis CI - 项目持续集成好伴侣](http://swiftcafe.io/2016/03/18/travis/)

#### [如何提升你的能力？给年轻程序员的几条建议](http://tech.glowing.com/cn/advices-to-junior-developers/)

#### [怎么做好互联网公司的技术团队负责人？](http://www.jianshu.com/p/463528c4ec91)

#### [写给那些傻傻的，想做服务器开发的应届生](http://blog.devtang.com/blog/2015/10/07/why-fresh-wants-to-do-server-dev/)

### 其他

#### [选择一个开源协议](http://choosealicense.online/)
> 为你自己的开源项目选择一个合适的开源协议

#### [Sonatype Nexus](https://www.sonatype.com/)
> Maven私服搭建服务

#### [强迫症的 Mac 设置指南](https://github.com/macdao/ocds-guide-to-setting-up-mac)
