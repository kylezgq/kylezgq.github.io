---
layout: post
title: "模型即产品？"
date: 2023-06-05
categories: Large Language Models
---


目前最头部的模型公司，如 OpenAI、Anthropic、Google Bard 等，都是既做模型又做产品，这与移动互联网时期非常不同。移动互联网时期，底层技术如 LBS、4G/5G ，和上层应用如淘宝、滴滴，是相对分离的。

为什么 AI 时代，这些公司需要既做底层技术（模型），又做产品（应用）？当下的 AI 时代和过去十年的移动互联网时期相比，有哪些不同？

**我觉得核心在于当下的 AI 还处于非常早期的阶段，这个阶段的技术并不 ready，需要 “技术驱动产品”。** 移动互联网时期（2010 年 - 2020 年），最优秀的公司成立于 2010 年之后的 3-4 年内，现在 AI 才刚刚开始。

ChatGPT 是一个非常朴素的聊天机器人产品，只有一个聊天界面，用户直接和大模型对话、交互。于 OpenAI 而言，这是非常高效构建数据反馈闭环的一种方式，用户对 ChatGPT 回答的每一次反馈，都是宝贵的数据积累，在早期能够迅速建立起数据飞轮效应形成壁垒。

如前文提到，头部的模型公司不仅 OpenAI 一家，我针对这个市场做了一些资料搜集整理，在此开源出来。

## 科技大厂
---

**微软** 2016 年与 OpenAI 展开了合作，2019 年向 OpenAI 投资了 10 亿美金。

得益于二者之间的战略合作关系，微软基于 OpenAI 的大模型推出了一系列全新的产品。有些是叠加生成式 AI 能力，有些则是全新的 AI-Native 产品。例如新一代搜索引擎 New Bing、对标 Notion 的团队生产力工具 Loop、新一代 AI-Copilot 的 Office 365 全家桶，以及在 Microsoft Build 2023 大会上推出的 Windows+Copilot，全系统层面集成 AI-Copilot。

微软的 “死对头” **谷歌**也有自研的大模型：PaLM，直接面向用户的产品叫 Bard，还有一个针对团队生产力工具产品 Duet ai。

Bard 在 2023 年 5 月举办的 Google I/O 大会中，宣布了新的功能和更新：接入网络，支持实时搜索网页内容；新增日语和韩语；取消申请使用的候补名单；与 Adobe 的 AI 图像生成功能合作，与 Firefly 的功能整合；接入谷歌地图。

Duet ai 类似微软的 365 Copilot，主要应用场景是 Google Workspace。通过打通谷歌的一系列办公软件，实现辅助写作、幻灯片生成、Meeting 的自动摘要等。

除此之外还有 **Meta** 的模型 LLaMA，产品有 Alpaca、Vicuna 等。

## 初创公司
---

**Anthropic** 由来自前 OpenAI 的员工创立，面向用户的聊天机器人产品为 Claude。目前一些测评反馈，Claude 可以在一些方面与 GPT-4 持平，诸如长对话和上下文理解时，Claude 的表现更佳。

**Inflection** 的愿景是成为人类的 AI 个人助理，旗下的第一款产品为 Pi，前不久推出了语音对话的功能，我试用了一番觉得体验很不错。同类产品如 Banterai.com，语音对话会出现掉线、许久不能接通的情况；Call Annie、Replika 等虽然里面的角色和声音的可选项更多，但目前来看 Pi 的产品界面是最简洁、体验最舒适的。

据用户反馈，Pi 和 ChatGPT 最大的不同之处在于能提供更多的情绪价值，更加善解人意、情商高。

<img src="https://kylezgq.github.io/assets/images/2023-06-05-01.png" width="600">

**Adept** 是由 Transformer 的八位作者中的 Ashish Vaswani 和 Niki Parmar 在离开谷歌后，与 David Luan 共同成立。

与其它 AI 个人助理不同，Adept 选择了一条截然不同的路线：通过建立 AI 工具实现自动化托管人类的事情，帮助人类执行各种任务。根据 CEO David Luan 的描述，Adept 要做的事情更像是 RPA（Robotic Process Automation，机器人流程自动化），例如自动回复邮件等，所有的任务请求通过与 Airtable、PhotoShop、Tableau、Twilio 等产品共同实现。

