---
layout: default
title: "Horizon Summary: 2026-06-27 (EN)"
date: 2026-06-27
lang: en
---

> From 69 items, 4 important content pieces were selected

---

1. [SGLang v0.5.14 Boosts DeepSeek-V4 5x on GB300](#item-1) ⭐️ 8.0/10
2. [IP Crawl: A live atlas of open webcams exposes privacy risks](#item-2) ⭐️ 8.0/10
3. [DSpark: Speculative Decoding Accelerates LLM Inference](#item-3) ⭐️ 8.0/10
4. [Meta Sued for Allegedly Surveilling Former Employee for 12 Months](#item-4) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [SGLang v0.5.14 Boosts DeepSeek-V4 5x on GB300](https://github.com/sgl-project/sglang/releases/tag/v0.5.14) ⭐️ 8.0/10

SGLang v0.5.14 has been released, adding support for new models such as GLM-5.2, LiquidAI LFM2.5, and Kimi-K2.7-Code, and achieving a 5x throughput improvement for DeepSeek-V4 on NVIDIA GB300 using the new Waterfill and LPLB load-balancing methods. This release significantly improves inference efficiency for Mixture-of-Experts (MoE) models like DeepSeek-V4, leveraging the powerful GB300 GPU and novel load-balancing techniques. The 5x throughput gain at the same interactivity sets a new standard for serving large language models, benefiting AI applications that require low-latency responses. The Waterfill method handles shared-expert dispatch, while LPLB uses linear programming to balance token routing across redundant expert replicas, both integrated into DeepEP expert parallelism. Additional enhancements include an int8 checkpoint pool for linear-attention prefix-cache and NVFP4 MoE quantization for DeepSeek-V4 on Blackwell.

github · Fridge003 · Jun 26, 22:57

**Background**: Mixture-of-Experts (MoE) models use multiple specialized sub-networks (experts) to improve model capacity without proportional compute increase, but they often suffer from load imbalance across experts. Expert parallelism distributes these experts across GPUs to enhance throughput. The NVIDIA GB300 is a GPU from the Blackwell Ultra series, offering substantial performance per watt improvements over prior generations. SGLang is an open-source inference engine for large language models, focusing on high performance and flexibility.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/NVIDIA_GB300">NVIDIA GB300</a></li>

</ul>
</details>

**Tags**: `#SGLang`, `#inference`, `#DeepSeek-V4`, `#GPU`, `#LLM`

---

<a id="item-2"></a>
## [IP Crawl: A live atlas of open webcams exposes privacy risks](https://ipcrawl.com/) ⭐️ 8.0/10

IP Crawl (ipcrawl.com) is a website that aggregates publicly accessible webcams from around the world, creating a searchable live atlas of unsecured cameras connected to the internet. This project underscores the widespread security failures of IoT devices, as many webcams are shipped with default credentials and no firewall, making them accessible to anyone. It raises serious privacy concerns, as users can view live feeds from private spaces without consent. The atlas allows browsing by location and filtering, with feeds updating live. It is similar to earlier projects like Insecam, which was taken down due to ethical concerns, highlighting the ongoing nature of the problem.

hackernews · arm32 · Jun 27, 19:09 · [Discussion](https://news.ycombinator.com/item?id=48700834)

**Background**: Many consumer IP cameras, especially low-cost models, are designed to be plug-and-play but often lack security features like changing default passwords or enabling encryption. These cameras are commonly exposed to the public internet via port forwarding or UPnP without the owner's knowledge. This has been a known issue since at least 2012, as noted by community comments, but remains largely unaddressed.

<details><summary>References</summary>
<ul>
<li><a href="https://ipcrawl.com/">IP Crawl</a></li>
<li><a href="https://news.ycombinator.com/item?id=48700834">IP Crawl : living atlas of open webcams discovered on... | Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters express ethical discomfort, comparing the site to using a telescope to peer into someone's home. Some note that the problem hasn't changed since 2012, and suggest the site should notify owners of exposed cameras rather than simply displaying feeds.

**Tags**: `#security`, `#privacy`, `#IoT`, `#webcams`, `#surveillance`

---

<a id="item-3"></a>
## [DSpark: Speculative Decoding Accelerates LLM Inference](https://github.com/deepseek-ai/DeepSpec/blob/main/DSpark_paper.pdf) ⭐️ 8.0/10

DeepSeek released the DSpark paper and open-sourced two models on Hugging Face—DeepSeek-V4-Flash-DSpark and DeepSeek-V4-Pro-DSpark—that use a novel speculative decoding framework to speed up per-user generation by 60–85% over multi-token prediction (MTP). This framework significantly reduces inference latency and cost, making large LLMs more practical for real-time applications. DeepSeek's open publication of both the paper and models fosters transparency and innovation, contrasting with the closed approach of many Western AI labs. DSpark pairs a parallel draft backbone with a tiny sequential head to cut suffix decay, and uses a confidence head and load-aware scheduler that verify more tokens when GPUs are idle and fewer when busy. The two released models (Flash and Pro) are built on DeepSeek-V4 with the DSpark module integrated.

hackernews · aurenvale · Jun 27, 09:18 · [Discussion](https://news.ycombinator.com/item?id=48696585)

**Background**: Speculative decoding is an inference-time optimization for autoregressive LLMs where a smaller draft model proposes multiple candidate tokens and the larger target model verifies them in a single forward pass, preserving the target model's output distribution while cutting latency by 2–3×. DSpark builds on this concept with additional mechanisms to further improve efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>
<li><a href="https://www.marktechpost.com/2026/06/27/deepseek-releases-dspark-a-speculative-decoding-framework-that-accelerates-deepseek-v4-per-user-generation-60-85-over-mtp-1/">DeepSeek Releases DSpark , a Speculative Decoding... - MarkTechPost</a></li>

</ul>
</details>

**Discussion**: The community praised DeepSeek for pushing boundaries and publishing detailed papers, unlike many US labs. Users noted the models are already available on Hugging Face with speculated decoding built-in, and shared positive experiences using DeepSeek-V4 Pro, citing its speed, reliability, and low cost.

**Tags**: `#speculative decoding`, `#LLM inference`, `#DeepSeek`, `#AI optimization`

---

<a id="item-4"></a>
## [Meta Sued for Allegedly Surveilling Former Employee for 12 Months](https://fortune.com/2026/06/26/meta-wynn-williams-surveillance-gag-order-lawsuit-2026/) ⭐️ 8.0/10

A former Meta employee and author of "Careless People" filed a lawsuit claiming Meta conducted extensive surveillance on her for 12 months to enforce a gag order and silence her. This case highlights concerns about corporate surveillance practices and the power of tech giants to monitor former employees, potentially chilling whistleblowing and free speech. The lawsuit alleges Meta used authorized access to monitor the author's communications in an attempt to enforce a non-disparagement agreement and prevent her from speaking about her experiences.

hackernews · 1vuio0pswjnm7 · Jun 27, 21:14 · [Discussion](https://news.ycombinator.com/item?id=48701822)

**Background**: Meta, formerly Facebook, is a major technology company that has faced scrutiny over privacy and data handling. Non-disclosure agreements (NDAs) are common in corporate settings to protect trade secrets, but critics argue they can be used to silence legitimate criticism. This lawsuit alleges that Meta went beyond typical NDA enforcement by actively surveilling a former employee.

**Discussion**: Commenters expressed skepticism about Meta's actions, with one suggesting that such behavior would be exactly what Meta would do if the claims were false. Another proposed renaming the Streisand effect after the author's book. Links to the actual court complaint and an archived version were shared for transparency.

**Tags**: `#Meta`, `#surveillance`, `#lawsuit`, `#privacy`, `#tech ethics`

---