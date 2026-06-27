---
layout: default
title: "Horizon Summary: 2026-06-27 (ZH)"
date: 2026-06-27
lang: zh
---

> 从 69 条内容中筛选出 4 条重要资讯。

---

1. [SGLang v0.5.14 在 GB300 上将 DeepSeek-V4 提速 5 倍](#item-1) ⭐️ 8.0/10
2. [IP Crawl：公开摄像头实时地图暴露隐私风险](#item-2) ⭐️ 8.0/10
3. [DSpark：推测解码加速大模型推理](#item-3) ⭐️ 8.0/10
4. [Meta 被前员工起诉，指控其监视 12 个月以压制言论](#item-4) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [SGLang v0.5.14 在 GB300 上将 DeepSeek-V4 提速 5 倍](https://github.com/sgl-project/sglang/releases/tag/v0.5.14) ⭐️ 8.0/10

SGLang v0.5.14 已发布，新增支持 GLM-5.2、LiquidAI LFM2.5、Kimi-K2.7-Code 等多款新模型，并通过新的 Waterfill 和 LPLB 负载均衡方法，在 NVIDIA GB300 上实现了 DeepSeek-V4 的 5 倍吞吐量提升。 此版本显著提升了如 DeepSeek-V4 等混合专家（MoE）模型的推理效率，利用了强大的 GB300 GPU 和新颖的负载均衡技术。在相同交互性下实现 5 倍吞吐量提升，为大型语言模型服务设立了新标准，惠及需要低延迟响应的 AI 应用。 Waterfill 方法处理共享专家分发，而 LPLB 使用线性规划平衡跨冗余专家副本的令牌路由，两者均集成到 DeepEP 专家并行中。其他增强包括用于线性注意力前缀缓存的 int8 检查点池，以及在 Blackwell 上为 DeepSeek-V4 提供的 NVFP4 MoE 量化。

github · Fridge003 · 6月26日 22:57

**背景**: 混合专家（MoE）模型使用多个专门子网络（专家）来提升模型容量，而计算量不会同比增加，但常面临专家间负载不均衡的问题。专家并行将专家分布到多个 GPU 上以提高吞吐量。NVIDIA GB300 是 Blackwell Ultra 系列的一款 GPU，相比前代在每瓦性能上有显著提升。SGLang 是一个面向大型语言模型的开源推理引擎，专注于高性能和灵活性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/NVIDIA_GB300">NVIDIA GB300</a></li>

</ul>
</details>

**标签**: `#SGLang`, `#inference`, `#DeepSeek-V4`, `#GPU`, `#LLM`

---

<a id="item-2"></a>
## [IP Crawl：公开摄像头实时地图暴露隐私风险](https://ipcrawl.com/) ⭐️ 8.0/10

IP Crawl（ipcrawl.com）是一个聚合全球公开可访问摄像头的网站，创建了一个可搜索的实时地图，展示连接到互联网的不安全摄像头。 该项目凸显了物联网设备普遍存在的安全缺陷，许多摄像头出厂时使用默认凭据且无防火墙，任何人都可访问。它引发了严重的隐私担忧，因为用户可以未经同意查看私人空间的实时画面。 该地图可按位置浏览和过滤，画面实时更新。它类似于早期的 Insecam 等项目，后者因道德问题被关闭，突显了问题的持续性。

hackernews · arm32 · 6月27日 19:09 · [社区讨论](https://news.ycombinator.com/item?id=48700834)

**背景**: 许多消费级 IP 摄像头，尤其是低成本型号，设计为即插即用，但通常缺乏更改默认密码或启用加密等安全功能。这些摄像头常通过端口转发或 UPnP 暴露在公共互联网上，而机主并不知情。社区评论指出，自 2012 年以来这已是已知问题，但仍未得到解决。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ipcrawl.com/">IP Crawl</a></li>
<li><a href="https://news.ycombinator.com/item?id=48700834">IP Crawl : living atlas of open webcams discovered on... | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了道德上的不适，将该网站比作用望远镜窥视他人住宅。有人指出自 2012 年以来问题未变，并建议该网站应通知摄像头机主其设备已暴露，而非仅仅显示画面。

**标签**: `#security`, `#privacy`, `#IoT`, `#webcams`, `#surveillance`

---

<a id="item-3"></a>
## [DSpark：推测解码加速大模型推理](https://github.com/deepseek-ai/DeepSpec/blob/main/DSpark_paper.pdf) ⭐️ 8.0/10

深度求索（DeepSeek）发布了 DSpark 论文，并在 Hugging Face 上开源了两个模型——DeepSeek-V4-Flash-DSpark 和 DeepSeek-V4-Pro-DSpark——它们采用一种新颖的推测解码框架，在每用户生成速度上比多令牌预测（MTP）提升了 60%–85%。 该框架大幅降低了推理延迟和成本，使大型语言模型在实时应用中更加实用。深度求索同时公开论文和模型的做法促进了透明度和创新，与许多西方 AI 实验室的封闭做法形成鲜明对比。 DSpark 将并行草稿骨干与一个小型顺序头配对以减少后缀衰减，并使用置信度头和负载感知调度器，在 GPU 空闲时验证更多令牌，繁忙时验证更少。发布的两个模型（Flash 和 Pro）基于 DeepSeek-V4 构建，并集成了 DSpark 模块。

hackernews · aurenvale · 6月27日 09:18 · [社区讨论](https://news.ycombinator.com/item?id=48696585)

**背景**: 推测解码是一种针对自回归大语言模型的推理时优化技术：一个小型草稿模型提出多个候选令牌，大型目标模型通过一次前向传播验证它们，在保持目标模型输出分布不变的同时将延迟降低 2-3 倍。DSpark 在此基础上增加了额外机制，进一步提升了效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>
<li><a href="https://www.marktechpost.com/2026/06/27/deepseek-releases-dspark-a-speculative-decoding-framework-that-accelerates-deepseek-v4-per-user-generation-60-85-over-mtp-1/">DeepSeek Releases DSpark , a Speculative Decoding... - MarkTechPost</a></li>

</ul>
</details>

**社区讨论**: 社区称赞深度求索不仅突破技术边界，还发布了详细论文，这不同于许多美国实验室的做法。用户注意到模型已直接在 Hugging Face 上提供，内置了推测解码功能，并分享了使用 DeepSeek-V4 Pro 的正面体验，称其速度快、可靠性高且成本低。

**标签**: `#speculative decoding`, `#LLM inference`, `#DeepSeek`, `#AI optimization`

---

<a id="item-4"></a>
## [Meta 被前员工起诉，指控其监视 12 个月以压制言论](https://fortune.com/2026/06/26/meta-wynn-williams-surveillance-gag-order-lawsuit-2026/) ⭐️ 8.0/10

"Careless People"一书的作者、前 Meta 员工提起诉讼，声称 Meta 对她进行了长达 12 个月的广泛监视，以执行禁言令并让她保持沉默。 此案凸显了企业对员工进行监视的担忧，以及科技巨头监控前员工的能力，这可能会阻碍举报和言论自由。 诉讼指控 Meta 利用授权访问权限监视作者的通讯，试图执行不贬低协议，阻止她谈论自己的经历。

hackernews · 1vuio0pswjnm7 · 6月27日 21:14 · [社区讨论](https://news.ycombinator.com/item?id=48701822)

**背景**: Meta（前身为 Facebook）是一家大型科技公司，曾因隐私和数据处理问题受到审查。保密协议（NDA）在企业中很常见，用于保护商业机密，但批评者认为它们可能被用来压制合理的批评。这起诉讼指控 Meta 超越了一般的 NDA 执行，积极监视前员工。

**社区讨论**: 评论者对 Meta 的行为表示怀疑，有人指出如果指控不实，Meta 恰恰会采取这种行动。还有人建议将“史翠珊效应”以作者的书名重新命名。为了透明起见，提供了实际法庭起诉书和存档版本的链接。

**标签**: `#Meta`, `#surveillance`, `#lawsuit`, `#privacy`, `#tech ethics`

---