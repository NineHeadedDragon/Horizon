---
layout: default
title: "Horizon Summary: 2026-05-29 (EN)"
date: 2026-05-29
lang: en
---

> From 37 items, 12 important content pieces were selected

---

1. [vLLM v0.22.0: DeepSeek V4 hardening, MRv2 improvements, Rust frontend](#item-1) ⭐️ 9.0/10
2. [Anthropic Releases Claude Opus 4.8 with Modest Gains](#item-2) ⭐️ 9.0/10
3. [Security Flaws Found in India's CBSE Exam Grading System](#item-3) ⭐️ 9.0/10
4. [Blue Origin's New Glenn Explodes in Static Fire, Damaging NASA Plans](#item-4) ⭐️ 9.0/10
5. [Volkswagen blocks Home Assistant integration via OAuth client assertion](#item-5) ⭐️ 8.0/10
6. [Cars collect and sell driver data, privacy risks escalate](#item-6) ⭐️ 8.0/10
7. [GitHub bans researcher for posting zero-day Windows exploits](#item-7) ⭐️ 8.0/10
8. [Postgres for Durable Workflows: A New Paradigm](#item-8) ⭐️ 8.0/10
9. [SQLite Rejects AI-Generated Code with New AGENTS.md Policy](#item-9) ⭐️ 8.0/10
10. [Anthropic and OpenAI Found Product-Market Fit](#item-10) ⭐️ 8.0/10
11. [Anthropic surpasses OpenAI in valuation with $965B](#item-11) ⭐️ 8.0/10
12. [China Certifies 9 Domestic AI Chips for Government Procurement](#item-12) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [vLLM v0.22.0: DeepSeek V4 hardening, MRv2 improvements, Rust frontend](https://github.com/vllm-project/vllm/releases/tag/v0.22.0) ⭐️ 9.0/10

vLLM v0.22.0 was released with 459 commits from 230 contributors. It introduces DeepSeek V4 model hardening, Model Runner V2 advances, an experimental Rust frontend, and batch-invariant inference with 28.9% latency improvement. This release significantly enhances the performance and flexibility of vLLM, the leading open-source LLM serving framework. The DeepSeek V4 maturity and Model Runner V2 improvements will accelerate adoption in production environments, while the Rust frontend opens new possibilities for performance-critical serving. DeepSeek V4 now has a dedicated package, NVFP4 fused MoE support, full CUDA graph, and MTP speculative decoding. Model Runner V2 adds an oracle for Qwen3 dense models, sleep-mode weight reload, and shared KV-cache layers. The Rust frontend is experimental with data-parallel serving support.

github · khluu · May 29, 10:28

**Background**: vLLM is an open-source library for high-throughput LLM serving, widely used in production for its efficient memory management and batching. Model Runner is a core component responsible for executing model inference; version 2 is a modular rewrite for better performance. Speculative decoding like MTP (Multi-Token Prediction) uses auxiliary heads to draft multiple tokens per step, reducing latency. NVFP4 is a 4-bit floating point quantization format from NVIDIA for efficient MoE inference.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/stable/api/vllm/model_executor/layers/fused_moe/oracle/nvfp4/">nvfp4 - vLLM</a></li>
<li><a href="https://docs.vllm.ai/en/latest/features/speculative_decoding/mtp/">MTP (Multi-Token Prediction) - vLLM</a></li>
<li><a href="https://docs.vllm.ai/en/latest/design/model_runner_v2/">Model Runner V2 Design Document - vLLM</a></li>

</ul>
</details>

**Tags**: `#vllm`, `#LLM serving`, `#deepseek`, `#model runner`, `#rust`

---

<a id="item-2"></a>
## [Anthropic Releases Claude Opus 4.8 with Modest Gains](https://www.anthropic.com/news/claude-opus-4-8) ⭐️ 9.0/10

Anthropic has released Claude Opus 4.8, a new version of their flagship large language model that offers a modest but tangible improvement over its predecessor Opus 4.7. This release continues Anthropic's steady incremental improvements to Opus, and community benchmarks show it excels at complex coding tasks like building an RTS game. The ability to disable adaptive thinking in the web UI also addresses user frustrations, enhancing practical usability. Claude Opus 4.8 marks the third minor version bump in the Opus 4.5 family, following 4.6 and 4.7. Users have verified that adaptive thinking can now be turned off in the web UI, a feature many had requested.

hackernews · craigmart · May 28, 16:49 · [Discussion](https://news.ycombinator.com/item?id=48311647)

**Background**: Claude is a series of large language models developed by Anthropic, first released in March 2023. Opus is Anthropic's most capable model tier, designed to handle complex reasoning, coding, and creative tasks. The 4.5 sub-family introduced major capability leaps, and subsequent versions (4.6, 4.7, 4.8) have focused on incremental refinements.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model ) - Wikipedia</a></li>
<li><a href="https://claude.com/product/overview">The AI for Problem Solvers | Claude by Anthropic</a></li>
<li><a href="https://www.anthropic.com/news/claude-opus-4-6">Claude Opus 4.6 \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Community members reported positive results with Opus 4.8 in coding benchmarks, with one user noting it created a functional RTS game better than any previous model. Another user appreciated the ability to disable adaptive thinking, which had caused inconsistent output. Some commenters observed that this is the third minor version bump without dramatic improvements, comparing it to earlier major leaps.

**Tags**: `#AI`, `#machine learning`, `#Anthropic`, `#Claude`, `#LLM`

---

<a id="item-3"></a>
## [Security Flaws Found in India's CBSE Exam Grading System](https://ni5arga.com/blog/posts/hacking-cbse/) ⭐️ 9.0/10

A security researcher disclosed severe vulnerabilities in the CBSE (Central Board of Secondary Education) online exam grading system, including hardcoded passwords and client-side OTP validation, reported to CERT-In in February 2026. These flaws could allow attackers to take over grader accounts, view and modify exam scores, potentially affecting millions of students' results. This highlights critical security weaknesses in national education technology systems. The researcher provided evidence after CBSE denied the issues, including screenshots and a video. Additionally, an SQL injection vulnerability was discovered before the system went offline.

telegram · zaihuapd · May 29, 05:52

**Background**: Client-side OTP validation means the one-time password is verified in the user's browser instead of the server, allowing attackers to bypass authentication. Hardcoded passwords are static credentials embedded in the source code, making unauthorized access easy if discovered. These are common web application security flaws.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/One-time_password">One - time password - Wikipedia</a></li>
<li><a href="https://owasp.org/www-community/vulnerabilities/Use_of_hard-coded_password">Use of hard-coded password | OWASP Foundation</a></li>
<li><a href="https://valencynetworks.com/kb/resolve-client-side-otp-validation-bypass-vulnerability.html">Resolve Client Side otp Validation Bypass Vulnerability</a></li>

</ul>
</details>

**Tags**: `#security`, `#vulnerabilities`, `#web application security`, `#education technology`, `#India`

---

<a id="item-4"></a>
## [Blue Origin's New Glenn Explodes in Static Fire, Damaging NASA Plans](https://arstechnica.com/space/2026/05/blue-origins-new-glenn-rocket-just-exploded-during-a-static-fire-test/) ⭐️ 9.0/10

On May 28, 2026, Blue Origin's New Glenn heavy-lift rocket exploded during a static fire test at Cape Canaveral, destroying the vehicle and damaging the launch pad. This incident severely delays Blue Origin's return to flight and threatens NASA's Artemis program, which relies on New Glenn for lunar lander and rover missions. The explosion originated from the seven BE-4 methane engines during ignition, causing total loss of the rocket and partial collapse of the lightning protection tower. No injuries were reported.

telegram · zaihuapd · May 29, 11:08

**Background**: New Glenn is a heavy-lift rocket developed by Blue Origin, powered by seven BE-4 engines burning liquefied methane. It is intended for commercial satellite launches (such as Amazon's Project Kuiper) and NASA lunar missions. The static fire test is a standard pre-launch procedure to verify engine and vehicle systems before flight.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BE-4">BE-4 - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed shock and sympathy, with some noting the BBC video showing the rocket's side disintegrating before the main explosion. Many speculated about possible causes, such as procedural errors or manufacturing defects, and highlighted the extensive launch pad damage, predicting over a year of repairs. Others emphasized the setback for NASA's moon plans.

**Tags**: `#火箭爆炸`, `#蓝色起源`, `#新格伦`, `#NASA`, `#阿尔忒弥斯`

---

<a id="item-5"></a>
## [Volkswagen blocks Home Assistant integration via OAuth client assertion](https://github.com/robinostlund/homeassistant-volkswagencarnet/issues/967) ⭐️ 8.0/10

Volkswagen has updated its carnet API to require client assertion, an OAuth 2.0 authentication mechanism, effectively blocking third-party integrations like Home Assistant. This move restricts user access to their own vehicle data, raising concerns about corporate lock-in and contravening the spirit of the EU Data Act. It affects the open-source smart home community and highlights ongoing tensions between manufacturers and user data rights. The change requires a client assertion token, which Home Assistant's open-source integration cannot obtain without official credentials. Similar actions have been taken by other car manufacturers like BYD, which issued DMCA takedowns.

hackernews · Kwastie · May 29, 05:45 · [Discussion](https://news.ycombinator.com/item?id=48319509)

**Background**: Home Assistant is an open-source home automation platform that integrates with various devices, including vehicles via APIs. OAuth 2.0 client assertion is a secure authentication method where a client proves its identity using a signed JWT, often requiring a client secret or certificate that car manufacturers control.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.logto.io/client-assertion-in-client-authn">What is client assertion in OAuth 2.0 client authentication? · Logto blog</a></li>
<li><a href="https://datatracker.ietf.org/doc/html/rfc7521">RFC 7521 - Assertion Framework for OAuth 2.0 Client Authentication and Authorization Grants</a></li>

</ul>
</details>

**Discussion**: Community members expressed frustration and pointed to the EU Data Act as potentially applicable, with some citing similar actions by other manufacturers. They questioned the business rationale, arguing it harms loyal customers and offers little revenue benefit.

**Tags**: `#Volkswagen`, `#Home Assistant`, `#IoT`, `#Data Access`, `#Open Source`

---

<a id="item-6"></a>
## [Cars collect and sell driver data, privacy risks escalate](https://www.bbc.com/future/article/20260513-your-car-is-spying-on-you-its-about-to-get-worse) ⭐️ 8.0/10

A BBC article reports that modern vehicles extensively collect telematics data such as location, speed, and driving behavior, which automakers sell to data brokers like Verisk, often without transparent consent. This practice exposes millions of drivers to surveillance and potential misuse of personal data, yet legal penalties remain minimal compared to the profits from data sales, highlighting a critical gap in privacy regulation. For example, Hyundai received 61 cents per vehicle from Verisk, Honda 26 cents, while GM earned $20 million from data sales and faced only a $12.75 million fine in California — the largest CCPA penalty ever.

hackernews · 1vuio0pswjnm7 · May 29, 03:01 · [Discussion](https://news.ycombinator.com/item?id=48318481)

**Background**: Telematics refers to the technology in cars that collects and transmits data about vehicle operation and driver behavior. Automakers often share this data with third-party brokers without explicit driver consent, and the data can be used for insurance rating, targeted advertising, or sold to other companies. This data collection is facilitated by built-in cellular connections and sensors that have become standard in modern vehicles.

<details><summary>References</summary>
<ul>
<li><a href="https://neworleanscitybusiness.com/blog/2025/11/06/modern-cars-driver-data-privacy/">One Tech Tip: Modern cars are spying on... | New Orleans CityBusiness</a></li>
<li><a href="https://www.theglobeandmail.com/drive/technology/article-what-kind-of-data-is-my-new-car-collecting-about-me-nearly-everything/">What kind of data is my new car collecting ... - The Globe and Mail</a></li>
<li><a href="https://blog.usro.net/2024/10/why-your-car-is-spying-on-you-a-look-at-modern-telematics-and-privacy/">Why Your Car Is Spying on You: A Look at Modern Telematics and...</a></li>

</ul>
</details>

**Discussion**: Comments express frustration over the lack of consequences for automakers, with one user noting that the financial rewards from data sales far outweigh penalties. Another suggests that CEOs should publicly share their own driving data, while some discuss technical solutions like removing cellular chips or buying cars without connectivity.

**Tags**: `#privacy`, `#data collection`, `#automotive`, `#surveillance`, `#consumer rights`

---

<a id="item-7"></a>
## [GitHub bans researcher for posting zero-day Windows exploits](https://www.tomshardware.com/tech-industry/cyber-security/microsofts-github-bans-security-researcher-who-posted-zero-day-windows-exploits-because-company-ruined-their-life-expert-claims-action-is-vindictive-and-promises-further-retaliation) ⭐️ 8.0/10

GitHub banned a security researcher for posting zero-day Windows exploits, citing a violation of its terms of service. The researcher had previously reported the vulnerabilities to Microsoft but received no compensation. This incident highlights ongoing tensions between security researchers and platforms over responsible disclosure policies, potentially discouraging ethical hacking. It also raises questions about the fairness of bug bounty programs and platform censorship. The researcher, whose identity is not disclosed, posted the exploits after Microsoft failed to acknowledge or pay for the findings. GitHub, owned by Microsoft, banned the researcher, while GitLab also reportedly took similar action.

hackernews · possibilistic · May 28, 21:45 · [Discussion](https://news.ycombinator.com/item?id=48315968)

**Background**: Zero-day exploits are vulnerabilities unknown to the software vendor, making them highly valuable to attackers. Bug bounty programs incentivize researchers to report such flaws responsibly, but disputes over disclosure and compensation are common. GitHub's terms prohibit posting exploits without a 30-day disclosure window, but controversial bans can deter white-hat research.

**Discussion**: Commenters expressed frustration with the current bug bounty system, with one user sharing a past experience of being threatened with arrest for reporting a bug. Another speculated that Microsoft might regret the ban as the researcher could sell exploits elsewhere. Some questioned why both GitHub and GitLab banned the researcher, suggesting possible rule violations.

**Tags**: `#security`, `#zero-day`, `#GitHub`, `#Microsoft`, `#bug bounty`

---

<a id="item-8"></a>
## [Postgres for Durable Workflows: A New Paradigm](https://www.dbos.dev/blog/postgres-is-all-you-need-for-durable-execution) ⭐️ 8.0/10

A blog post from DBOS.dev argues that Postgres alone is sufficient for building durable, reliable workflows, challenging the need for specialized workflow engines like Temporal or Cadence. This approach could simplify system architecture by reducing dependencies on external workflow engines, leveraging the existing Postgres deployments many organizations already have, and potentially lowering operational complexity. The article references Armin Ronacher's 'absurd' project as an implementation of durable workflows on Postgres, and discusses practical trade-offs such as handling retries, backoff, timeouts, and versioning within a single database.

hackernews · KraftyOne · May 28, 18:41 · [Discussion](https://news.ycombinator.com/item?id=48313530)

**Background**: Durable workflows are systems that maintain execution state across failures, typically implemented using specialized workflow engines. Postgres is a mature relational database with strong transactional guarantees and support for features like advisory locks and LISTEN/NOTIFY, making it a potential platform for workflow orchestration.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/developers-guide-durable-workflow-execution-shubhanshu-singh-cdauc">The Developer's Guide to Durable Workflow Execution</a></li>
<li><a href="https://docs.hatchet.run/v1/durable-workflows-overview">Durable Workflows - Hatchet Documentation</a></li>
<li><a href="https://github.com/meirwah/awesome-workflow-engines">GitHub - meirwah/awesome- workflow - engines : A curated list of...</a></li>

</ul>
</details>

**Discussion**: Commenters noted comparisons to Armin Ronacher's 'absurd', shared experiences with DBOS.dev, Restate.dev, and Cloudflare Workflows, and expressed concerns that starting with Postgres for workflows may eventually lead to reimplementing features already present in dedicated workflow systems.

**Tags**: `#postgresql`, `#workflows`, `#durability`, `#distributed-systems`, `#software-architecture`

---

<a id="item-9"></a>
## [SQLite Rejects AI-Generated Code with New AGENTS.md Policy](https://simonwillison.net/2026/May/27/sqlite-agents/#atom-everything) ⭐️ 8.0/10

SQLite has added an AGENTS.md file to its repository that explicitly states it does not accept 'agentic code' (AI-generated code contributions), but welcomes bug reports and documentation patches from AI agents. The policy was strengthened by removing the word '(currently)' from the statement. As SQLite is a foundational database engine used in billions of devices, this policy sets a precedent for how critical open-source projects can manage the influx of AI-generated contributions. It highlights the tension between efficiency gains from AI agents and the need for human oversight and code quality. The AGENTS.md file also notes that SQLite does not accept pull requests without prior agreement and legal paperwork placing the contribution in the public domain. Additionally, the SQLite forum has been so overwhelmed by AI-generated bug reports that a separate 'SQLite Bug Forum' was created to handle them, with D. Richard Hipp actively resolving issues.

rss · Simon Willison · May 27, 23:44

**Background**: AGENTS.md is a file that some projects use to provide instructions specifically for AI coding agents, similar to custom instructions for tools like Codex. It defines what contributions are acceptable from agents. SQLite's AGENTS.md explicitly prohibits any code written by agents, but allows bug reports and documentation patches, reflecting a cautious approach to AI-generated code in critical infrastructure.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/May/27/sqlite-agents/">sqlite AGENTS . md | Simon Willison’s Weblog</a></li>
<li><a href="https://agents.md/">AGENTS . md</a></li>

</ul>
</details>

**Discussion**: The news has been discussed on the Datasette Discord, where Alex Garcia shared it. While not provided in detail, the overall sentiment appears supportive of SQLite's clear policy, with recognition of the growing challenge of AI-generated noise in open-source projects.

**Tags**: `#sqlite`, `#open-source`, `#AI-agents`, `#policy`, `#software-engineering`

---

<a id="item-10"></a>
## [Anthropic and OpenAI Found Product-Market Fit](https://simonwillison.net/2026/May/27/product-market-fit/#atom-everything) ⭐️ 8.0/10

Anthropic is rumored to be approaching its first profitable quarter, and both Anthropic and OpenAI have shifted enterprise pricing to API-based usage, causing some companies to see rapidly rising LLM costs. This signals that large language models have achieved sustainable product-market fit, validating the business model for AI labs and indicating that enterprise adoption is accelerating. Anthropic changed its Enterprise plan to $20/seat/month plus API pricing in November 2025, and OpenAI made a similar shift on April 2, 2026, aligning Codex pricing with token usage.

rss · Simon Willison · May 27, 16:38

**Background**: Product-market fit (PMF) describes when a product satisfies strong market demand, often indicated by profitability and growing customer spend. LLM companies like Anthropic (Claude) and OpenAI (ChatGPT/Codex) previously offered subscription plans with flat-rate fees, but are now charging enterprise customers based on actual token usage, leading to higher bills for heavy users.

<details><summary>References</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://www.anthropic.com/claude-code">Claude Code : Deep Coding at Terminal Velocity \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLMs`, `#product-market fit`, `#Anthropic`, `#OpenAI`

---

<a id="item-11"></a>
## [Anthropic surpasses OpenAI in valuation with $965B](https://www.nytimes.com/2026/05/28/technology/anthropic-tops-openai-valuation.html) ⭐️ 8.0/10

Anthropic completed a $65 billion funding round, achieving a post-money valuation of $965 billion, surpassing OpenAI's estimated $852 billion valuation. This marks a major shift in AI startup valuation leadership, indicating strong investor confidence in Anthropic's technology and commercial potential, and intensifying competition in the AI industry. Anthropic's key product is the Claude series of AI models, and the massive funding will be used for computing power, model training, and commercial expansion.

telegram · zaihuapd · May 29, 03:29

**Background**: Anthropic is an AI safety startup founded by former OpenAI employees, known for its Claude chatbot. OpenAI is the creator of GPT-4 and ChatGPT, and was previously the highest-valued AI startup. Valuations reflect market expectations for future revenue and technological leadership.

**Tags**: `#AI startups`, `#valuation`, `#Anthropic`, `#funding`

---

<a id="item-12"></a>
## [China Certifies 9 Domestic AI Chips for Government Procurement](https://www.tomshardware.com/tech-industry/semiconductors/china-certifies-nine-domestic-ai-chips-for-government-procurement) ⭐️ 8.0/10

China's Information Security Evaluation Center has added a new category for AI training and inference chips in its security certification framework, certifying nine domestic AI processors for government procurement, valid for three years. This policy shift promotes China's semiconductor self-sufficiency and reduces reliance on foreign AI chips like NVIDIA's, impacting global supply chains and accelerating domestic AI hardware development. Certified chips include Huawei Ascend, Alibaba's Pingtouge Zhenwu, Biren Technology, and Hygon; notably absent are Cambricon and Baidu Kunlun. The certification is a prerequisite for government and state-owned enterprise procurement.

telegram · zaihuapd · May 29, 08:41

**Background**: The "Anke" (secure and controllable) procurement catalog is a key mechanism for China to promote domestic IT equipment in government and state sectors, aiming to replace foreign technology. This move extends the catalog to AI chips, which are critical for national AI strategy and data security.

**Tags**: `#AI chips`, `#China`, `#government procurement`, `#semiconductors`, `#policy`

---