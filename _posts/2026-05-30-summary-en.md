---
layout: default
title: "Horizon Summary: 2026-05-30 (EN)"
date: 2026-05-30
lang: en
---

> From 33 items, 10 important content pieces were selected

---

1. [vLLM v0.22.0: DeepSeek V4 maturity, MRv2 advances, Rust frontend](#item-1) ⭐️ 9.0/10
2. [MCP isn't dead despite claims, shows widespread adoption](#item-2) ⭐️ 8.0/10
3. [UC faculty demand return of SAT for STEM admissions](#item-3) ⭐️ 8.0/10
4. [The Dead Economy Theory: AI's Impact on Jobs and Wealth](#item-4) ⭐️ 8.0/10
5. [Bijou64: A New Variable-Length Integer Encoding](#item-5) ⭐️ 8.0/10
6. [Anthropic's run-rate revenue hits $47 billion](#item-6) ⭐️ 8.0/10
7. [China certifies 9 domestic AI chips for government procurement](#item-7) ⭐️ 8.0/10
8. [Blue Origin's New Glenn rocket explodes during static fire test](#item-8) ⭐️ 8.0/10
9. [SpaceX Wins $4.16B US Military Satellite Tracking Contract](#item-9) ⭐️ 8.0/10
10. [Huawei's 'Tao's Law' Proposes Time Scaling for Chips](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [vLLM v0.22.0: DeepSeek V4 maturity, MRv2 advances, Rust frontend](https://github.com/vllm-project/vllm/releases/tag/v0.22.0) ⭐️ 9.0/10

vLLM v0.22.0 delivers major improvements including DeepSeek V4 model maturity with NVFP4 fused MoE and MTP speculative decoding, Model Runner V2 advances toward becoming the default runner, and an experimental Rust frontend for data-parallel serving. This release significantly enhances inference performance and model support for vLLM, a critical open-source LLM serving engine, enabling faster and more efficient deployment of state-of-the-art models like DeepSeek V4 and Qwen3. The Rust frontend is experimental and integrates with a DP Supervisor; Model Runner V2 now automatically falls back to MRv1 when a KV connector is present; DeepSeek V4 gains full CUDA graph support and a dedicated model package.

github · khluu · May 29, 10:28

**Background**: vLLM is a high-throughput, memory-efficient inference engine for large language models (LLMs). Model Runner V2 (MRv2) is a ground-up reimplementation of the core execution pipeline, aiming for better modularity and efficiency. The experimental Rust frontend is intended to improve performance for data-parallel serving scenarios.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/v0.19.0/design/moe_kernel_features/">Fused MoE Kernel Features - vLLM</a></li>
<li><a href="https://docs.vllm.ai/en/latest/design/model_runner_v2/">Model Runner V2 Design Document - vLLM</a></li>
<li><a href="https://vllm.ai/blog/mrv2">Model Runner V2: A Modular and Faster Core for vLLM | vLLM Blog</a></li>

</ul>
</details>

**Tags**: `#vLLM`, `#DeepSeek`, `#LLM inference`, `#open source`, `#machine learning`

---

<a id="item-2"></a>
## [MCP isn't dead despite claims, shows widespread adoption](https://www.quandri.io/engineering-blog/mcp-is-dead) ⭐️ 8.0/10

A blog post from Quandri challenges the narrative that MCP is dead, arguing that widespread adoption by companies building MCP servers contradicts such claims. MCP is critical for standardizing how AI agents connect to external tools and data; its continued relevance affects the entire AI tooling ecosystem and developer workflows. The post highlights that an OpenAI team member (mxstbr) noted that practically every company is building an MCP server, making the transport protocol debate irrelevant. Deferred tool loading is also mentioned as a recent update.

hackernews · nadis · May 29, 22:56 · [Discussion](https://news.ycombinator.com/item?id=48330436)

**Background**: The Model Context Protocol (MCP) is an open standard introduced by Anthropic in November 2024 to standardize how large language models (LLMs) interact with external systems like data sources and tools. It is often compared to a USB-C port for AI applications, providing a universal interface for integration.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://www.anthropic.com/news/model-context-protocol">Introducing the Model Context Protocol</a></li>
<li><a href="https://modelcontextprotocol.io/docs/getting-started/intro">What is the Model Context Protocol (MCP)? - Model Context Protocol</a></li>

</ul>
</details>

**Discussion**: Community comments reveal strong support for MCP's continued relevance. OpenAI's mxstbr emphasizes that server adoption makes MCP essential, while others note that MCP is functionally similar to JSON-RPC and serves as a necessary service discovery layer for LLMs. Some concerns about sandbox limitations and timeouts are also raised.

**Tags**: `#MCP`, `#AI agents`, `#tool use`, `#LLM APIs`, `#community discussion`

---

<a id="item-3"></a>
## [UC faculty demand return of SAT for STEM admissions](https://www.latimes.com/california/story/2026-05-27/uc-math-professors-demand-return-of-sat-for-stem-admissions) ⭐️ 8.0/10

Faculty at the University of California have publicly demanded the reinstatement of the SAT as a requirement for STEM admissions, citing severe math deficiencies among incoming students that force instructors to reteach middle-school mathematics. This debate challenges the test-optional admissions trend that gained momentum during the pandemic and could reshape how universities assess quantitative readiness in STEM fields. The faculty letter warns that preparation gaps are so severe that instructors must simultaneously teach middle-school math and advanced STEM material, and they argue that the SAT provides a standardized metric to identify students who are truly prepared.

hackernews · brandonb · May 28, 14:13 · [Discussion](https://news.ycombinator.com/item?id=48309233)

**Background**: The University of California eliminated SAT/ACT requirements in 2020 following a lawsuit and campus protests against standardized testing, citing equity concerns. The move toward test-optional admissions was widely adopted by other institutions. Critics of the SAT have argued it favors privileged students, while proponents say it remains a strong predictor of college success, especially in math-intensive fields.

**Discussion**: Commenters express mixed views: some support faculty, pointing to digital distractions in high school math and a shift from equality to equity in education; others suggest alternative systems like Italy's free but demanding model, or argue that prerequisites should be strictly enforced instead of reteaching fundamentals.

**Tags**: `#education`, `#STEM`, `#SAT`, `#math`, `#university admissions`

---

<a id="item-4"></a>
## [The Dead Economy Theory: AI's Impact on Jobs and Wealth](https://www.owenmcgrann.com/p/the-dead-economy-theory) ⭐️ 8.0/10

The article 'The dead economy theory' explores the idea that AI could render many jobs obsolete and concentrate wealth, sparking intense debate about its economic assumptions and long-term implications. This discussion is significant because it challenges optimistic AI narratives and raises urgent questions about societal restructuring, wealth inequality, and the future of labor markets. The article garnered high community engagement with 974 points and 1123 comments, highlighting deep divisions: some argue AI could enable new competition, while others note it may lead to task reallocation rather than mass unemployment.

hackernews · WillDaSilva · May 29, 15:46 · [Discussion](https://news.ycombinator.com/item?id=48324712)

**Background**: The 'dead economy theory' posits that AI automation could eliminate jobs and concentrate wealth, ultimately reducing consumer spending to B2B-only transactions. The article critiques mainstream AI discourse for overlooking systemic political economy consequences.

**Discussion**: Commenters shared diverse viewpoints: some argued that AI could enable laid-off workers to start competing firms, while others warned of a B2B-only economy if ordinary people lose income. Several commenters critiqued the article for missing economic nuances, noting that AI currently leads to task reallocation and has not significantly impacted wages.

**Tags**: `#AI`, `#economics`, `#automation`, `#labor market`, `#technology impact`

---

<a id="item-5"></a>
## [Bijou64: A New Variable-Length Integer Encoding](https://www.inkandswitch.com/tangents/bijou64/) ⭐️ 8.0/10

Ink and Switch has published Bijou64, a novel variable-length integer encoding designed for the Subduction CRDT protocol, which ensures canonical representation by eliminating redundant encodings. Bijou64 balances compactness and simplicity, offering performance gains and enhanced security against adversarial inputs, and it challenges existing encodings like LEB128 and BER-TLV in specific use cases. Bijou64 uses a length-prefixed scheme that supports the full uint64 range without an extra 10th byte, but it has a slightly larger encoding size for small numbers and faces challenges with SIMD acceleration due to its variable-length nature.

hackernews · justinweiss · May 29, 15:03 · [Discussion](https://news.ycombinator.com/item?id=48323992)

**Background**: Variable-length integer encodings (varints) represent integers using a variable number of bytes, with smaller numbers using fewer bytes. Common examples include LEB128 used in DWARF and WebAssembly, and BER-TLV used in ASN.1. Canonical encodings ensure each integer has exactly one representation, preventing ambiguity and security bugs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.inkandswitch.com/tangents/bijou64/">bijou64</a></li>
<li><a href="https://bestcadpapers.com/tips-hacks-miscellaneous/bijou64-a-variable-length-integer-encoding/">Bijou64: A variable-length integer encoding - Best CAD papers</a></li>

</ul>
</details>

**Discussion**: Commenters noted that Bijou64's design breaks down under SIMD instructions, and compared it to LEB128 and BER-TLV. Some appreciated its nicer structure for most use cases, while others highlighted the usefulness of non-canonical encodings for linking and relocation in compilers.

**Tags**: `#variable-length integer`, `#encoding`, `#data serialization`, `#compression`, `#integer encoding`

---

<a id="item-6"></a>
## [Anthropic's run-rate revenue hits $47 billion](https://simonwillison.net/2026/May/29/anthropic/#atom-everything) ⭐️ 8.0/10

Anthropic disclosed that its run-rate revenue crossed $47 billion in early May 2026, as part of its $65 billion Series H announcement, up from $30 billion in April and $14 billion in February. This explosive revenue growth validates strong enterprise demand for AI and positions Anthropic for a potential IPO, while also sparking debate about the sustainability of such rapid scaling. The run-rate revenue is an annualized projection based on the most recent month's revenue; the $47 billion figure follows a trajectory from $9 billion at end of 2025 to $14 billion in February, $30 billion in April, and $47 billion in May 2026.

rss · Simon Willison · May 29, 01:23

**Background**: Run-rate revenue is a financial metric that extrapolates a company's current monthly revenue to estimate annual revenue, assuming no changes. Anthropic is a leading AI company developing the Claude model series and competing with OpenAI. Its massive fundraising rounds (Series G at $30 billion, Series H at $65 billion) indicate investor confidence in its growth trajectory.

<details><summary>References</summary>
<ul>
<li><a href="https://corporatefinanceinstitute.com/resources/accounting/revenue-run-rate/">Revenue Run Rate - Definition, Calculation, Examples</a></li>
<li><a href="https://www.investopedia.com/terms/r/runrate.asp">Run Rate Explained: Benefits, Risks, and Business Insights</a></li>

</ul>
</details>

**Discussion**: Ed Zitron previously expressed skepticism about the $30 billion run-rate, and the author questions whether he will update his view given the higher $47 billion figure. Some readers dismiss the numbers as untrustworthy because they come from Anthropic, but the author argues that lying to investors in a fundraise would constitute securities fraud, especially with an IPO on the horizon.

**Tags**: `#AI`, `#Anthropic`, `#funding`, `#revenue`, `#business`

---

<a id="item-7"></a>
## [China certifies 9 domestic AI chips for government procurement](https://www.tomshardware.com/tech-industry/semiconductors/china-certifies-nine-domestic-ai-chips-for-government-procurement) ⭐️ 8.0/10

China's Information Security Evaluation Center has, for the first time, added an 'AI training and inference chip' category to its security certification framework, certifying 9 domestic AI processors including Huawei Ascend, Alibaba Pingtouge Zhenwu, Biren, and Haiguang, with a three-year validity. This formal certification marks a strategic push for China's AI hardware self-reliance, directly influencing government and state-owned enterprise procurement, and reshaping the global semiconductor competition landscape. Certified chips include Huawei Ascend, Alibaba Pingtouge Zhenwu, Biren, and Haiguang, while notable absentees are Cambricon and Baidu Kunlun Core; the certification is valid for three years and serves as a basis for government procurement.

telegram · zaihuapd · May 29, 08:41

**Background**: The 'Anke' (secure and reliable) procurement catalog is a Chinese government list of certified domestic IT products for state use, aimed at reducing reliance on foreign technology. With US export controls on advanced AI chips, China has accelerated development of homegrown alternatives; these certified chips target training and inference workloads critical for AI applications.

<details><summary>References</summary>
<ul>
<li><a href="https://www.doit.com.cn/p/527695.html">华 为 昇 腾 +DeepSeek：国产 AI 推理引擎的破局之战</a></li>
<li><a href="https://m.c114.com.cn/w16-1306635.html">总投资400亿元：阿里云基于“真 武 ” 芯 片 加速投产金山算力中心 - C114...</a></li>

</ul>
</details>

**Tags**: `#AI chips`, `#China`, `#semiconductor`, `#government procurement`, `#Huawei`

---

<a id="item-8"></a>
## [Blue Origin's New Glenn rocket explodes during static fire test](https://arstechnica.com/space/2026/05/blue-origins-new-glenn-rocket-just-exploded-during-a-static-fire-test/) ⭐️ 8.0/10

On May 28, 2026, Blue Origin's New Glenn heavy-lift rocket exploded during a static fire test at Cape Canaveral, destroying the entire vehicle and damaging launch pad infrastructure. The incident occurred during preparations for the NG-4 mission, which was to deploy 48 Amazon Project Kuiper satellites. This explosion significantly delays Blue Origin's return to flight and impacts NASA's Artemis program, which relies on New Glenn for lunar lander and rover missions. It also hampers Amazon's Project Kuiper satellite internet constellation deployment. The rocket's first stage, powered by seven BE-4 methane engines, experienced an anomaly during ignition, leading to a massive fireball that consumed both stages. The launch pad's lightning protection tower collapsed, and no injuries were reported.

telegram · zaihuapd · May 29, 11:08

**Background**: New Glenn is a heavy-lift launch vehicle developed by Blue Origin, designed with a partially reusable first stage and powered by seven BE-4 engines. A static fire test is a pre-launch rehearsal where the rocket's engines are briefly fired while the vehicle remains attached to the launch pad. Blue Origin was contracted by NASA to provide lander and rover services for the Artemis program, and also plans to deploy Amazon's Project Kuiper satellite constellation.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/space/2026/05/blue-origins-new-glenn-rocket-just-exploded-during-a-static-fire-test/">New Glenn was due to play a starring role in NASA's Artemis Program.</a></li>
<li><a href="https://en.wikipedia.org/wiki/New_Glenn">New Glenn - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/BE-4">BE - 4 - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#space`, `#rocketry`, `#Blue Origin`, `#NASA`, `#Artemis`

---

<a id="item-9"></a>
## [SpaceX Wins $4.16B US Military Satellite Tracking Contract](https://www.bloomberg.com/news/articles/2026-05-29/spacex-wins-4-billion-contract-for-us-golden-dome-satellites) ⭐️ 8.0/10

SpaceX has been awarded a $4.16 billion contract by the US Space Force to build a space-based tracking network for identifying and tracking foreign aircraft and missiles as part of the Golden Dome defense system. This contract positions SpaceX as a key player in US national security space architecture, and demonstrates the military's increasing reliance on commercial space capabilities for missile warning and tracking. The tracking network will integrate space sensors, communication systems, and ground processing to reduce blind spots of existing ground-based radars and aircraft sensors. SpaceX had previously participated in Golden Dome's space-based interceptor prototype development.

telegram · zaihuapd · May 30, 01:53

**Background**: The Golden Dome is a planned multi-layer missile defense system for the United States, designed to detect and intercept ballistic, hypersonic, and cruise missiles. The system aims to leverage space-based assets for persistent surveillance. The US Space Force has also awarded contracts for space-based interceptor prototypes to multiple companies.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Golden_Dome_(missile_defense_system)">Golden Dome (missile defense system) - Wikipedia</a></li>
<li><a href="https://www.airandspaceforces.com/space-force-first-contracts-golden-dome-space-based-interceptors/">Space Force Awards First Contracts for Golden Dome Interceptors</a></li>

</ul>
</details>

**Tags**: `#SpaceX`, `#military contract`, `#satellite tracking`, `#Golden Dome`, `#defense technology`

---

<a id="item-10"></a>
## [Huawei's 'Tao's Law' Proposes Time Scaling for Chips](https://t.me/zaihuapd/41648) ⭐️ 8.0/10

Huawei unveiled 'Tao's Law' at the 2026 International Conference on Circuits and Systems, advocating a shift from geometric scaling to 'time scaling' for semiconductor advancement. The company claims to have designed and mass-produced 381 chips based on this principle over the past six years, and plans to release a new Kirin mobile chip featuring logic folding in autumn 2026. As Moore's law approaches physical limits, Tao's Law offers an alternative path to improve chip performance by reducing time delays rather than shrinking transistors. This could extend the semiconductor industry's trajectory without relying solely on extreme miniaturization, potentially reshaping design strategies for decades. Tao's Law achieves multi-level co-optimization across devices, circuits, chips, and systems by reducing time constants. Huawei projects that by 2031, high-end chips based on this law could reach a transistor density equivalent to that of a 1.4nm process.

telegram · zaihuapd · May 30, 02:18

**Background**: Moore's Law, the decades-old observation that transistor counts double roughly every two years, has been sustained largely by geometric scaling—shrinking the physical size of transistors. However, this approach is hitting fundamental physical barriers as features approach atomic scales. 'Time scaling' instead focuses on reducing signal propagation delays through architectural innovations like logic folding and interconnect optimization, aiming to continue performance gains without further miniaturization.

<details><summary>References</summary>
<ul>
<li><a href="https://www.peopleapp.com/column/30052254360-500007517346">“ 韬 定 律 ”，做 时 间 的朋友_人民日报</a></li>
<li><a href="https://m.gelonghui.com/p/4928231">告别光刻机依赖？ 华为“ 韬 定 律 ”的野心与边界</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#Huawei`, `#Moore's Law`, `#chip design`, `#technology breakthrough`

---