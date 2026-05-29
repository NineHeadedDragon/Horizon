---
layout: default
title: "Horizon Summary: 2026-05-29 (EN)"
date: 2026-05-29
lang: en
---

> From 28 items, 11 important content pieces were selected

---

1. [Anthropic raises $65B in Series H at $965B valuation](#item-1) ⭐️ 10.0/10
2. [Anthropic Releases Claude Opus 4.8, Teases Mythos Model](#item-2) ⭐️ 8.0/10
3. [Postgres Durable Workflow Solutions Under Debate](#item-3) ⭐️ 8.0/10
4. [YouTube Automatically Labels AI-Generated Videos](#item-4) ⭐️ 8.0/10
5. [SQLite AGENTS.md Rejects AI Agent Code Contributions](#item-5) ⭐️ 8.0/10
6. [Anthropic and OpenAI Found Product-Market Fit, Says Willison](#item-6) ⭐️ 8.0/10
7. [Nvidia CEO: We've effectively abandoned China AI chip market](#item-7) ⭐️ 8.0/10
8. [Qualcomm-ByteDance AI Chip Deal for Custom ASICs](#item-8) ⭐️ 8.0/10
9. [Sony Bravia 9 II and 7 II: First Consumer TVs with Independent RGB LED Backlight](#item-9) ⭐️ 8.0/10
10. [BYD launches 4nm autonomous driving chip Xuanji A3](#item-10) ⭐️ 8.0/10
11. [US DOJ Subpoenas Reddit and X for Anonymous ICE Critics' Identities](#item-11) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Anthropic raises $65B in Series H at $965B valuation](https://www.anthropic.com/news/series-h) ⭐️ 10.0/10

Anthropic announced a $65 billion Series H funding round at a $965 billion post-money valuation, and reported a run-rate revenue of $47 billion as of early May 2026. This funding round makes Anthropic the highest-valued private AI company, surpassing OpenAI in both revenue and valuation, signaling a major shift in the AI competitive landscape. The $47 billion run-rate revenue is self-reported and represents annualized revenue based on recent growth trends. The company previously reported $30 billion run-rate in April 2026, showing rapid acceleration.

hackernews · meetpateltech · May 28, 18:09 · [Discussion](https://news.ycombinator.com/item?id=48313048)

**Background**: Run-rate revenue is an extrapolation of short-term revenue to estimate annual performance, often used by high-growth companies. Anthropic develops the Claude AI assistant and competes directly with OpenAI's ChatGPT. The Series H round is one of the largest private fundraising rounds in history, reflecting investor confidence in AI.

**Discussion**: Community comments expressed amazement at the valuation, with some questioning the use of run-rate revenue. Others noted that Anthropic has surpassed OpenAI, making OpenAI appear vulnerable. There was also discussion about the trend of companies waiting for trillion-dollar valuations before going public.

**Tags**: `#AI`, `#funding`, `#Anthropic`, `#valuation`, `#OpenAI`

---

<a id="item-2"></a>
## [Anthropic Releases Claude Opus 4.8, Teases Mythos Model](https://www.anthropic.com/news/claude-opus-4-8) ⭐️ 8.0/10

Anthropic released Claude Opus 4.8, a modest but tangible improvement over its predecessor, and announced Project Glasswing, previewing a new 'Mythos-class' model for cybersecurity use with select organizations. This release signals Anthropic's continued incremental refinement of its frontier models, while the Mythos preview hints at a potential breakthrough in AI-driven cybersecurity, though safety concerns delay general release. Opus 4.8 allows users to disable adaptive thinking in the web UI, a feature requested by the community. The Mythos Preview is capable of identifying and exploiting zero-day vulnerabilities in major operating systems and web browsers when directed by a user.

hackernews · craigmart · May 28, 16:49 · [Discussion](https://news.ycombinator.com/item?id=48311647)

**Background**: Anthropic's Claude model family includes tiers like Sonnet and Opus, with Opus being the flagship. The Opus 4.5 lineage has seen several minor updates (4.6, 4.7, 4.8) with modest gains. Project Glasswing is a cybersecurity initiative leveraging advanced AI to secure critical software infrastructure, with Mythos being a new, more capable frontier model not yet publicly released.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing : Securing critical software for the AI era \ Anthropic</a></li>
<li><a href="https://www.bbc.com/news/articles/crk1py1jgzko">What is Anthopic's Claude Mythos and what risks does it pose?</a></li>
<li><a href="https://red.anthropic.com/2026/mythos-preview/">Claude Mythos Preview \ red.anthropic.com</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some appreciate the modest improvements and the ability to disable adaptive thinking, while others criticize the slow pace of capability gains. There is excitement about the Mythos model but also concern about its safety implications.

**Tags**: `#AI`, `#Anthropic`, `#Claude`, `#model release`, `#Project Glasswing`

---

<a id="item-3"></a>
## [Postgres Durable Workflow Solutions Under Debate](https://www.dbos.dev/blog/postgres-is-all-you-need-for-durable-execution) ⭐️ 8.0/10

A blog post explores building durable workflows on Postgres, sparking community debate comparing DBOS, Temporal, River, and Armin Ronacher's absurd implementation. This debate helps developers choose the right durable workflow solution, balancing simplicity, scalability, and cost while leveraging Postgres as the backbone. DBOS requires a paid component (Conductor) for scaling and recovery; River lacks a dead-letter queue in its free version; absurd is a simple, Postgres-only implementation by Flask creator Armin Ronacher.

hackernews · KraftyOne · May 28, 18:41 · [Discussion](https://news.ycombinator.com/item?id=48313530)

**Background**: Durable workflows ensure a series of steps complete exactly once despite failures. Traditional solutions like Temporal require separate services, while newer tools like DBOS, River, and absurd embed durability directly into Postgres, simplifying the stack.

<details><summary>References</summary>
<ul>
<li><a href="https://lucumr.pocoo.org/2025/11/3/absurd-workflows/">Absurd Workflows: Durable Execution With Just Postgres | Armin Ronacher's Thoughts and Writings</a></li>
<li><a href="https://riverqueue.com/">River - Fast, reliable background jobs in Go</a></li>
<li><a href="https://www.dbos.dev/">DBOS | Durable Workflow Orchestration</a></li>

</ul>
</details>

**Discussion**: Community members share experiences and concerns: one user finds DBOS's paid scaling a dealbreaker, another flags River's missing DLQ as a trap, while others praise absurd's simplicity and express interest in comparing these tools in real-world use.

**Tags**: `#postgres`, `#durable workflows`, `#queue processing`, `#temporal`, `#software engineering`

---

<a id="item-4"></a>
## [YouTube Automatically Labels AI-Generated Videos](https://blog.youtube/news-and-events/improving-ai-labels-viewers-creators/) ⭐️ 8.0/10

YouTube has begun using automated detection systems to label AI-generated and synthetic content, requiring creators to disclose such material or face labels applied by the platform. This policy is significant because it increases transparency for viewers, helping them identify potentially misleading AI content, and sets a precedent for other platforms to follow in regulating synthetic media. The automated labels are applied to videos that realistically depict events or people that never occurred, with creators able to appeal incorrect tags; the feature initially rolls out on mobile and tablet devices.

hackernews · nopg · May 27, 20:00 · [Discussion](https://news.ycombinator.com/item?id=48299753)

**Background**: In March 2025, YouTube introduced a policy requiring creators to disclose when their content is altered or synthetic, including AI-generated material. Labels appear in the video description. Now, YouTube is expanding this with automated detection to catch non-disclosed AI content, leveraging technology similar to third-party AI video detectors.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.youtube/news-and-events/disclosing-ai-generated-content/">How we're helping creators disclose altered or synthetic content - YouTube Blog</a></li>
<li><a href="https://support.google.com/youtube/answer/14328491?hl=en&co=GENIE.Platform=Android">Disclosing use of altered or synthetic content - Android - YouTube Help</a></li>
<li><a href="https://www.plataformamedia.com/en/2026/05/27/youtube-automatic-ai-detection-content-labeling/">YouTube begins automatically labeling AI-generated content</a></li>

</ul>
</details>

**Discussion**: Commenters largely welcome the move, noting that vulnerable groups like children and seniors are often victimized by AI-generated content, and that disclosures are currently hard to find. Some question whether the labels will apply to AI music and express skepticism about the effectiveness of automated detection.

**Tags**: `#AI`, `#YouTube`, `#Content Moderation`, `#Platform Policy`, `#Digital Media`

---

<a id="item-5"></a>
## [SQLite AGENTS.md Rejects AI Agent Code Contributions](https://simonwillison.net/2026/May/27/sqlite-agents/#atom-everything) ⭐️ 8.0/10

SQLite added an AGENTS.md file that explicitly states it does not accept agentic code contributions, and removed the word 'currently' to strengthen the rejection. The project also split AI-generated bug reports into a separate forum due to overwhelming volume. This marks one of the first clear policy statements from a major open-source project against AI agent contributions, setting a precedent for others. It highlights the growing tension between AI-assisted development and traditional open-source governance. The AGENTS.md states SQLite does not accept pull requests without prior agreement and legal paperwork, but human developers may review proof-of-concept patches. Bug reports with reproducible test cases from agents are accepted, and the new SQLite Bug Forum handles AI-generated submissions.

rss · Simon Willison · May 27, 23:44

**Background**: Agentic coding refers to AI systems that autonomously plan, write, test, and modify code with minimal human intervention. Open-source projects like SQLite, which rely on human craftsmanship and strict licensing, face challenges from AI agents that may produce low-quality or legally ambiguous contributions. Many projects are now establishing explicit policies for AI contributions.

<details><summary>References</summary>
<ul>
<li><a href="https://cloud.google.com/discover/what-is-agentic-coding">What is agentic coding? How it works and use cases | Google Cloud</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-coding">What is Agentic Coding? | IBM</a></li>
<li><a href="https://www.linuxfoundation.org/blog/todo-group-launches-new-working-group-on-agentic-ai-to-empower-open-source-program-offices">TODO Group Launches New Working Group on Agentic AI to...</a></li>

</ul>
</details>

**Discussion**: The news was shared by Alex Garcia on the Datasette Discord, likely sparking discussion. Given the SQLite forum's move to split AI bug reports, the community sentiment appears to be mixed—some appreciate the clarity, while others may see it as restrictive.

**Tags**: `#sqlite`, `#open-source policy`, `#AI-generated code`, `#software engineering`, `#agent contributions`

---

<a id="item-6"></a>
## [Anthropic and OpenAI Found Product-Market Fit, Says Willison](https://simonwillison.net/2026/May/27/product-market-fit/#atom-everything) ⭐️ 8.0/10

Simon Willison argues that Anthropic and OpenAI have achieved product-market fit, citing rumors of Anthropic's first profitable quarter and enterprises surprised by high LLM API bills. This indicates that AI companies are moving from experimentation to sustainable revenue, with enterprise customers willing to pay full API prices for coding agents, validating the business model. Anthropic and OpenAI have shifted enterprise plans to per-seat plus API pricing, making heavy usage costly; Willison estimates his personal usage would cost $2,180 at API prices but he pays only $200 for subscriptions.

rss · Simon Willison · May 27, 16:38

**Background**: Product-market fit refers to a product satisfying strong market demand. Claude Code by Anthropic and OpenAI's Codex are AI coding agents used by developers. The shift to API-based pricing in enterprise plans reflects growing usage and willingness to pay.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**Tags**: `#AI Industry`, `#Product-Market Fit`, `#Anthropic`, `#OpenAI`, `#LLM Economics`

---

<a id="item-7"></a>
## [Nvidia CEO: We've effectively abandoned China AI chip market](https://t.me/zaihuapd/41609) ⭐️ 8.0/10

Nvidia CEO Jensen Huang stated that the company has essentially given up on the Chinese AI chip market due to US export restrictions, ceding the market to local competitors like Huawei. He told investors not to expect any licenses for selling advanced chips in China. This marks a major shift in the global AI chip landscape, as China was a significant revenue source for Nvidia, and its exit strengthens domestic players like Huawei. It highlights the increasing impact of US-China tech decoupling on the semiconductor industry. The Chinese market previously accounted for at least 20% of Nvidia's data center revenue. In April 2025, the Trump administration required licenses for chip exports to China, effectively excluding Nvidia's H20 and other advanced chips. Nvidia is now focusing on supply chain expansion and an $80 billion stock buyback.

telegram · zaihuapd · May 28, 03:03

**Background**: Since October 2022, the US has imposed export controls on advanced AI chips to China, initially banning Nvidia's A100 and H100. Subsequent rules targeted lower-performance chips like the H20. In response, Chinese companies like Huawei have developed their own AI chips, such as the Ascend 910B and 920, which are increasingly used for training large models. In February 2026, Zhipu AI trained GLM-5 entirely on Huawei's Ascend 910B chips using the MindSpore framework, demonstrating the growing capability of China's domestic AI ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tomshardware.com/pc-components/gpus/huawei-introduces-the-ascend-920-ai-chip-to-fill-the-void-left-by-nvidias-h20">Huawei introduces the Ascend 920 AI chip to fill the... | Tom's Hardware</a></li>
<li><a href="https://thamizhelango.medium.com/mindspore-zhipu-ai-huawei-ascend-how-china-built-a-frontier-ai-model-without-a-single-nvidia-68403d92cedb">MindSpore, Zhipu AI & Huawei Ascend : How China Built... | Medium</a></li>
<li><a href="https://www.rand.org/pubs/commentary/2025/02/deepseeks-lesson-america-needs-smarter-export-controls.html">DeepSeek's Lesson: America Needs Smarter Export Controls | RAND</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#AI Chips`, `#Export Controls`, `#China`, `#Huawei`

---

<a id="item-8"></a>
## [Qualcomm-ByteDance AI Chip Deal for Custom ASICs](https://t.me/zaihuapd/41616) ⭐️ 8.0/10

Qualcomm has reportedly partnered with ByteDance on custom AI ASIC chips, with ByteDance planning to purchase millions of chips to support its AI services. The deal will also help ByteDance convert its internal chip designs into mass-producible semiconductor products. This partnership signals a major investment in AI infrastructure by ByteDance and highlights Qualcomm's expansion into custom AI accelerators. It could intensify competition among AI chip providers and drive further adoption of specialized ASICs for large-scale AI workloads. The report is based on anonymous sources and has not been confirmed by Qualcomm or ByteDance. Qualcomm previously announced in April that it would deliver its first ASIC to a hyperscale cloud provider this year.

telegram · zaihuapd · May 28, 07:09

**Background**: An application-specific integrated circuit (ASIC) is a custom chip designed for a specific task, offering superior performance and energy efficiency compared to general-purpose CPUs or GPUs. In AI, ASICs are increasingly used to accelerate inference and training, with leading-edge designs often using advanced nodes like 4nm or 3nm. ByteDance, the parent of TikTok, operates large-scale AI services that require massive compute resources, making custom ASICs an attractive option.

<details><summary>References</summary>
<ul>
<li><a href="https://www.arm.com/glossary/asic">What is ASIC? - ASIC Cost</a></li>
<li><a href="https://tspasemiconductor.substack.com/p/the-rise-of-asic-custom-chips-becoming">The Rise of ASIC: Custom Chips Becoming a Key Trend</a></li>
<li><a href="https://www.marvell.com/products/custom-asic.html">Custom ASICs | Pushing the boundaries of AI with advanced silicon technologies and custom multi-chip systems - Marvell</a></li>

</ul>
</details>

**Tags**: `#AI hardware`, `#ASIC`, `#Qualcomm`, `#ByteDance`, `#semiconductors`

---

<a id="item-9"></a>
## [Sony Bravia 9 II and 7 II: First Consumer TVs with Independent RGB LED Backlight](https://www.flatpanelshd.com/news.php?subaction=showfull&amp;id=1779897602) ⭐️ 8.0/10

Sony has launched the Bravia 9 II and Bravia 7 II, the first consumer TVs to feature independent RGB LED backlight technology called 'True RGB', achieving peak brightness near 4000 nits and over 90% BT.2020 color gamut coverage. This breakthrough combines the brightness of Mini-LED with the color purity of OLED, offering superior color volume and accuracy, which could set a new standard for high-end LCD TVs and challenge both Mini-LED and OLED technologies. The new TVs come in sizes from 50 to 115 inches, with the 115-inch model being the largest Sony TV ever. However, high-end models still only include two HDMI 2.1 ports and do not support Dolby Vision 2.0.

telegram · zaihuapd · May 28, 12:15

**Background**: Traditional LCD TVs use a white LED backlight with color filters, while Mini-LED backlights improve local dimming but still use white LEDs. Independent RGB LED backlights use separate red, green, and blue LEDs to directly control color, resulting in purer colors and wider gamut. Sony first experimented with this technology in 2004 with the QUALIA 005, but it was expensive and niche. The new 'True RGB' system aims to bring this technology to mainstream consumer TVs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ascension6.com/article/122.html">【新葡京】密度 LED 显示系统值得等待！ 新葡京网上赌场索尼 RGB ...</a></li>
<li><a href="https://tieba.baidu.com/p/5946775886">有大佬解释下 BT .709和 2020 吗【电视吧】_百度贴吧</a></li>

</ul>
</details>

**Tags**: `#display technology`, `#TV`, `#Sony`, `#consumer electronics`, `#backlight`

---

<a id="item-10"></a>
## [BYD launches 4nm autonomous driving chip Xuanji A3](https://finance.sina.com.cn/roll/2026-05-28/doc-inhznenn1371824.shtml) ⭐️ 8.0/10

BYD unveiled the Xuanji A3, a 4nm autonomous driving chip, during its 'Dare to Act' intelligent strategy launch on May 28, 2026. The chip has entered mass production and supports L3 and L4 autonomous driving, with three chips delivering over 2100 TOPS of total computing power. This announcement marks BYD's full-chain control over assisted driving hardware, following the trend of Chinese automakers developing custom chips. It could accelerate the adoption of L3/L4 autonomous driving in mass-market vehicles and intensify competition in the EV chip space. Each Xuanji A3 chip delivers 700 TOPS, and when combined with BYD's self-developed algorithms, the computing power utilization is claimed to be doubled. BYD also revealed it has developed over 2000 chip products and operates five wafer fabrication plants.

telegram · zaihuapd · May 28, 13:01

**Background**: Autonomous driving chips are specialized processors that handle sensor data and decision-making for self-driving cars. TOPS (trillions of operations per second) measures chip performance; higher TOPS enables more advanced driving assistance features. BYD, a leading Chinese EV maker, has been investing heavily in vertical integration, including chip design, to reduce reliance on external suppliers.

<details><summary>References</summary>
<ul>
<li><a href="https://cnevpost.com/2026/05/28/byd-unveils-4nm-smart-driving-chip-xuanji-a3/">BYD unveils 4nm smart driving chip , deepening vertical... - CnEVPost</a></li>
<li><a href="https://electrek.co/2026/05/28/byd-reveals-chinas-first-in-house-4nm-smart-driving-chip/">BYD reveals China's first in-house 4nm smart driving chip</a></li>
<li><a href="https://thenextweb.com/news/byd-has-built-chinas-first-4nm-driving-chip-and-its-putting-lidar-on-a-10000-car">BYD unveils China's first 4nm driving chip and expands God's Eye</a></li>

</ul>
</details>

**Tags**: `#BYD`, `#autonomous driving`, `#chip`, `#semiconductor`, `#AI`

---

<a id="item-11"></a>
## [US DOJ Subpoenas Reddit and X for Anonymous ICE Critics' Identities](https://www.bloomberg.com/news/articles/2026-05-28/trump-s-doj-ramps-up-probes-of-anonymous-ice-critics-with-x-reddit-subpoenas) ⭐️ 8.0/10

The U.S. Department of Justice has issued subpoenas to Reddit and X demanding the real names, addresses, and bank information of at least two anonymous users who criticized ICE, escalating from administrative to grand jury subpoenas. This action threatens online anonymity and free speech, as it targets government critics, potentially chilling dissent. It also raises concerns about government overreach and the expanding use of grand jury subpoenas against anonymous internet users. The subpoenas have been escalated to grand jury subpoenas, indicating a criminal investigation, but the users have not been informed of any specific charges. The users have retained legal counsel to challenge the subpoenas in court, and a judge is currently reviewing motions to quash them.

telegram · zaihuapd · May 28, 14:22

**Background**: In U.S. law, an administrative subpoena is issued by a federal agency without court approval, while a grand jury subpoena is issued as part of a criminal investigation and is generally more difficult to challenge. The escalation from administrative to grand jury subpoena suggests the DOJ intends to pursue criminal charges against the anonymous critics. The case is pending before a federal judge who will decide whether to quash the subpoenas.

<details><summary>References</summary>
<ul>
<li><a href="https://theamericanroulette.com/news/justice-dept-john-brennan-subpoenas-html-2/">司 法 部周一急撤对布伦南 大 陪 审 团 传 票 上周刚踢掉资深检察官 换上 81...</a></li>

</ul>
</details>

**Tags**: `#legal`, `#free speech`, `#subpoena`, `#Reddit`, `#ICE`

---