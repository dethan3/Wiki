---
title: Python 潮流周刊#23：35 个容易上手的 Python 小项目
date: 2023-10-22
updated: 2024-5-21 02:03:25
authors:
  - luojiyin1987
original: https://pythoncat.top/posts/2023-10-22-weekly/
categories:
  - Article
  - Translation
toc: true
---

你好，我是猫哥。这里每周分享优质的 Python、AI 及通用技术内容，大部分为英文。标题取自其中两则分享，不代表全部内容都是该主题，特此声明。

本周刊由 **Python 猫** 出品，精心筛选国内外的 250+ 信息源，为你挑选最值得分享的文章、教程、开源项目、软件工具、播客和视频、热门话题等内容。愿景：帮助所有读者精进 Python 技术，并增长职业和副业的收入。

[微信][1] | [博客][2] | [邮件][3] | [GitHub][4] | [Telegram][5] | [Twitter][6]

本周刊的源文件归档在 GitHub 上，已收获 730+ star 好评，如果你也喜欢本周刊，就请给颗 star 支持一下吧：[https://github.com/chinesehuazhou/python-weekly][7]

<!-- more -->

## 🦄 文章&教程

1、[20 个令人兴奋的 Python 项目创意][8]

经常看到有人问：有没有简单易上手的 Python 项目推荐？不妨看看这篇文章，它介绍了 20 个小项目的想法，另外原作者已经实现了很多项目，源码可从文中的[仓库地址][9]获取。

2、[Python 3.11 vs Python 3.12 之性能测试][10]

文章在配备 AMD 锐龙 7000 系列和第 13 代英特尔酷睿处理器的不同机器上共进行了 91 种基准测试，详细给出了各项数值。

3、[当我遇见了 Guido van Rossum][11]

作者在今年 Pycascades 上做了演讲“Python 中用元类作元编程”，并遇见 Guido，他们聊了一些 Python 使用中的话题以及如何成为 CPython 核心开发者。

4、[通过阅读代码学习：Python 标准库设计决策解释][12]

程序员提升能力的一个方法是大量阅读优秀的代码，Python 标准库就是很好的选择。但标准库茫茫之多，该选择哪些呢？文章作者推荐了这些：**statistics、pathlib、dataclasses、graphlib**。

5、[使用 Stripe、Vue.js 和 Flask 开发收款功能][13]

国人的付费意愿差，独立开发者选择出海掘金的话，大多会选择用 Stripe 账号。这篇教程使用 Stripe 实现网站的收款功能，前后端技术栈为 Vue 和 Flask。

6、[使用 Python 调用 Rust 的三种方法][14]

介绍了 Python 调用 Rust 的三种方法：HTTP、IPC（进程间通信） 和 FFI（外部函数接口）。

7、[如何开发 FastAPI 的中间件？][15]

FastAPI 内置了一些中间件，但你可能还需要量身定制自己的中间件。文章介绍了 FastAPI 中间件原理及内置的中间件，然后基于函数和基于类来实现自定义中间件，给出了最佳实践建议以及相应的测试用例。

8、[Django 项目实现无密码身份验证][16]

文章介绍了三种无密码的身份验证方法：基于邮件的身份验证、使用 OAuth 进行身份验证和使用超链接进行身份验证；介绍了它们的优点、局限性以及使用的注意事项。

9、[在发布 Python 项目前，建议用上这 4 个工具][17]

有什么工具可以简化开发工作流程，遵循行业构建良好软件的最佳实践？文章分享了 4 种好用的工具：**Poetry、Pre-commit 钩子、Makefiles、python-dotenv**。

10、[我们必须聊聊 Flask][18]

Flask 最近发布了 3.0 版本，Werkzeug 也同时发了 3.0 版本，但它引入了不向后兼容的更改！作者吐槽 Flask 总是出现版本不兼容的问题，给出了不少例子和原因分析，希望 Flask 核心开发不要做无端的重构，要三思而行。（文章出自《Flask Web Development》一书的作者）

11、[基于 ProPainter 技术去除图片以及视频水印][19]

介绍使用 ProPainter 框架来解决视频去水印问题，它引入了双域传播的新方法和一种高效的遮罩引导视频 Transformers，增强了视频修复的性能，同时保持了计算效率，成本更低。

12、[Google Sheets 也能用 Python 了][20]

微软在 8 月让 Excel 支持了 Python，现在一家名为 Neptyne 的公司推出了一款在 Google Sheets 中使用 Python 功能的产品。文章介绍了它的基本情况。

🎁**Python 潮流周刊**🎁 已免费发布了 23 期，访问下方链接，即可查看全部内容：[https://pythoncat.top/tags/weekly][21]

如果你觉得周刊有价值，请表达小小心意，赞赏一下猫哥吧~~

![](https://img.pythoncat.top/support_pythoncat.png)

## 🐿️ 项目&资源

1、[一个 Python 知识问答网站][22]

一个很简洁的网站，有近百道选择题，大多是 Python 基础语法相关的内容。来测一下你都学会了么？

2、[CardStock：跨平台的 GUI 构建工具][23]

它提供了一个类似于绘图程序的编辑器，用于构建图形用户界面，支持文本、图形、图像、按钮、输入框和 Web 视图等元素；提供了一个代码编辑器，可添加事件驱动的 Python 代码。

3、[python-package-template：标准化的 Python package 模板][24]

它内置了单元测试、代码检查、格式化、包管理、pre-commit 配置、GitHub Actions 等众多方便的工具，可以很方便的管理 Python 项目。（投稿自@Undertone0809）

4、[pipeless：一个计算机视觉框架][25]

轻松构建与部署可实时分析及操作视频流的应用，无需构建和维护多媒体 pipeline。支持插件，例如使用 Kafka 实时处理事件、使用 YOLOv8 模型等。

5、[RealtimeSTT：强大、高效、低延迟的语音转文本库][26]

它具有高级语音活动检测、唤醒词激活和即时转录功能，使用的技术栈有：语音活动检测（**WebRTCVAD、SileroVAD**）、语音转文本（**Faster Whisper**）、唤醒词检测（**Porcupine**）。

6、[Chrome-GPT：可控制 Chrome 的 AutoGPT 代理][27]

它利用 Langchain 和 Selenium 使 AutoGPT 代理能够控制 Chrome 会话。支持以交互方式滚动、单击和输入网页上的文本，从而可以导航和操作 Web 内容。（star 1.4K）

7、[ZenNotes：Windows 记事本，支持翻译和 TTS][28]

一个简约的 Windows 记事本程序，支持翻译、TTS、Markdown，基于 [PyQt-Fluent-Widgets][29] 开发而成。

8、[kr8s：用于 Kubernetes 的客户端库][30]

用于 k8s 的一个简单、可扩展的 Python 客户端库，如果你用过 **kubectl**，就会觉得它很熟悉。

9、[swirl-search：用 AI 同时搜索多个数据源][31]

可搜索多个内容源并返回 AI 的排名结果，支持连接到数据库（SQL、NoSQL、Google BigQuery）、公共数据（谷歌、Arxiv）、企业数据源（Microsoft 365、Jira、Miro 等）。

10、[sentry：面向开发者的错误跟踪和性能监控平台][32]

一个强大的错误跟踪和性能监控平台，还支持定期任务监控、代码覆盖率、会话重播、告警、安全策略等功能，支持 100 多种平台和框架，支持 30+ 编程语言。（star 35.4K）

11、[15 个 Python 小项目][33]

这个仓库收录了一些 Python 小项目及其实现代码，跟本期周刊的第一则分享相似。（star 1K）

12、[ssh-audit：SSH 服务器和客户端安全审计][34]

用于审查 SSH 的配置，支持 SSH1 和 SSH2 协议，支持 Linux 和 Windows，可识别安全漏洞、不安全密钥、不安全算法等，并给出安全建议。另外它也有[在线版本][35] 。（star 2.6K）

## 🐢 播客&视频

1、[哥本哈根 2023 Django Day 演讲视频][36]

Django Day 是一个专门围绕 Django 框架和 Django 社区的活动，目前视频列表中有 11 则视频。

2、[Talk Python To Me #434：用 Python 构建移动 APP][37]

Python 能够用于开发移动端应用么？能不能用 Python 实现端到端的移动应用开发？这期播客邀请了几个移动端 APP 的开发者聊了相关话题。

## 🐱 赞助&支持

如果你喜欢周刊，请分享给其他需要的同学，让更多人可以从中受益～

如果你觉得周刊有价值，请随意[赞赏][38] 或 [买杯咖啡][39] 进行支持！

如果你想帮助周刊办得更好，欢迎向我们投稿或提出建议：[投稿/建议通道][40]

如果你是品牌方或广告主，欢迎私信我，洽谈赞助与合作事项。

## 🐼 欢迎订阅

- [微信公众号][41]：除更新周刊外，还发布其它原创作品，并转载一些优质文章。（可加好友，可加读者交流群）
- [博客][42] 及 [RSS][43]：我的独立博客，上面有历年原创/翻译的技术文章，以及从 2009 年以来的一些随笔。
- [GitHub][44]：你可以获取本周刊的 Markdown 源文件，做任何想做的事！
- [邮件][45]：在 Substack 上开通的频道，满足你通过邮件阅读时事通讯的诉求。
- [Telegram][46]：除了发布周刊的通知外，我将它视为一个“副刊”，补充发布更加丰富的资讯。
- [Twitter][47]：我的关注列表里有大量 Python 相关的开发者与组织的账号。

![](https://img.pythoncat.top/wechat_code.png)

[1]: https://img.pythoncat.top/python_cat.jpg
[2]: https://pythoncat.top/
[3]: https://pythoncat.substack.com/
[4]: https://github.com/chinesehuazhou/python-weekly
[5]: https://t.me/pythontrendingweekly
[6]: https://twitter.com/chinesehuazhou
[7]: https://github.com/chinesehuazhou/python-weekly
[8]: https://dev.to/praise002/20-exciting-python-project-ideas-3la9
[9]: https://github.com/praise002/20-python-project
[10]: https://en.lewoniewski.info/2023/python-3-11-vs-python-3-12-performance-testing/
[11]: https://blog.adarshd.dev/posts/when-i-met-guido-van-rossum/
[12]: https://death.andgravity.com/stdlib
[13]: https://testdriven.io/blog/accepting-payments-with-stripe-vuejs-and-flask/
[14]: https://blog.frankel.ch/rust-from-python/
[15]: https://semaphoreci.com/blog/custom-middleware-fastapi
[16]: https://www.honeybadger.io/blog/options-for-passwordless-authentication-in-django/
[17]: https://thetechbuffet.substack.com/p/improve-python-development-workflow
[18]: https://blog.miguelgrinberg.com/post/we-have-to-talk-about-flask
[19]: https://juejin.cn/post/7288998044020326415
[20]: https://thenewstack.io/python-comes-to-google-sheets/
[21]: https://pythoncat.top/tags/weekly
[22]: http://python.jpglomot.com/#/questions
[23]: https://github.com/benjie-git/CardStock
[24]: https://github.com/Undertone0809/python-package-template
[25]: https://github.com/pipeless-ai/pipeless
[26]: https://github.com/KoljaB/RealtimeSTT
[27]: https://github.com/richardyc/Chrome-GPT
[28]: https://github.com/rohankishore/ZenNotes
[29]: https://github.com/zhiyiYo/PyQt-Fluent-Widgets
[30]: https://github.com/kr8s-org/kr8s
[31]: https://github.com/swirlai/swirl-search
[32]: https://github.com/getsentry/sentry
[33]: https://github.com/zhiwehu/100_plus_Python_Projects_Challenge
[34]: https://github.com/jtesta/ssh-audit
[35]: https://www.ssh-audit.com/
[36]: https://www.youtube.com/playlist?list=PLEpW1LzVyQWgtT_i_IlUmx2FSP2jHcroX
[37]: https://talkpython.fm/episodes/show/434/building-mobile-apps-backed-with-python
[38]: https://img.pythoncat.top/wechat_code.png
[39]: https://www.buymeacoffee.com/pythoncat
[40]: https://github.com/chinesehuazhou/python-weekly/issues/new
[41]: https://img.pythoncat.top/python_cat.jpg
[42]: https://pythoncat.top/
[43]: https://pythoncat.top/rss.xml
[44]: https://github.com/chinesehuazhou/python-weekly
[45]: https://pythoncat.substack.com/
[46]: https://t.me/pythontrendingweekly
[47]: https://twitter.com/chinesehuazhou
