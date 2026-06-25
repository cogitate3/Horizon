---
layout: default
title: "Horizon Summary: 2026-06-25 (ZH)"
date: 2026-06-25
lang: zh
---

> 从 89 条内容中筛选出 9 条重要资讯。

---

1. [Anthropic 指控阿里巴巴非法提取 Claude AI 模型能力](#item-1) ⭐️ 9.0/10
2. [OpenAI 发布首款定制 AI 推理芯片 'Jalapeno'](#item-2) ⭐️ 9.0/10
3. [高通以 40 亿美元收购 AI 初创公司 Modular](#item-3) ⭐️ 9.0/10
4. [IBM 宣布全球首个亚 1 纳米芯片技术](#item-4) ⭐️ 9.0/10
5. [Cloudflare 为所有客户推出自托管 OAuth](#item-5) ⭐️ 8.0/10
6. [谷歌降低 Play Store 费用以履行 Epic 和解协议](#item-6) ⭐️ 8.0/10
7. [LLM 生成的求职申请抹去真实性](#item-7) ⭐️ 7.0/10
8. [ICE 监控技术支出翻倍至历史新高](#item-8) ⭐️ 7.0/10
9. [全球“终局行动”打击网络犯罪工具](#item-9) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Anthropic 指控阿里巴巴非法提取 Claude AI 模型能力](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 9.0/10

据路透社 2026 年 6 月 24 日报道，Anthropic 指控阿里巴巴通过称为模型蒸馏的过程非法提取其 Claude AI 模型的能力。 这一指控凸显了 AI 行业在模型安全和知识产权方面日益紧张的局势，可能对国际竞争和 AI 监管产生重大影响。 模型蒸馏是指利用较大的‘教师’模型来训练较小的‘学生’模型，这使得竞争对手能够在不投入昂贵训练的情况下快速复制能力。

hackernews · htrp · 6月24日 19:48 · [社区讨论](https://news.ycombinator.com/item?id=48664814)

**背景**: 知识蒸馏是一种机器学习技术，将大型预训练模型（教师）的知识转移到较小的模型（学生），从而实现高效部署。虽然常用于微调，但在未经授权的情况下用于提取专有模型能力时则存在争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation</a></li>
<li><a href="https://www.ibm.com/think/topics/knowledge-distillation">What is Knowledge distillation? | IBM</a></li>

</ul>
</details>

**社区讨论**: 评论观点不一：一些人认为蒸馏是标准的微调实践，而另一些人则批评 Anthropic 虚伪，因为 AI 模型是在公共数据上训练的，且像 Anthropic 这样的公司本身未经许可使用了受版权保护的内容。

**标签**: `#AI`, `#model security`, `#distillation`, `#Anthropic`, `#competition`

---

<a id="item-2"></a>
## [OpenAI 发布首款定制 AI 推理芯片 'Jalapeno'](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI 宣布推出其首款定制 AI 推理芯片 'Jalapeno'，该芯片与 Broadcom 合作开发，并由 TSMC 制造。芯片从设计到生产仅用九个月完成，部分设计过程借助 OpenAI 自身的 AI 模型加速。 此举减少 OpenAI 对外部硬件供应商（如 NVIDIA）的依赖，可能降低推理成本并提升其 AI 服务的效率。这标志着 AI 公司开发定制芯片以优化性能并掌控供应链的更广泛趋势。 Jalapeno 芯片专门用于推理（运行已训练的 AI 模型进行预测），而非训练。该芯片采用 TSMC 的先进工艺制造，但具体技术节点细节未公布。

hackernews · jamdesk · 6月24日 17:47 · [社区讨论](https://news.ycombinator.com/item?id=48663324)

**背景**: 推理芯片是专门设计用于高效执行已训练 AI 模型的处理器，注重速度和每次查询的成本。定制芯片指为特定工作负载优化的专用集成电路，比通用硬件提供更好的性能和能效。谷歌（TPU）和亚马逊（Trainium/Inferentia）等公司已采用定制芯片用于 AI。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://naddod.medium.com/inference-chip-guide-the-foundation-of-scalable-ai-applications-d18f2c22b36c">Inference Chip Guide: The Foundation of Scalable AI Applications | by NADDOD | Medium</a></li>
<li><a href="https://www.aboutamazon.com/news/aws/ai-chip-terms-explained">10 AI chip terms to know: GPUs, accelerators, inference, and more</a></li>
<li><a href="https://www.arm.com/glossary/custom-silicon">What is Custom Silicon – Arm®</a></li>

</ul>
</details>

**社区讨论**: 一些评论者对 OpenAI 声称 AI 模型加速了芯片设计表示怀疑，认为这可能是空洞的营销宣传。其他人指出制造商是 TSMC（而非 Intel），并讨论了将模型权重硬编码到硅片中实现极高效率的可能性，尽管这种设计会非常庞大。

**标签**: `#AI chips`, `#OpenAI`, `#Broadcom`, `#custom silicon`, `#inference`

---

<a id="item-3"></a>
## [高通以 40 亿美元收购 AI 初创公司 Modular](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 9.0/10

高通于 2026 年 6 月 24 日宣布以约 40 亿美元收购 AI 初创公司 Modular，后者是 Mojo 编程语言的开发商。此次收购旨在增强高通的 AI 能力和 RISC-V 计划。 此次收购标志着高通的一项重大战略举措，使其能够在 AI 硬件和软件生态系统中更具竞争力。这也表明行业对跨平台 AI 解决方案和 RISC-V 等开放指令集架构的兴趣日益增长。 Modular 的 Mojo 语言基于 MLIR 构建，旨在结合类似 Python 的易用性与 C++/Rust 级别的 AI 工作负载性能。交易包括整个 Modular 团队，包括联合创始人 Chris Lattner，他以创建 LLVM 和 Swift 而闻名。

hackernews · timmyd · 6月24日 13:49 · [社区讨论](https://news.ycombinator.com/item?id=48659798)

**背景**: Modular 开发了 Mojo 编程语言，该语言使用多级中间表示（MLIR）编译器框架，针对 CPU、GPU 和其他加速器进行高性能 AI 计算。RISC-V 是一种免费开放的指令集架构，高通一直在投资将其作为 ARM 的替代方案。此次收购是高通构建涵盖 AI 计算、RISC-V 核心和边缘设备组合的更广泛战略的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/RISC-V_architecture">RISC-V architecture</a></li>
<li><a href="https://www.qualcomm.com/news/releases/2026/06/qualcomm-to-acquire-modular">Qualcomm to Acquire Modular</a></li>

</ul>
</details>

**社区讨论**: 社区情绪复杂：一些人表示失望，认为 Mojo 可能无法实现真正的跨平台，重蹈 SYCL 和 OpenCL 的覆辙。另一些人则认为此次收购对 Modular 员工和高通的战略方向（特别是转向 RISC-V）是积极举措。少数评论者指出，鉴于其创始人对硬件厂商 AI 栈的批评，Modular 被硬件公司收购颇具讽刺意味。

**标签**: `#acquisition`, `#AI`, `#Qualcomm`, `#Modular`, `#Mojo`

---

<a id="item-4"></a>
## [IBM 宣布全球首个亚 1 纳米芯片技术](https://arstechnica.com/gadgets/2026/06/ibm-claims-worlds-first-sub-1-nanometer-chip-technology/) ⭐️ 9.0/10

IBM 宣布了全球首个亚 1 纳米芯片技术，采用新型纳米堆叠晶体管，通过垂直堆叠纳米片沟道来实现更高的晶体管密度。 这一突破可能带来计算性能和能效的显著提升，为未来设备提供更强大、更节能的处理器。 与 IBM 之前的 2 纳米 GAAFET 技术相比，纳米堆叠晶体管预计将缩小约 50%，提供更高的密度和更好的每瓦性能。

rss · Ars Technica · 6月25日 10:00

**背景**: 亚 1 纳米芯片技术是指晶体管特征尺寸小于 1 纳米，超越了传统硅的缩放极限。纳米堆叠晶体管是一种新架构，通过顺序堆叠纳米片沟道，实现更高的密度和节能。这一进步对于延续摩尔定律和推动未来计算创新至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://research.ibm.com/blog/what-is-a-nanostack">What is IBM's nanostack chip architecture? - IBM Research</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#chip manufacturing`, `#nanotechnology`, `#IBM`

---

<a id="item-5"></a>
## [Cloudflare 为所有客户推出自托管 OAuth](https://blog.cloudflare.com/oauth-for-all/) ⭐️ 8.0/10

Cloudflare 宣布了一项新的自托管 OAuth 服务，所有客户均可使用，简化了认证设置，无需依赖第三方提供商。 此举解决了企业认证中的常见痛点，可能为管理自己身份和访问管理的组织降低复杂性和成本。 该服务构建在 Cloudflare 的全球网络之上，并利用 Ory Hydra 支持 OAuth 2.0 和 OpenID Connect。它设计为高效扩展，CPU 使用率极低。

hackernews · terryds · 6月25日 02:18 · [社区讨论](https://news.ycombinator.com/item?id=48668033)

**背景**: OAuth 是一种基于令牌的认证和授权开放标准，常用于单点登录 (SSO) 和 API 访问。管理 OAuth 基础设施可能复杂且容易出错，导致许多组织寻求托管解决方案或自行构建。

**社区讨论**: 社区对此次发布反响积极，Ory Hydra 的作者称赞了其性能和规模。然而，一些用户对 Cloudflare 推出项目后缺乏持续改进的历史表示怀疑，并引用了 Cloudflare Web Analytics 和 Wrangler CLI 等例子。

**标签**: `#OAuth`, `#Cloudflare`, `#Authentication`, `#Identity Management`, `#Single Sign-On`

---

<a id="item-6"></a>
## [谷歌降低 Play Store 费用以履行 Epic 和解协议](https://arstechnica.com/google/2026/06/google-starts-lowering-play-store-fees-making-good-on-epic-games-settlement/) ⭐️ 8.0/10

谷歌已开始在部分市场降低 Play Store 服务费，作为与 Epic Games 和解协议的一部分，并计划于 2027 年全球推广。 此次费用削减标志着应用商店经济模式的重大转变，可能惠及全球开发者，并为由反垄断驱动的移动生态系统变革树立先例。 费用削减今年先在少数额外市场实施，2027 年再全球推广；公告未透露具体降低的百分比。

rss · Ars Technica · 6月24日 17:00

**背景**: Epic Games 的和解源于 2020 年针对 Google Play Store 政策（包括应用内购买 30% 佣金）的反垄断诉讼。作为和解的一部分，Google 同意降低费用并允许替代支付系统。全球范围内，应用商店费用结构一直受到审查，苹果也面临类似案件。

**标签**: `#Google Play Store`, `#Epic Games`, `#app store fees`, `#antitrust`, `#settlement`

---

<a id="item-7"></a>
## [LLM 生成的求职申请抹去真实性](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 7.0/10

Tom MacWright 观察到，求职申请中越来越多地出现 LLM 生成的内容，包括简历、作品集网站、GitHub 项目和提交信息，这使得申请人变得难以区分且缺乏个性。 这种趋势破坏了招聘过程，因为它消除了关于候选人技能和个性的真实信号，迫使招聘人员依赖于信息量较少的指标，并可能导致更差的招聘决策。 MacWright 指出，经过 LLM 优化的完美申请除了表明候选人使用了特定工具外，无法提供任何关于其本人的信息，而且候选人没有展现自我或表达任何真实的内容。

rss · Simon Willison · 6月24日 18:13

**背景**: 大型语言模型（如 GPT-4）可以根据提示生成连贯的文本，这使得它们被用于自动化求职申请。虽然这节省了时间，但存在使候选人同质化的风险，并削弱了帮助雇主评估匹配度的个人特色。

**标签**: `#ai`, `#careers`, `#hiring`, `#llm`, `#authenticity`

---

<a id="item-8"></a>
## [ICE 监控技术支出翻倍至历史新高](https://www.theguardian.com/us-news/2026/jun/24/ice-tech-surveillance-arsenal) ⭐️ 7.0/10

一份新报告显示，美国政府用于移民执法的 AI 监控工具支出从 2024 年到 2025 年翻了一番，超过 3.1 亿美元，并在 2026 年飙升至创纪录的 5.13 亿美元，发生在特朗普第二届政府期间。 监控支出的迅速增长引发了对隐私、公民自由以及 AI 在执法中伦理部署的严重担忧，可能为其他政府机构树立先例。 该报告分析了 ICE 和 CBP 与 11 家提供监控技术的公司的合同，包括面部识别和间谍软件工具，如 Clearview AI 和 Flock Safety 的车牌扫描仪。

rss · The Guardian US · 6月24日 20:07

**背景**: ICE 一直在扩大使用 AI 工具追踪移民，包括面部识别、移动间谍软件和来自 Palantir 等公司的数据分析。这些工具因可能侵犯公民权利和缺乏透明度而受到批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theguardian.com/us-news/2026/jun/24/ice-tech-surveillance-arsenal">‘We should be worried’: report sheds light on ICE ’s booming arsenal of...</a></li>
<li><a href="https://www.npr.org/2025/11/08/nx-s1-5585691/ice-facial-recognition-immigration-tracking-spyware">ICE agents have new tools to track and ID people : NPR</a></li>
<li><a href="https://stateofsurveillance.org/articles/surveillance/ice-surveillance-arsenal-complete-tech-stack/">ICE Surveillance Arsenal 2025: $45M Tech Stack - State of ...</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#surveillance`, `#government contracts`, `#immigration`, `#privacy`

---

<a id="item-9"></a>
## [全球“终局行动”打击网络犯罪工具](https://arstechnica.com/security/2026/06/one-two-punch-delivered-in-global-operation-disrupts-cybercrime-assembly-line/) ⭐️ 7.0/10

在一场名为“终局行动”的全球协调执法行动中，当局同时打击了两个广泛使用的网络犯罪工具，摧毁了相关基础设施并逮捕了嫌疑人。 此次行动通过移除支持恶意软件传播和勒索软件攻击的关键工具，严重破坏了网络犯罪供应链，可能有助于减少全球勒索软件事件。 该行动在 2024 年至 2025 年的多个阶段中，摧毁了超过 1000 台服务器，并扣押了超过 2120 万欧元的加密货币。

rss · Ars Technica · 6月24日 21:03

**背景**: “终局行动”是一项长期进行的国际执法行动，旨在打击僵尸网络和网络犯罪助推工具。该行动始于 2024 年 5 月，已包括针对不同恶意软件家族和投放点的多个阶段。此类行动旨在摧毁网络犯罪分子赖以分发恶意软件和发动攻击的基础设施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.europol.europa.eu/media-press/newsroom/news/end-of-game-for-cybercrime-infrastructure-1025-servers-taken-down">End of the game for cybercrime infrastructure: 1025 servers ...</a></li>
<li><a href="https://www.fbi.gov/news/press-releases/operation-endgame-coordinated-worldwide-law-enforcement-action-against-network-of-cybercriminals">Operation Endgame: Coordinated Worldwide Law Enforcement ...</a></li>
<li><a href="https://www.europol.europa.eu/media-press/newsroom/news/operation-endgame-strikes-again-ransomware-kill-chain-broken-its-source">Operation ENDGAME strikes again: the ransomware kill chain ...</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#cybercrime`, `#law enforcement`, `#tool disruption`

---