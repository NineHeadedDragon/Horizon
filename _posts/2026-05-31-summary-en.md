---
layout: default
title: "Horizon Summary: 2026-05-31 (EN)"
date: 2026-05-31
lang: en
---

> From 36 items, 11 important content pieces were selected

---

1. [vLLM v0.22.0: DeepSeek V4 Maturity, MRv2 Advances, Rust Frontend](#item-1) ⭐️ 9.0/10
2. [Anthropic's Run-Rate Revenue Hits $47 Billion](#item-2) ⭐️ 9.0/10
3. [Blue Origin's New Glenn Rocket Explodes in Static Fire Test](#item-3) ⭐️ 9.0/10
4. [Domain expertise is the real moat as AI lowers barriers](#item-4) ⭐️ 8.0/10
5. [Voxel Space Algorithm Explained in Retro Rendering Deep-Dive](#item-5) ⭐️ 8.0/10
6. [OpenRouter Raises $113M Series B as LLM Proxy Demand Surges](#item-6) ⭐️ 8.0/10
7. [Openrsync: OpenBSD's Clean-Room Rsync Now in macOS 15.0](#item-7) ⭐️ 8.0/10
8. [Leo's first encyclical attacks technological messianism](#item-8) ⭐️ 8.0/10
9. [How Anthropic contains Claude across products](#item-9) ⭐️ 8.0/10
10. [SpaceX wins $4.16B US military satellite missile tracking contract](#item-10) ⭐️ 8.0/10
11. [Huawei Proposes 'Tao Law': Time Scaling Replaces Geometric Shrinking in Semiconductors](#item-11) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [vLLM v0.22.0: DeepSeek V4 Maturity, MRv2 Advances, Rust Frontend](https://github.com/vllm-project/vllm/releases/tag/v0.22.0) ⭐️ 9.0/10

vLLM v0.22.0 introduces DeepSeek V4 as a mature backend with a dedicated package and NVFP4 fused MoE, advances Model Runner V2 (MRv2) toward becoming the default runner, and adds an experimental Rust frontend. This release significantly enhances vLLM's capability to serve state-of-the-art models like DeepSeek V4 with better performance and modularity, and the Rust frontend promises improved efficiency for data-parallel serving. The release includes 459 commits from 230 contributors, with batch-invariant inference achieving 28.9% end-to-end latency improvement via Cutlass FP8, and a new multi-tier KV cache offloading framework that extends beyond CPU memory.

github · khluu · May 29, 10:28

**Background**: vLLM is an open-source library for fast LLM inference and serving. Model Runner V2 (MRv2) is a ground-up re-implementation of the model runner for cleaner, more modular execution. Rust frontend is experimental and aims to replace Python components for higher performance.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/design/model_runner_v2/">Model Runner V2 Design Document - vLLM</a></li>
<li><a href="https://vllm.ai/blog/mrv2">Model Runner V2: A Modular and Faster Core for vLLM | vLLM Blog</a></li>
<li><a href="https://api-docs.deepseek.com/news/news260424">DeepSeek V4 Preview Release | DeepSeek API Docs</a></li>

</ul>
</details>

**Tags**: `#vLLM`, `#LLM inference`, `#DeepSeek V4`, `#Model Runner`, `#Rust`

---

<a id="item-2"></a>
## [Anthropic's Run-Rate Revenue Hits $47 Billion](https://simonwillison.net/2026/May/29/anthropic/#atom-everything) ⭐️ 9.0/10

Anthropic announced in its $65 billion Series H announcement that its run-rate revenue crossed $47 billion earlier this month, up from $30 billion in April 2026 and $9 billion at the end of 2025. This explosive revenue growth marks a major financial milestone for a leading AI company, indicating strong market adoption and rapid scaling that is unprecedented in any industry according to analysts. The run-rate revenue is an annualized projection calculated by multiplying the most recent month's revenue by 12; Anthropic has shared such figures in previous funding announcements, including $14 billion in February 2026.

rss · Simon Willison · May 29, 01:23

**Background**: Run-rate revenue is a non-GAAP metric used by fast-growing companies to annualize current revenue, often seen in private company disclosures. Anthropic is a leading AI safety and research company, known for its Claude model series, and has raised significant funding from investors like Google and Spark Capital.

**Discussion**: Some observers have expressed skepticism about the $47 billion figure, noting that it comes from Anthropic itself. However, the author argues that since the numbers were disclosed as part of a fundraising round, lying would constitute securities fraud, and the actual figures will likely be verified through the upcoming S-1 filing for an IPO.

**Tags**: `#Anthropic`, `#AI`, `#revenue`, `#business`, `#growth`

---

<a id="item-3"></a>
## [Blue Origin's New Glenn Rocket Explodes in Static Fire Test](https://arstechnica.com/space/2026/05/blue-origins-new-glenn-rocket-just-exploded-during-a-static-fire-test/) ⭐️ 9.0/10

On May 28, 2026, Blue Origin's New Glenn rocket exploded during a static fire test at Cape Canaveral, destroying the vehicle and damaging the launch pad. The accident occurred during NG-4 mission preparation intended to launch 48 Amazon Leo satellites. This explosion severely impacts Blue Origin's launch schedule and NASA's Artemis program, which relies on New Glenn for lunar lander and rover deliveries. It also delays Amazon's satellite internet constellation deployment. The rocket's first stage was powered by seven BE-4 methane engines, which showed anomalies during ignition. The explosion destroyed both stages and collapsed the lightning protection tower, with no injuries reported.

telegram · zaihuapd · May 29, 11:08

**Background**: New Glenn is a heavy-lift rocket developed by Blue Origin using BE-4 engines that burn liquid oxygen and methane. It is designed to compete with SpaceX's Falcon Heavy and support NASA's Artemis campaign. Amazon's Project Kuiper (now Amazon Leo) had contracted Blue Origin for multiple launches to deploy its broadband satellite constellation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BE-4">BE-4 - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Project_Kuiper">Project Kuiper</a></li>

</ul>
</details>

**Tags**: `#航天`, `#火箭爆炸`, `#蓝色起源`, `#NASA`, `#事故`

---

<a id="item-4"></a>
## [Domain expertise is the real moat as AI lowers barriers](https://www.brethorsting.com/blog/2026/05/domain-expertise-has-always-been-the-real-moat/) ⭐️ 8.0/10

A blog post argues that domain expertise, not technical skill, is the lasting competitive advantage in software development as AI tools like vibe coding lower technical barriers. This insight reframes the debate around AI's impact on software engineering, suggesting that professionals who deeply understand their domain will thrive, while those relying solely on technical skills may be vulnerable. The post highlights that as AI automates coding, the ability to define problems, validate outputs, and integrate domain knowledge becomes more critical, making domain expertise the ultimate moat.

hackernews · aaronbrethorst · May 30, 20:40 · [Discussion](https://news.ycombinator.com/item?id=48340411)

**Background**: The term 'vibe coding,' coined by Andrej Karpathy in February 2025, refers to AI-assisted programming where developers describe projects in natural language and accept generated code without deep review. This trend lowers barriers to entry for software creation, but critics warn of maintainability and security risks. Domain expertise—specialized knowledge of a particular field—enables developers to design useful, reliable systems that mere AI generation cannot replicate.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding</a></li>
<li><a href="https://grokipedia.com/page/Vibe_coding">Vibe coding</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about shifting goalposts on what matters with AI, with one noting that domain expertise is just the latest 'moat' after being a good developer, architecture, and taste. Another shared a real-world example of a poorly built vibe-coded app that failed due to lack of domain knowledge, supporting the thesis. A third questioned whether AI itself could possess comparable domain expertise.

**Tags**: `#AI`, `#domain expertise`, `#software engineering`, `#vibe coding`, `#moat`

---

<a id="item-5"></a>
## [Voxel Space Algorithm Explained in Retro Rendering Deep-Dive](https://s-macke.github.io/VoxelSpace/) ⭐️ 8.0/10

An online article provides a detailed technical explanation of the Voxel Space heightmap-based rendering algorithm that powered the 1992 game Comanche. This retrospective highlights a groundbreaking pseudo-3D technique that achieved impressive performance on limited hardware, offering valuable insights for retro-gaming enthusiasts and algorithm designers. The algorithm uses a heightmap (2D array of elevation values) rather than true volumetric voxels, rendering terrain as a set of vertical columns for efficiency.

hackernews · davikr · May 30, 14:25 · [Discussion](https://news.ycombinator.com/item?id=48336564)

**Background**: Voxels are volumetric pixels representing 3D space, but the Voxel Space technique employed heightmaps, which store elevation at each grid point. Rendering a landscape by scanning columns from a heightmap was computationally cheaper than full 3D voxel raycasting, enabling real-time flight simulators on 1990s hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://experiments.withgoogle.com/javascript-voxel-spacing">Javascript Voxel Spacing by Selim Arsever - Experiments with Google</a></li>

</ul>
</details>

**Discussion**: Commenters clarified that the technique uses heightmaps not true voxels, shared personal projects inspired by the article, and recalled the game's impressive performance on weak hardware like a 386SX.

**Tags**: `#voxels`, `#rendering`, `#algorithms`, `#retro-gaming`, `#heightmaps`

---

<a id="item-6"></a>
## [OpenRouter Raises $113M Series B as LLM Proxy Demand Surges](https://openrouter.ai/announcements/series-b) ⭐️ 8.0/10

OpenRouter, an LLM API proxy service, announced it has raised $113 million in a Series B funding round, signaling strong investor confidence in the growing demand for unified model access and billing management. This funding round validates the increasing need for infrastructure that simplifies access to multiple large language models, offering developers lower friction and better cost control. It also positions OpenRouter as a key player in the AI ecosystem, potentially accelerating adoption of diverse AI models. OpenRouter remains founder-led and founder-controlled after the raise, with the company stating its intention to continue building products for AI builders. The service charges a small surcharge (around 5%) on top of model provider costs, which has been a point of discussion in the community.

hackernews · freeCandy · May 30, 17:27 · [Discussion](https://news.ycombinator.com/item?id=48338660)

**Background**: OpenRouter is an LLM API proxy service that provides a unified interface to access and manage billing for multiple large language models from providers like OpenAI, Google, Anthropic, and others. It allows developers to try out different models without dealing with each provider's distinct API, and offers features like billing caps to prevent unexpected costs.

<details><summary>References</summary>
<ul>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>
<li><a href="https://grokipedia.com/page/openrouter">OpenRouter</a></li>

</ul>
</details>

**Discussion**: Community comments are generally positive, with users praising OpenRouter for its low friction in trying new models and its billing cap feature. However, some express skepticism about the long-term value, noting that as the model landscape stabilizes, the 5% surcharge may become less justifiable. The co-founder's reassurance of remaining founder-controlled was well received.

**Tags**: `#AI`, `#LLM`, `#funding`, `#OpenRouter`, `#startup`

---

<a id="item-7"></a>
## [Openrsync: OpenBSD's Clean-Room Rsync Now in macOS 15.0](https://github.com/kristapsdz/openrsync) ⭐️ 8.0/10

OpenBSD's openrsync, a clean-room reimplementation of the rsync utility, is now used in Apple's macOS 15.0 (Sequoia), replacing the original rsync for enhanced security and reliability. This adoption highlights the growing concern over security and code quality in the original rsync codebase, and validates OpenBSD's approach to building secure, portable tools. Users of macOS and potentially other systems benefit from a more trustworthy file synchronization tool. Openrsync is designed to be lightweight and simple, is licensed under the BSD license, and is still under development with some features missing compared to Samba's rsync. It aims for compatibility while focusing on security.

hackernews · sph · May 30, 10:51 · [Discussion](https://news.ycombinator.com/item?id=48334854)

**Background**: A clean-room implementation is a method of reverse-engineering a system without infringing copyrights, by having one team analyze the original and write a specification, then a separate team implements from the spec. OpenBSD is a security-focused Unix-like operating system known for its proactive security and integrated cryptography. Many of its components, like OpenSSH, are widely used in other systems. Openrsync follows this tradition, providing a secure alternative to the original rsync.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Openrsync">Openrsync</a></li>
<li><a href="https://en.wikipedia.org/wiki/Clean_room_implementation">Clean room implementation</a></li>

</ul>
</details>

**Discussion**: Commenters noted that openrsync has improved over time but still lacks some features like creating remote files with certain paths. Others mentioned the project's origin as part of an RPKI validator, and that a Go implementation also exists. Overall sentiment is positive, especially given recent regressions in the original rsync codebase due to 'vibe-coded' commits.

**Tags**: `#rsync`, `#OpenBSD`, `#security`, `#macOS`, `#open-source`

---

<a id="item-8"></a>
## [Leo's first encyclical attacks technological messianism](https://www.economist.com/europe/2026/05/28/leos-first-encyclical-attacks-technological-messianism) ⭐️ 8.0/10

Pope Leo released his first encyclical, strongly criticizing technological messianism—the belief that technology, especially AI, can solve all human problems and replace ethical judgment. This encyclical challenges the dominant narrative of tech companies like OpenAI and Anthropic, sparking a global debate on who should control technology: technologists, governments, or religious institutions. The encyclical is Pope Leo's first major document and focuses on the risks of AI replacing human decision-making. It warns against treating AI as a god and calls for ethical guardrails.

hackernews · 1vuio0pswjnm7 · May 30, 10:30 · [Discussion](https://news.ycombinator.com/item?id=48334710)

**Background**: Technological messianism is the belief that technology will save humanity from all problems, often seen in AI hype. The Vatican has long engaged with AI ethics, hosting meetings with tech leaders like Dario Amodei.

<details><summary>References</summary>
<ul>
<li><a href="https://www.biomedima.org/techno-messianism/">Techno- Messianism | BioMedima</a></li>

</ul>
</details>

**Discussion**: Comments reference Peter Thiel's list of antichrists, with some suggesting he now includes AI CEOs. Others debate whether technologists, governments, or religious leaders should control AI, with one commenter accusing AI CEOs of 'psychosis' for treating LLMs as divine.

**Tags**: `#technology`, `#ethics`, `#AI`, `#religion`, `#society`

---

<a id="item-9"></a>
## [How Anthropic contains Claude across products](https://simonwillison.net/2026/May/30/how-we-contain-claude/#atom-everything) ⭐️ 8.0/10

Anthropic published a comprehensive blog post detailing the sandboxing techniques used across Claude.ai, Claude Code, and Claude Cowork, including gVisor, Seatbelt, Bubblewrap, and full VMs. This transparency addresses a common lack of documentation in AI sandboxing, helping developers and users understand the security boundaries of Claude agents and build trust in the system. Claude.ai uses Google's gVisor user-space sandbox, Claude Code uses Apple's Seatbelt on macOS and Bubblewrap on Linux, and Claude Cowork runs a full VM (Apple Virtualization on macOS, HCS on Windows). The post also describes a previously missed exfiltration vector via the /v1/files API endpoint.

rss · Simon Willison · May 30, 21:36

**Background**: Sandboxing is a security technique that isolates applications to limit the damage they can cause if compromised. For AI agents like Claude, sandboxing prevents unauthorized access to the host system, credentials, or data. gVisor is an open-source container sandbox by Google that implements system calls in userspace. Seatbelt is a macOS kernel extension for restricting process capabilities. Bubblewrap is a lightweight Linux sandboxing tool used by Flatpak. Full VMs provide hardware-level isolation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GVisor">gVisor - Wikipedia</a></li>
<li><a href="https://github.com/containers/bubblewrap">GitHub - containers/bubblewrap: Low-level unprivileged sandboxing tool used by Flatpak and similar projects · GitHub</a></li>
<li><a href="https://theapplewiki.com/wiki/Dev:Seatbelt">Dev:Seatbelt - The Apple Wiki</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#sandboxing`, `#Anthropic`, `#Claude`, `#security`

---

<a id="item-10"></a>
## [SpaceX wins $4.16B US military satellite missile tracking contract](https://www.bloomberg.com/news/articles/2026-05-29/spacex-wins-4-billion-contract-for-us-golden-dome-satellites) ⭐️ 8.0/10

SpaceX has been awarded a $4.16 billion contract by the U.S. Space Force to build a space-based tracking network for identifying and tracking foreign aircraft and missiles as part of the Golden Dome defense plan. This contract places SpaceX at the center of a major U.S. defense initiative aimed at countering advanced missile threats, particularly hypersonic missiles, by reducing blind spots that ground-based systems suffer from. The space-based network will integrate space sensors, communication systems, and ground processing capabilities. SpaceX had previously participated in the development of space-based interceptor prototypes for Golden Dome and joined a multi-company alliance for the program's underlying software.

telegram · zaihuapd · May 30, 01:53

**Background**: The Golden Dome is a planned multi-layer missile defense system for the United States, intended to detect and destroy ballistic, hypersonic, and cruise missiles. Current U.S. missile warning satellites were designed for predictable ballistic trajectories and struggle to effectively track hypersonic missiles that maneuver unpredictably at five times the speed of sound. The Space Development Agency is buying and launching a network of hundreds of missile-tracking and communications satellites.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Golden_Dome_(missile_defense_system)">Golden Dome (missile defense system) - Wikipedia</a></li>
<li><a href="https://www.bbc.com/news/articles/cqxp27j1xyjo">Trump's ' Golden Dome ' will cost $1.2tn and might not stop all-out...</a></li>
<li><a href="https://arstechnica.com/space/2025/07/pentagon-may-put-spacex-at-the-center-of-a-sensor-to-shooter-targeting-network/">Pentagon may put SpaceX at the center of... - Ars Technica</a></li>

</ul>
</details>

**Tags**: `#SpaceX`, `#defense`, `#satellites`, `#military`, `#space technology`

---

<a id="item-11"></a>
## [Huawei Proposes 'Tao Law': Time Scaling Replaces Geometric Shrinking in Semiconductors](https://t.me/zaihuapd/41648) ⭐️ 8.0/10

At the 2026 International Symposium on Circuits and Systems (ISCAS) in Shanghai, Huawei formally introduced the 'Tao Law' ('τ law'), which proposes 'time scaling' as a new guiding principle for semiconductor evolution, replacing traditional geometric scaling based on process node shrinking. This represents a potential paradigm shift in the semiconductor industry, as it offers a path to continue performance gains without relying on extreme ultraviolet (EUV) lithography or ever-smaller nanometer nodes, which are approaching physical limits. If validated, it could reshape competitive dynamics and reduce dependence on advanced manufacturing equipment. Over the past six years, Huawei has already designed and mass-produced 381 chip models based on the Tao Law, and this autumn it plans to release a new Kirin mobile chip using 'logic folding' technology. Huawei's long-term goal is to achieve a transistor density equivalent to a 1.4nm process by 2031.

telegram · zaihuapd · May 30, 02:18

**Background**: Traditional semiconductor advancement follows Moore's Law and Dennard scaling, which rely on shrinking transistor dimensions (geometric scaling) to increase density and performance. However, as physical limits approach, further shrinkage becomes increasingly difficult and expensive. The Tao Law shifts the focus from reducing feature size to reducing the time constant τ (tau) across the entire system stack—from transistors to data center workloads—using design innovations like logic folding to compress signal propagation delays.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnblogs.com/qiniushanghai/p/20166392">华为韬（τ）定律：用"时间缩微"重写半导体演进规则（2026） - 七牛云行业应用 - 博客园</a></li>
<li><a href="https://www.sohu.com/a/1027841484_121123901">华为韬定律：多层电子系统的时间缩放理论（附下载）_晶体管_Dennard_半导体</a></li>
<li><a href="https://m.thepaper.cn/newsDetail_forward_33228813">究竟｜“韬定律”将如何影响半导体产业演进路径</a></li>

</ul>
</details>

**Tags**: `#半导体`, `#华为`, `#摩尔定律`, `#芯片设计`

---