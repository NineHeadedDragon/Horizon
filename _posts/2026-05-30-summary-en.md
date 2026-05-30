---
layout: default
title: "Horizon Summary: 2026-05-30 (EN)"
date: 2026-05-30
lang: en
---

> From 32 items, 12 important content pieces were selected

---

1. [Anthropic surpasses OpenAI in valuation](#item-1) ⭐️ 9.0/10
2. [vLLM v0.22.0 released with DeepSeek V4, MRv2, Rust frontend](#item-2) ⭐️ 8.0/10
3. [Dead Economy Theory: AI Efficiency Paradox](#item-3) ⭐️ 8.0/10
4. [Bijou64: A new varint encoding with speed and simplicity trade-offs](#item-4) ⭐️ 8.0/10
5. [California Passes 'Protect Our Games Act' for Game Preservation](#item-5) ⭐️ 8.0/10
6. [GTA 6 Developers Form Union to End Crunch](#item-6) ⭐️ 8.0/10
7. [UC Math Faculty Demand Return of SAT for STEM Admissions](#item-7) ⭐️ 8.0/10
8. [Claude Opus 4.8 Released: Performance Boost, Fast Mode Price Cut 66%](#item-8) ⭐️ 8.0/10
9. [BYD offers one-year accident liability coverage for city navigation assist](#item-9) ⭐️ 8.0/10
10. [CBSE exam grading system has critical vulnerabilities](#item-10) ⭐️ 8.0/10
11. [China Certifies 9 Domestic AI Chips for Government Procurement](#item-11) ⭐️ 8.0/10
12. [Blue Origin New Glenn Explodes During Static Fire Test](#item-12) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Anthropic surpasses OpenAI in valuation](https://www.nytimes.com/2026/05/28/technology/anthropic-tops-openai-valuation.html) ⭐️ 9.0/10

Anthropic announced a $65 billion Series H funding round, achieving a post-money valuation of $965 billion, surpassing OpenAI's estimated $852 billion valuation and becoming the highest-valued AI startup. This marks a significant shift in the AI startup landscape, as Anthropic overtakes OpenAI in valuation, reflecting intense competition and investor confidence in Anthropic's growth trajectory and enterprise adoption. Anthropic's run-rate revenue reached $47 billion earlier in May 2026, up from $30 billion in April and $14 billion in February, showcasing hypergrowth. The company is expected to file for an IPO, which would require revealing actual financials.

telegram · zaihuapd · May 29, 03:29

**Background**: Anthropic is an AI company known for its Claude models, competing with OpenAI's GPT series. Run-rate revenue is an annualized projection of current monthly revenue, often used by private companies to indicate growth. The $65B round is one of the largest in tech history.

**Discussion**: Some critics, like Ed Zitron, expressed skepticism about Anthropic's revenue claims, but others argue that the numbers are likely credible due to the risk of securities fraud if misstated to investors. The rapid run-rate growth is seen as unprecedented.

**Tags**: `#AI`, `#valuation`, `#Anthropic`, `#OpenAI`, `#funding`

---

<a id="item-2"></a>
## [vLLM v0.22.0 released with DeepSeek V4, MRv2, Rust frontend](https://github.com/vllm-project/vllm/releases/tag/v0.22.0) ⭐️ 8.0/10

vLLM v0.22.0 has been released with 459 commits from 230 contributors, featuring major hardening for DeepSeek V4, advances toward making Model Runner V2 the default, an experimental Rust frontend, batch-invariant inference with 28.9% latency improvement, and a multi-tier KV cache offloading framework. This release significantly improves vLLM's support for cutting-edge LLM architectures like DeepSeek V4 and Qwen3, while introducing performance optimizations that reduce inference latency. The experimental Rust frontend and multi-tier KV offloading demonstrate vLLM's commitment to scalability and efficiency, impacting AI infrastructure across the industry. DeepSeek V4 gained NVFP4 fused MoE support, full and piecewise CUDA graph, and MTP speculative decoding. Model Runner V2 now selects itself by default for Qwen3 dense models and includes sleep-mode weight reload, update_config, and shared KV-cache layers. The Rust frontend integration moved into the tree with a DP supervisor for data-parallel serving.

github · khluu · May 29, 10:28

**Background**: vLLM is a high-throughput and memory-efficient inference engine for large language models (LLMs), widely used in production AI serving. DeepSeek V4 is an open-weight MoE model from DeepSeek, a Chinese AI company known for cost-effective training. Model Runner V2 is a refactored execution path in vLLM aimed at improving performance and flexibility. The Rust frontend experiment explores using Rust for better performance and safety.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash">deepseek -ai/ DeepSeek - V 4 -Flash · Hugging Face</a></li>
<li><a href="https://docs.vllm.ai/en/v0.15.0/api/vllm/model_executor/layers/fused_moe/oracle/nvfp4/">vllm.model_executor.layers.fused_moe.oracle.nvfp4</a></li>

</ul>
</details>

**Tags**: `#vllm`, `#AI inference`, `#LLM`, `#DeepSeek V4`, `#Model Runner`

---

<a id="item-3"></a>
## [Dead Economy Theory: AI Efficiency Paradox](https://www.owenmcgrann.com/p/the-dead-economy-theory) ⭐️ 8.0/10

Owen McGrann's article 'The dead economy theory' proposes a paradox where AI-driven efficiency reduces the customer base by eliminating jobs, potentially leading to an economic stagnation he calls a 'dead economy'. This theory challenges the conventional assumption that AI automation will boost overall economic growth, highlighting systemic risks of demand collapse and market shrinkage. The article describes a 'turn three' scenario where companies that fire workers save costs but discover their customers were those very workers, causing revenue to stall; the extreme outcome is a fully robot economy with no human consumers.

hackernews · WillDaSilva · May 29, 15:46 · [Discussion](https://news.ycombinator.com/item?id=48324712)

**Background**: The dead economy theory builds on concepts like job displacement due to automation and aggregate demand. Historically, technological progress has created new jobs, but AI's broad applicability across sectors may cause simultaneous displacement, leaving fewer employed workers to generate demand.

**Discussion**: Commenters like Animats draw parallels to India's subsidized labor-intensive farming, suggesting similar inefficiencies are sustained politically. Others, like movpasd, praise the article for considering systemic consequences and political economy, while rootusrootus points to overcapacity in tech labor as a pre-existing issue.

**Tags**: `#AI`, `#economics`, `#automation`, `#labor`, `#technology`

---

<a id="item-4"></a>
## [Bijou64: A new varint encoding with speed and simplicity trade-offs](https://www.inkandswitch.com/tangents/bijou64/) ⭐️ 8.0/10

Bijou64 is a novel variable-length integer encoding developed for the Subduction CRDT protocol, designed to be fast and simple. However, it faces criticism for allowing non-canonical representations and being incompatible with SIMD optimization. If widely adopted, Bijou64 could outperform common varint encodings like LEB128 in certain scenarios, but non-canonicality introduces potential security vulnerabilities, and the lack of SIMD support limits its performance ceiling. This highlights the ongoing challenge of balancing encoding efficiency with correctness and hardware adaptability. The encoding uses the first byte to indicate both the length and part of the data, but it does not prevent overlong encodings, meaning the same integer can be represented in multiple ways. Community members point out that this non-canonicality mirrors issues in other varint schemes and that SIMD-friendly alternatives like vlen may be preferable.

hackernews · justinweiss · May 29, 15:03 · [Discussion](https://news.ycombinator.com/item?id=48323992)

**Background**: Variable-length integer encodings (varints) store integers using fewer bytes for smaller values, commonly used in data formats (e.g., LEB128 in WebAssembly and DWARF). Canonicality ensures each integer has a unique encoding, which is important for security and correctness; non-canonical encodings can lead to buffer overflows and parser bugs. SIMD (Single Instruction, Multiple Data) is a parallel processing technique that can accelerate encoding/decoding, but some varint formats are not designed to leverage it.

<details><summary>References</summary>
<ul>
<li><a href="https://www.inkandswitch.com/tangents/bijou64/">bijou64</a></li>
<li><a href="https://en.wikipedia.org/wiki/Canonicalization">Canonicalization - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Variable-length_encoding">Variable-length encoding - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Comments highlight a split in opinion: some argue that non-canonicality is a serious security flaw, while others note that it can be useful for applications like linker relocations where redundant representations are acceptable. There is also agreement that Bijou64's lack of SIMD support is a significant limitation for high-performance use cases.

**Tags**: `#variable-length integers`, `#encoding`, `#data representation`, `#performance`, `#Hacker News`

---

<a id="item-5"></a>
## [California Passes 'Protect Our Games Act' for Game Preservation](https://www.invenglobal.com/articles/22330/stop-killing-games-movement-gains-momentum-california-assembly-passes-game-protection-bill) ⭐️ 8.0/10

The California State Assembly passed the 'Protect Our Games Act', a bill requiring game publishers to maintain functionality of digitally sold games even after server shutdowns, with exceptions for subscription and free-to-play games. This legislation sets a precedent for digital preservation in the gaming industry, potentially forcing publishers to support offline modes or release server binaries, impacting how live-service games are designed and marketed. The bill prohibits continued sale of games rendered unusable by server termination and excludes games that are inherently playable offline indefinitely, aiming to prevent consumer loss after online shutdowns.

hackernews · TechTechTech · May 29, 19:55 · [Discussion](https://news.ycombinator.com/item?id=48328365)

**Background**: Digital game preservation has become a growing concern as many online-only games become unplayable after servers shut down. The 'Protect Our Games Act' is one of the first state-level efforts to mandate long-term playability, similar to movements like 'Stop Killing Games' that advocate for consumer rights in software ownership.

**Discussion**: Community comments show mixed reactions: some support the regulation as a consumer protection win, but others worry about loopholes like publishers creating shell companies per game to avoid liability, or the incentive shifting games toward subscription or free-to-play models to bypass the law.

**Tags**: `#gaming`, `#legislation`, `#digital preservation`, `#consumer protection`

---

<a id="item-6"></a>
## [GTA 6 Developers Form Union to End Crunch](https://rockstarintel.com/gta-6-developers-announce-rockstar-games-union/) ⭐️ 8.0/10

A group of developers working on Grand Theft Auto VI have announced the formation of a union at Rockstar Games, with demands including pay transparency, flexible working arrangements, and an end to mandatory overtime known as crunch. This marks a significant step for labor organizing in the video game industry, where crunch culture is endemic and unionization is rare. If successful, it could set a precedent for other studios and help address the systemic issue of overwork and pay disparity compared to big tech. The union is focusing on three key areas: pay transparency to address salary disparities, flexible working to improve work-life balance, and an end to crunch, which often involves unpaid 65–80 hour weeks. The announcement has generated significant discussion, with over 368 comments on the original post.

hackernews · AndrewKemendo · May 29, 15:32 · [Discussion](https://news.ycombinator.com/item?id=48324499)

**Background**: Crunch culture is widespread in video game development, where teams often work excessive overtime for months leading up to a game's release, frequently without additional pay. This practice is particularly common at large studios like Rockstar, which has faced criticism for crunch during previous titles. Unionization in the U.S. tech sector is rare due to factors like high worker mobility, anti-union employer tactics, and the ease of outsourcing or hiring H1B workers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Crunch_(video_games)">Crunch (video games) - Wikipedia</a></li>
<li><a href="https://www.aurochdigital.com/blog/2020/7/20/what-is-crunch-in-the-video-games-industry">Video game crunch: What is it and is it a problem? — Auroch Digital</a></li>

</ul>
</details>

**Discussion**: Commenters expressed support for the union and highlighted broader issues in tech: one noted the large pay gap between game developers and big tech engineers, another explained how H1B visas depress wages and enable scabbing, and a sarcastic remark pointed out that the demands are reasonable and should include competitive salaries as well.

**Tags**: `#gaming`, `#labor-union`, `#software-engineering`, `#work-culture`, `#crunch`

---

<a id="item-7"></a>
## [UC Math Faculty Demand Return of SAT for STEM Admissions](https://www.latimes.com/california/story/2026-05-27/uc-math-professors-demand-return-of-sat-for-stem-admissions) ⭐️ 8.0/10

A group of UC math faculty publicly demanded the reinstatement of SAT scores for STEM admissions, citing severe math deficits that force instructors to reteach middle-school content. This debate challenges the test-blind admissions policy adopted by UC and questions how to ensure college readiness in quantitative fields without standardized benchmarks. The faculty warned that gaps are so severe that middle-school math must be retaught alongside college material, and they argue that the SAT provides a reliable measure of mathematical preparedness.

hackernews · brandonb · May 28, 14:13 · [Discussion](https://news.ycombinator.com/item?id=48309233)

**Background**: During COVID-19, the University of California system adopted a test-blind admissions policy, removing SAT/ACT requirements. Many supporters argued it reduced biases, but critics now point to declining math readiness as a side effect.

**Discussion**: Commenters are divided: some blame digital learning distractions and equity-focused policies for the deficit, while others argue that mandatory prerequisites and placement tests—not necessarily the SAT—are the real solution.

**Tags**: `#education`, `#standardized testing`, `#STEM`, `#math deficits`, `#higher education policy`

---

<a id="item-8"></a>
## [Claude Opus 4.8 Released: Performance Boost, Fast Mode Price Cut 66%](https://www.anthropic.com/news/claude-opus-4-8) ⭐️ 8.0/10

Anthropic released Claude Opus 4.8, featuring improved coding, reasoning, and agent benchmarks, and reduced Fast Mode pricing to one-third of the previous cost. New features include adjustable effort levels in the web interface and Dynamic Workflows in Claude Code that can run hundreds of parallel subagents. This release significantly lowers the cost of using Anthropic's most capable model while adding practical features for developers, making advanced AI assistance more accessible for complex software engineering tasks. The introduction of Dynamic Workflows and adjustable effort levels enhances productivity for large-scale code migrations and other multi-file projects. Fast Mode pricing is now $10 per million input tokens and $50 per million output tokens, while the standard mode price remains unchanged. The model is 4x less likely to ignore coding errors and tends to proactively point out problems in user input.

telegram · zaihuapd · May 28, 16:50

**Background**: Claude is a series of large language models developed by Anthropic, with Opus being the flagship model for complex reasoning and coding tasks. The new version introduces Dynamic Workflows, a feature that replaces context-window orchestration with a JavaScript script that Claude generates on the fly, capable of managing up to 1,000 parallel subagents for tasks like security reviews and large migrations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techtimes.com/articles/317363/20260529/claude-code-dynamic-workflows-scripts-replace-context-windows-ultracode-automates-orchestration.htm">Claude Code Dynamic Workflows: Scripts Replace Context Windows, Ultracode Automates Orchestration</a></li>
<li><a href="https://news.pedaily.cn/202605/564627.shtml">Claude Opus 4.8问世，Anthropic估值暴涨至9650亿美元_投资界</a></li>
<li><a href="https://www.datalearner.com/benchmark-compare/popular-compare/claude-mythos-preview-vs-opus-4_6">热门大 模 型 对比：Claude Mythos Preview 与 Opus...</a></li>

</ul>
</details>

**Tags**: `#Anthropic`, `#Claude`, `#大语言模型`, `#AI发布`, `#模型升级`

---

<a id="item-9"></a>
## [BYD offers one-year accident liability coverage for city navigation assist](https://news.mydrivers.com/1/1125/1125729.htm) ⭐️ 8.0/10

BYD announced that it will provide one-year accident liability coverage for its city navigation assisted driving (NOA) systems. For new car buyers of the "Eye of God" A and B trims, BYD will cover the vehicle owner's economic losses caused by assisted driving accidents during city navigation, with no upper limit, for one year from delivery. Existing owners who upgrade to Eye of God 5.0 OTA also qualify. This policy significantly reduces consumer liability risk for ADAS failures, potentially boosting adoption of advanced city navigation features. It sets a precedent in the automotive industry for automakers to back their self-driving claims with financial guarantees, enhancing trust and accelerating deployment. Coverage applies to "Eye of God" A and B trims (high-end with lidar), while "Eye of God" C (entry-level) is available as a 12,000 RMB option. The liability coverage is unlimited in amount and lasts one year from delivery or OTA upgrade date. It specifically covers the vehicle owner's share of economic losses in accidents caused by assisted driving during city navigation.

telegram · zaihuapd · May 29, 01:03

**Background**: City navigation assisted driving (also called City NOA) is a Level 2+ function that allows the vehicle to drive autonomously on urban roads with driver supervision. BYD's "Eye of God" system ranges from basic assist (C) to advanced lidar-based (A/B). Automakers traditionally disclaim liability for ADAS failures, but BYD's move directly addresses consumer concerns about responsibility in accidents.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BYD_Auto">BYD Auto - Wikipedia</a></li>
<li><a href="https://ee.ofweek.com/2026-05/ART-8110-2801-30688887.html">智 驾 竞赛比亚迪丢王炸：兜底 城 市 NOA... - OFweek电子工程网</a></li>

</ul>
</details>

**Tags**: `#autonomous driving`, `#ADAS`, `#BYD`, `#liability`, `#automotive`

---

<a id="item-10"></a>
## [CBSE exam grading system has critical vulnerabilities](https://ni5arga.com/blog/posts/hacking-cbse/) ⭐️ 8.0/10

A researcher disclosed multiple severe security vulnerabilities in India's CBSE online exam grading system, including hardcoded master passwords, OTP validation performed on the browser side, login bypass, and password reset without verifying old credentials, which could allow grader account takeover and score manipulation. This vulnerability could compromise the integrity of exam results for millions of students, eroding trust in the centralized education system. It also underscores the critical security gaps in public infrastructure handling sensitive data. The researcher reported the issues to CERT-In in February 2025, but CBSE initially denied the existence of the vulnerabilities. After providing screenshots, screen recordings, and archived links as evidence, the researcher also discovered an SQL injection vulnerability before the site was taken offline.

telegram · zaihuapd · May 29, 05:52

**Background**: The Central Board of Secondary Education (CBSE) is a national board of education in India that conducts final exams for millions of students. Its online grading system allows examiners to remotely assess answer sheets. Security flaws in such systems can lead to unauthorized score changes, potentially affecting students' academic futures. The disclosure followed a responsible disclosure process but was complicated by CBSE's initial denial.

**Tags**: `#security vulnerability`, `#India`, `#exam system`, `#CBSE`, `#web security`

---

<a id="item-11"></a>
## [China Certifies 9 Domestic AI Chips for Government Procurement](https://www.tomshardware.com/tech-industry/semiconductors/china-certifies-nine-domestic-ai-chips-for-government-procurement) ⭐️ 8.0/10

China's information security evaluation center has for the first time added an "AI training and inference chip" category to its secure procurement catalog, certifying nine domestic AI processors for a three-year period. This move accelerates China's push for self-sufficiency in AI hardware and reduces reliance on foreign chips, potentially reshaping the global semiconductor competitive landscape. Certified chips include products from Huawei Ascend, Alibaba T-Head Zhenwu, Biren Technology, and Haiguang, while Cambricon and Baidu Kunlun are absent. The certification serves as a procurement basis for government agencies and state-owned enterprises.

telegram · zaihuapd · May 29, 08:41

**Background**: The "Anke" (secure and controllable) procurement catalog is a Chinese government list of approved domestic IT products for official use, aiming to reduce dependence on foreign technology. AI chips are key components for training and running artificial intelligence models, and China has been promoting indigenous chip development amid trade tensions with the US.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.csdn.net/huzia/article/details/130315416">自主可控目录入围产品名单(安可目录入围产品名单 服务器)-CSDN博客</a></li>

</ul>
</details>

**Tags**: `#AI chips`, `#China`, `#government procurement`, `#semiconductor`, `#Huawei`

---

<a id="item-12"></a>
## [Blue Origin New Glenn Explodes During Static Fire Test](https://arstechnica.com/space/2026/05/blue-origins-new-glenn-rocket-just-exploded-during-a-static-fire-test/) ⭐️ 8.0/10

On May 28, 2026, Blue Origin's New Glenn rocket exploded during a static fire test at Cape Canaveral's Launch Complex 36, destroying the vehicle and damaging launch infrastructure. The incident occurred during preparations for the NG-4 mission, which was set to deploy 48 Amazon Project Kuiper satellites. The explosion significantly impacts Blue Origin's launch schedule and jeopardizes NASA's Artemis program, which relies on Blue Origin's lunar lander and rover missions. This setback also delays the deployment of Amazon's Kuiper broadband constellation, affecting the competitive landscape of satellite internet. The first stage's seven BE-4 methane engines malfunctioned during ignition, causing a massive fireball that destroyed both stages and collapsed the launch pad's lightning protection tower. No injuries were reported, and the FAA and NASA are monitoring the investigation.

telegram · zaihuapd · May 29, 11:08

**Background**: A static fire test is a routine prelaunch procedure where a rocket's engines are fired at full power while the vehicle remains firmly anchored to the launch pad. New Glenn is Blue Origin's heavy-lift launch vehicle, standing 98 meters tall and designed to be partially reusable, powered by seven BE-4 engines that burn liquid methane and liquid oxygen. Blue Origin is a key contractor for NASA's Artemis program, tasked with developing the Blue Moon lander and delivering lunar payloads.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/New_Glenn">New Glenn - Wikipedia</a></li>
<li><a href="https://www.cbsnews.com/news/blue-origin-new-glenn-rocket-explodes-launchpad-florida/">Blue Origin New Glenn rocket explodes on launch pad in Florida - CBS News</a></li>
<li><a href="https://www.space.com/space-exploration/launches-spacecraft/blue-origins-new-glenn-rocket-explodes-in-massive-fireball-during-prelaunch-test">Blue Origin's New Glenn rocket explodes in massive fireball during prelaunch test | Space</a></li>

</ul>
</details>

**Tags**: `#industrial accident`, `#Blue Origin`, `#rocket explosion`, `#NASA`, `#Artemis`

---