Ashish Vaswani 和 Niki Parmar 二人在成立 Adept 后不到一年时间因为一些原因而先后离开了 Adept，目前 Adept 仍未推出自己的产品。与此同时，市场上已经出现了非常多的平替，多为独立开发者所开发，例如 Multion、UnAGI，以及比较著名的 AutoGPT 等。

**Cohere** 的创始人同样来自 Transformer 中的八位作者 ——Aidan Gomez。目前 Cohere 有两个文本生成模型，分别是 Command 和 Command-light。与 ChatGPT 类似，支持文本生成和上下文对话，官方提供了非常直观易用的 SDK，可以使开发人员快速基于 Command 模型构建、整合进应用程序。

还有一家初创公司同样值得关注。**AI21 Labs** 是一家以色列公司，旗下有：Wordtune，是 AI21 Labs 的第一个产品，AI 驱动的写作辅助工具；Jurassic-1 Jumbo 模型，模型大小与 GPT-3 相近；以及 AI21 Studio，一个 AI-as-a-Service 的平台。

Wordtune 是一个 Paraphrasing（内容改写）工具，支持内容重写、写作风格切换（随意风格和专业风格），以及内容缩写和扩写。

<img src="https://kylezgq.github.io/assets/images/2023-06-05-02.png" width="600">

Wordtune 的产品形态目前有两种，一种是类似 Grammarly 的浏览器插件，用户在 Google Docs 中或是任何网站，例如 Twitter、LinkedIn、Gmail 等，都可以通过鼠标光标选中进行内容编辑操作。

另一种则是一款 all-in-one 的内容编辑器，比较像剥离多人协作功能后的 Notion。相比插件多了两个功能，分别是 Read & Summarize 和 Spices。前者是总结内容生成摘要，用户上传文件 PDF、URL 或是若干段文字，即可生成对应内容的摘要总结，但不支持生成总结摘要之后的问答。Spices 功能是 AI21 Labs 的大模型能力的主要体现，支持内容续写、举例、论证强调和改编为笑话等更高级的功能，目前还处于 beta 测试阶段。

<img src="https://kylezgq.github.io/assets/images/2023-06-05-03.png" width="600">

Wordtune 目前提供了两种用户使用方案，免费版每天有 5 次试用机会，付费版不限次数，每月 9.99 美金。

AI21 Studio 是 2021 年 8 月发布的，提供 “即用即付” 服务。开发者可申请访问根据其需求独特的数据集，亦或是 Jurassic 系列模型的 API，在 AI21 Studio Playground 中进行微调自定义模型。

在 AI21 Studio 中，Jurassic 系列模型可用于释义，例如从长文本描述中生成总结性词语，从文本中提取内容，以及按主题标记电子邮件等。这些模型还可以通过 Wordtune 中的 Read & Summarize 功能来汇总内容，包括来自文章，报告和 PDF 文件的片段。

**目前大模型的市场共识是开源和闭源模型共存，但具体最终会演进成怎样的市场格局，这是存在非共识的地方。**

[Chatbot Arena](https://chat.lmsys.org/?leaderboard) 是一个基于大众参与的大型语言模型基准平台，通过匿名、随机的语言模型之间进行对决来评估模型的效能。经过超过 27,000 次对决，OpenAI 的 GPT-4 获得了第一名。**紧跟其后是 Anthropic 的 Claude。Vicuna 等开源模型同样出现在了这场模型竞赛中，这给 “开源派” 带来了希望：私人公司无法最终垄断大模型市场。**

<img src="https://kylezgq.github.io/assets/images/2023-06-05-04.png" width="600">

**企业最终可能会采用多个大模型实现自身的业务目的，而非仅采用例如 OpenAI 一家。** 例如：需要强推理能力的任务采用 GPT-4，对成本有要求的采用开源模型，需要强共情能力的任务采用 Inflection。

<img src="https://kylezgq.github.io/assets/images/2023-06-05-05.png" width="600">

我很期待这场大模型之间的技术竞争，有人说这是一个 **“类云计算服务市场”**，有人说这是 **“类 iOS 和 Android 市场”**…… 如果你也对此充满好奇与想法，欢迎联系我！

