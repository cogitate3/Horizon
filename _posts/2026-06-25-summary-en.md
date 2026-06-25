---
layout: default
title: "Horizon Summary: 2026-06-25 (EN)"
date: 2026-06-25
lang: en
---

> From 89 items, 9 important content pieces were selected

---

1. [Anthropic accuses Alibaba of illicitly extracting Claude AI model capabilities](#item-1) ⭐️ 9.0/10
2. [OpenAI unveils first custom AI inference chip 'Jalapeno'](#item-2) ⭐️ 9.0/10
3. [Qualcomm Acquires AI Startup Modular for $4B](#item-3) ⭐️ 9.0/10
4. [IBM Announces World's First Sub-1nm Chip Technology](#item-4) ⭐️ 9.0/10
5. [Cloudflare launches self-managed OAuth for all customers](#item-5) ⭐️ 8.0/10
6. [Google lowers Play Store fees after Epic settlement](#item-6) ⭐️ 8.0/10
7. [LLM-Generated Job Applications Erase Authenticity](#item-7) ⭐️ 7.0/10
8. [ICE Surveillance Tech Spending Doubles to Record Highs](#item-8) ⭐️ 7.0/10
9. [Global Operation Endgame Disrupts Cybercrime Tools](#item-9) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Anthropic accuses Alibaba of illicitly extracting Claude AI model capabilities](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 9.0/10

Anthropic has accused Alibaba of illicitly extracting capabilities from its Claude AI model through a process known as model distillation, according to a Reuters report dated June 24, 2026. This accusation highlights growing tensions in the AI industry over model security and intellectual property, and could have significant implications for international competition and AI regulation. Model distillation involves using a larger 'teacher' model to train a smaller 'student' model, which can allow competitors to quickly replicate capabilities without investing in expensive training.

hackernews · htrp · Jun 24, 19:48 · [Discussion](https://news.ycombinator.com/item?id=48664814)

**Background**: Knowledge distillation is a machine learning technique where knowledge from a large pre-trained model (teacher) is transferred to a smaller model (student), enabling efficient deployment. While common for fine-tuning, it is controversial when used to extract proprietary model capabilities without authorization.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation</a></li>
<li><a href="https://www.ibm.com/think/topics/knowledge-distillation">What is Knowledge distillation? | IBM</a></li>

</ul>
</details>

**Discussion**: Comments express mixed views: some see distillation as a standard fine-tuning practice, while others criticize Anthropic for hypocrisy given that AI models are trained on public data and that companies like Anthropic themselves used copyrighted content without permission.

**Tags**: `#AI`, `#model security`, `#distillation`, `#Anthropic`, `#competition`

---

<a id="item-2"></a>
## [OpenAI unveils first custom AI inference chip 'Jalapeno'](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI announced its first custom AI inference chip, named 'Jalapeno', developed in collaboration with Broadcom and manufactured by TSMC. The chip was designed and produced in just nine months, with parts of the design process accelerated by OpenAI's own AI models. This move reduces OpenAI's reliance on external hardware suppliers like NVIDIA, potentially lowering inference costs and improving efficiency for its AI services. It signals a broader trend where AI companies develop custom silicon to optimize performance and control their supply chains. The Jalapeno chip is specialized for inference—running trained AI models to make predictions—rather than training. It is manufactured using TSMC's advanced process, though specific technology node details were not disclosed.

hackernews · jamdesk · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: Inference chips are specialized processors designed to execute trained AI models efficiently, focusing on speed and cost per query. Custom silicon refers to purpose-built integrated circuits optimized for specific workloads, offering better performance and power efficiency than general-purpose hardware. Companies like Google (TPU) and Amazon (Trainium/Inferentia) have already adopted custom chips for AI.

<details><summary>References</summary>
<ul>
<li><a href="https://naddod.medium.com/inference-chip-guide-the-foundation-of-scalable-ai-applications-d18f2c22b36c">Inference Chip Guide: The Foundation of Scalable AI Applications | by NADDOD | Medium</a></li>
<li><a href="https://www.aboutamazon.com/news/aws/ai-chip-terms-explained">10 AI chip terms to know: GPUs, accelerators, inference, and more</a></li>
<li><a href="https://www.arm.com/glossary/custom-silicon">What is Custom Silicon – Arm®</a></li>

</ul>
</details>

**Discussion**: Some commenters expressed skepticism about OpenAI's claim that AI models accelerated chip design, calling it potentially meaningless marketing. Others highlighted that TSMC is the manufacturer (not Intel) and discussed the potential for extreme efficiency gains by hard-coding model weights into silicon, though such designs would be huge.

**Tags**: `#AI chips`, `#OpenAI`, `#Broadcom`, `#custom silicon`, `#inference`

---

<a id="item-3"></a>
## [Qualcomm Acquires AI Startup Modular for $4B](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 9.0/10

Qualcomm announced on June 24, 2026, its acquisition of Modular, an AI startup behind the Mojo programming language, for approximately $4 billion. The deal aims to bolster Qualcomm's AI capabilities and RISC-V initiatives. This acquisition marks a major strategic move for Qualcomm, positioning it to compete more aggressively in the AI hardware and software ecosystem. It also signals growing industry interest in cross-platform AI solutions and open instruction set architectures like RISC-V. Modular's Mojo language is built on MLIR and designed to combine Python-like usability with C++/Rust-level performance for AI workloads. The deal includes the entire Modular team, including co-founder Chris Lattner, known for creating LLVM and Swift.

hackernews · timmyd · Jun 24, 13:49 · [Discussion](https://news.ycombinator.com/item?id=48659798)

**Background**: Modular develops the Mojo programming language, which uses the Multi-Level Intermediate Representation (MLIR) compiler framework to target CPUs, GPUs, and other accelerators for high-performance AI. RISC-V is a free and open instruction set architecture that Qualcomm has been investing in as an alternative to ARM. This acquisition is part of Qualcomm's broader strategy to build a portfolio spanning AI compute, RISC-V cores, and edge devices.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/RISC-V_architecture">RISC-V architecture</a></li>
<li><a href="https://www.qualcomm.com/news/releases/2026/06/qualcomm-to-acquire-modular">Qualcomm to Acquire Modular</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some express disappointment that Mojo may not achieve true cross-platform status, echoing past failures like SYCL and OpenCL. Others see the acquisition as a positive move for Modular's employees and Qualcomm's strategic direction, particularly toward RISC-V. A few commenters note the irony of Modular being acquired by a hardware company given its founder's critiques of hardware vendors' AI stacks.

**Tags**: `#acquisition`, `#AI`, `#Qualcomm`, `#Modular`, `#Mojo`

---

<a id="item-4"></a>
## [IBM Announces World's First Sub-1nm Chip Technology](https://arstechnica.com/gadgets/2026/06/ibm-claims-worlds-first-sub-1-nanometer-chip-technology/) ⭐️ 9.0/10

IBM has announced the world's first sub-1 nanometer chip technology, utilizing novel nanostack transistors that stack nanosheet channels vertically to achieve greater transistor density. This breakthrough could lead to significant improvements in computing performance and energy efficiency, enabling more powerful and energy-saving processors for future devices. Compared to IBM's previous 2nm GAAFET technology, nanostack transistors are expected to be roughly 50% smaller, offering higher density and better performance per watt.

rss · Ars Technica · Jun 25, 10:00

**Background**: Sub-1nm chip technology refers to transistor features smaller than one nanometer, beyond the traditional scaling limits of silicon. Nanostack transistors are a new architecture that sequentially stacks nanosheet channels, allowing for greater density and energy savings. This advancement is critical for continuing Moore's Law and enabling future computing innovations.

<details><summary>References</summary>
<ul>
<li><a href="https://research.ibm.com/blog/what-is-a-nanostack">What is IBM's nanostack chip architecture? - IBM Research</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#chip manufacturing`, `#nanotechnology`, `#IBM`

---

<a id="item-5"></a>
## [Cloudflare launches self-managed OAuth for all customers](https://blog.cloudflare.com/oauth-for-all/) ⭐️ 8.0/10

Cloudflare announced a new self-managed OAuth service, available to all customers, simplifying authentication setup without relying on third-party providers. This move addresses a common pain point in enterprise authentication, potentially reducing complexity and cost for organizations that manage their own identity and access management. The service is built on top of Cloudflare's global network and leverages Ory Hydra for OAuth 2.0 and OpenID Connect support. It is designed to scale efficiently with minimal CPU usage.

hackernews · terryds · Jun 25, 02:18 · [Discussion](https://news.ycombinator.com/item?id=48668033)

**Background**: OAuth is an open standard for token-based authentication and authorization, commonly used for single sign-on (SSO) and API access. Managing OAuth infrastructure can be complex and error-prone, leading many organizations to seek managed solutions or build their own.

**Discussion**: The community received the announcement positively, with Ory Hydra's author praising the performance and scale. However, some users expressed skepticism about Cloudflare's history of launching projects without sustained improvement, citing examples like Cloudflare Web Analytics and Wrangler CLI.

**Tags**: `#OAuth`, `#Cloudflare`, `#Authentication`, `#Identity Management`, `#Single Sign-On`

---

<a id="item-6"></a>
## [Google lowers Play Store fees after Epic settlement](https://arstechnica.com/google/2026/06/google-starts-lowering-play-store-fees-making-good-on-epic-games-settlement/) ⭐️ 8.0/10

Google has begun reducing Play Store service fees in select markets as part of its settlement with Epic Games, with a global rollout planned for 2027. This fee reduction signals a major shift in app store economics, potentially benefiting developers worldwide and setting a precedent for antitrust-driven changes in the mobile ecosystem. The fee cuts apply to a few additional markets this year before expanding globally in 2027; specific percentage reductions were not detailed in the announcement.

rss · Ars Technica · Jun 24, 17:00

**Background**: The Epic Games settlement stems from a 2020 antitrust lawsuit over Google's Play Store policies, including its 30% commission on in-app purchases. As part of the settlement, Google agreed to lower fees and allow alternative payment systems. The broader app store fee structure has faced scrutiny globally, with similar cases against Apple.

**Tags**: `#Google Play Store`, `#Epic Games`, `#app store fees`, `#antitrust`, `#settlement`

---

<a id="item-7"></a>
## [LLM-Generated Job Applications Erase Authenticity](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 7.0/10

Tom MacWright observed that job applications increasingly feature LLM-generated content, including resumes, portfolio sites, GitHub projects, and commit messages, making applicants indistinguishable and impersonal. This trend undermines the hiring process by removing genuine signal about candidates' skills and personality, forcing recruiters to rely on less informative indicators and potentially leading to worse hiring decisions. MacWright notes that perfected, LLM-generated applications tell nothing about the person other than their use of specific tools, and that candidates have not put themselves out there or said anything true.

rss · Simon Willison · Jun 24, 18:13

**Background**: Large language models (LLMs) like GPT-4 can generate coherent text based on prompts, leading to their use in automating job applications. While this saves time, it risks homogenizing candidates and diluting the personal touch that helps employers assess fit.

**Tags**: `#ai`, `#careers`, `#hiring`, `#llm`, `#authenticity`

---

<a id="item-8"></a>
## [ICE Surveillance Tech Spending Doubles to Record Highs](https://www.theguardian.com/us-news/2026/jun/24/ice-tech-surveillance-arsenal) ⭐️ 7.0/10

A new report reveals that U.S. government spending on AI-powered surveillance tools for immigration enforcement doubled from 2024 to 2025, reaching over $310 million, and soared to a record $513 million in 2026 under the second Trump administration. This rapid escalation in surveillance spending raises serious concerns about privacy, civil liberties, and the ethical deployment of AI in law enforcement, potentially setting a precedent for other government agencies. The report analyzed ICE and CBP contracts with 11 companies providing surveillance tech, including facial recognition and spyware tools like Clearview AI and Flock Safety's license plate scanners.

rss · The Guardian US · Jun 24, 20:07

**Background**: ICE has been expanding its use of AI-powered tools for tracking immigrants, including facial recognition, mobile spyware, and data analytics from companies like Palantir. These tools have been criticized for potential civil rights violations and lack of transparency.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/us-news/2026/jun/24/ice-tech-surveillance-arsenal">‘We should be worried’: report sheds light on ICE ’s booming arsenal of...</a></li>
<li><a href="https://www.npr.org/2025/11/08/nx-s1-5585691/ice-facial-recognition-immigration-tracking-spyware">ICE agents have new tools to track and ID people : NPR</a></li>
<li><a href="https://stateofsurveillance.org/articles/surveillance/ice-surveillance-arsenal-complete-tech-stack/">ICE Surveillance Arsenal 2025: $45M Tech Stack - State of ...</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#surveillance`, `#government contracts`, `#immigration`, `#privacy`

---

<a id="item-9"></a>
## [Global Operation Endgame Disrupts Cybercrime Tools](https://arstechnica.com/security/2026/06/one-two-punch-delivered-in-global-operation-disrupts-cybercrime-assembly-line/) ⭐️ 7.0/10

In a coordinated global law enforcement operation called Operation Endgame, authorities simultaneously disrupted two widely used cybercrime tools, taking down infrastructure and arresting suspects. This operation significantly disrupts the cybercrime supply chain by removing key tools that enable malware distribution and ransomware attacks, potentially reducing global ransomware incidents. The operation involved taking down over 1,000 servers and seizing more than EUR 21.2 million in cryptocurrency across multiple phases spanning 2024 and 2025.

rss · Ars Technica · Jun 24, 21:03

**Background**: Operation Endgame is a long-running international law enforcement campaign targeting botnets and cybercrime enablers. It began in May 2024 and has included phases focusing on different malware families and dropzones. Such operations aim to dismantle the infrastructure that cybercriminals rely on to distribute malware and launch attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.europol.europa.eu/media-press/newsroom/news/end-of-game-for-cybercrime-infrastructure-1025-servers-taken-down">End of the game for cybercrime infrastructure: 1025 servers ...</a></li>
<li><a href="https://www.fbi.gov/news/press-releases/operation-endgame-coordinated-worldwide-law-enforcement-action-against-network-of-cybercriminals">Operation Endgame: Coordinated Worldwide Law Enforcement ...</a></li>
<li><a href="https://www.europol.europa.eu/media-press/newsroom/news/operation-endgame-strikes-again-ransomware-kill-chain-broken-its-source">Operation ENDGAME strikes again: the ransomware kill chain ...</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#cybercrime`, `#law enforcement`, `#tool disruption`

---