---
layout: default
title: "Horizon Summary: 2026-05-24 (EN)"
date: 2026-05-24
lang: en
---

> From 27 items, 7 important content pieces were selected

---

1. [Backdoored Telegram on APKPure Steals Sensitive Data](#item-1) ⭐️ 9.0/10
2. [Microsoft Open-Sources Earliest DOS Source Code](#item-2) ⭐️ 8.0/10
3. [Wake up! 16b: 16-Byte Demo Pushes Minimalism to Extreme](#item-3) ⭐️ 8.0/10
4. [AI-driven HBM demand raises consumer electronics prices](#item-4) ⭐️ 8.0/10
5. [Microsoft Widely Deploys Claude Code Internally, Even for Non-Coders](#item-5) ⭐️ 8.0/10
6. [China Fines Futu 1.85B Yuan, Tiger Brokers 411M Yuan](#item-6) ⭐️ 8.0/10
7. [Corsair begins using Chinese CXMT DRAM chips, DDR5 prices may drop](#item-7) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Backdoored Telegram on APKPure Steals Sensitive Data](https://x.com/EricParker/status/2058411298195661221) ⭐️ 9.0/10

A repackaged version of Telegram 12.6.5 on APKPure contains a spyware framework called DataCollector that steals chats, contacts, photos, GPS, and SIM info, encrypted and sent to a C2 server at 38.190.225.166. This critical security incident compromises the trust in third-party app stores and exposes millions of Telegram users who downloaded from APKPure to complete data theft, potentially leading to privacy breaches and financial loss. The malicious code resides in classes3.dex with over 3000 lines, uses AES-GCM encryption for exfiltration, and was signed with a key not belonging to Telegram. Users who installed from APKPure should immediately uninstall and download the official version.

telegram · zaihuapd · May 24, 11:38

**Background**: APKPure is a third-party Android app store popular for providing APK files not always available on Google Play. Telegram is a widely-used cloud-based messaging app known for its security features. Repackaging involves modifying an official app to include malware while preserving its appearance, tricking users into installing a backdoored version.

<details><summary>References</summary>
<ul>
<li><a href="https://kod.ru/telegram-s-apkpure-virus">В Telegram со стороннего магазина APKPure нашли...</a></li>
<li><a href="https://apkpure.net/telegram/org.telegram.messenger/download">Download Telegram 12.7.1 APK for Android - Free and Safe Download</a></li>

</ul>
</details>

**Tags**: `#security`, `#malware`, `#backdoor`, `#spyware`, `#Telegram`

---

<a id="item-2"></a>
## [Microsoft Open-Sources Earliest DOS Source Code](https://arstechnica.com/gadgets/2026/04/microsoft-open-sources-the-earliest-dos-source-code-discovered-to-date/) ⭐️ 8.0/10

Microsoft has open-sourced the earliest known source code for MS-DOS, including the 86-DOS kernel and utilities, painstakingly recovered from paper printouts via OCR by the DOS Disassembly Group. This release provides unprecedented insight into the origins of the operating system that launched the PC revolution, offering historical value for researchers, hobbyists, and retrocomputing enthusiasts. The source code was recovered from printed listings found in a garage, and modern OCR software struggled with the quality of the decades-old printouts, requiring manual transcription by a dedicated team.

hackernews · DamnInteresting · May 24, 01:21 · [Discussion](https://news.ycombinator.com/item?id=48253386)

**Background**: MS-DOS was a foundational operating system for early IBM PCs, originally developed as 86-DOS by Seattle Computer Products and licensed by Microsoft. The open-sourcing of this early code allows developers to study the minimalist assembly language that ran on early x86 hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/microsoft/MS-DOS">GitHub - microsoft/MS- DOS : The original sources of MS- DOS 1.25...</a></li>
<li><a href="https://computerhistory.org/blog/microsoft-ms-dos-early-source-code/">Microsoft MS- DOS early source code - CHM</a></li>
<li><a href="https://onehack.st/t/microsoft-just-open-sourced-45-year-old-dos-code-found-on-paper-printouts-in-a-garage/322059">Microsoft Just Open-Sourced 45-Year-Old DOS Code Found on Paper ...</a></li>

</ul>
</details>

**Discussion**: The community response has been largely positive, with many thanking Microsoft for preserving computing history. Some commenters noted the importance of the simultaneous open-sourcing of early Microsoft BASIC, and others expressed nostalgia for the era when a few thousand lines of assembly could launch a software company.

**Tags**: `#open-source`, `#DOS`, `#Microsoft`, `#software history`, `#retrocomputing`

---

<a id="item-3"></a>
## [Wake up! 16b: 16-Byte Demo Pushes Minimalism to Extreme](https://hellmood.111mb.de/wake_up_16b_writeup.html) ⭐️ 8.0/10

A 16-byte executable program called 'Wake up!' produces an impressive audiovisual demo, featuring both visuals and sound, pushing the limits of minimalistic programming. This achievement demonstrates the pinnacle of size coding artistry, inspiring programmers to explore creative constraints. It shows that even with only 16 bytes, a program can deliver a rich, engaging experience. The demo includes both visual effects and sound, which is rare for such tiny intros. Achieving this likely requires exploitation of system calls, self-modifying code, and careful instruction selection.

hackernews · MaximilianEmel · May 24, 00:30 · [Discussion](https://news.ycombinator.com/item?id=48253060)

**Background**: The demoscene is an international computer art subculture that creates small, self-contained programs called demos, often size-restricted (e.g., 64K, 4K intros). Size coding techniques aim to produce the smallest possible executables while still generating impressive audiovisual output. A 16-byte demo is exceptionally rare and considered a masterpiece of minimalism.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Demoscene">Demoscene</a></li>
<li><a href="http://www.sizecoding.org/wiki/Main_Page">SizeCoding</a></li>

</ul>
</details>

**Discussion**: Commenters expressed awe at the achievement, with one noting it sent them on a rabbit hole to a Sierpinski triangle built in PowerPoint. Others compared it to other tiny demos and called it a masterpiece, lamenting that industry work rarely offers such creative freedom.

**Tags**: `#demoscene`, `#minimalism`, `#programming`, `#creativity`, `#assembly`

---

<a id="item-4"></a>
## [AI-driven HBM demand raises consumer electronics prices](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

Memory manufacturers are reallocating wafer capacity from DDR and LPDDR memory production to high-bandwidth memory (HBM) for AI data centers, causing a repricing of consumer electronics, especially in the sub-$100 smartphone market. This shift means consumer devices like smartphones and PCs will become significantly more expensive over the next few years, affecting global markets, particularly price-sensitive regions in Africa and South Asia. HBM consumes over three times the wafer capacity per gigabyte compared to DDR or LPDDR, and its wafer allocation is expected to rise from 2% to 20% by the end of 2026, squeezing supply for consumer memory.

rss · Simon Willison · May 22, 22:01

**Background**: There are only three major memory manufacturers, and they have fixed wafer capacity. HBM is a 3D-stacked memory used in AI GPUs, offering high bandwidth but consuming more wafer resources per gigabyte. The surge in AI data center demand is driving a structural shift in memory production, prioritizing HBM over commodity DRAM like DDR and LPDDR, which are used in consumer electronics.

<details><summary>References</summary>
<ul>
<li><a href="https://semiwiki.com/wikis/semiconductor-ip-wikis/ddr-vs-lpddr-vs-hbm-wiki/">DDR vs. LPDDR vs. HBM Wiki - SemiWiki</a></li>
<li><a href="https://www.fusionww.com/insights/blog/ai-sets-the-price-why-dram-shortages-are-rewriting-memory-market-economics">AI Sets the Price: Why DRAM Shortages Are Rewriting Memory ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#memory shortage`, `#AI demand`, `#consumer electronics`, `#HBM`, `#hardware pricing`

---

<a id="item-5"></a>
## [Microsoft Widely Deploys Claude Code Internally, Even for Non-Coders](https://t.me/zaihuapd/41535) ⭐️ 8.0/10

Microsoft is broadly rolling out Anthropic's Claude Code to its key engineering teams, including the CoreAI team and the Experiences & Devices division responsible for Windows and Microsoft 365. The company is also requiring software engineers to compare Claude Code with GitHub Copilot and provide feedback. This move signals that Microsoft is willing to adopt a competing AI coding tool even as it sells GitHub Copilot, which could reshape the AI-assisted programming landscape. Encouraging non-technical staff to use Claude Code for prototyping also highlights its potential to democratize software development. Microsoft is specifically asking teams behind Windows, Microsoft 365, and Outlook to install Claude Code. The company is also having engineers run parallel comparisons with GitHub Copilot, gathering performance data to inform future tooling decisions.

telegram · zaihuapd · May 23, 06:05

**Background**: Claude Code is an AI-powered coding assistant developed by Anthropic, the company behind the Claude family of large language models. It competes directly with GitHub Copilot, which is owned by Microsoft. Anthropic trains Claude using 'constitutional AI' to improve ethical compliance. The tool is designed to help developers write, debug, and refactor code directly in their IDE or terminal.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**Tags**: `#AI programming tools`, `#Microsoft`, `#Claude Code`, `#GitHub Copilot`, `#software engineering`

---

<a id="item-6"></a>
## [China Fines Futu 1.85B Yuan, Tiger Brokers 411M Yuan](https://t.me/zaihuapd/41539) ⭐️ 8.0/10

Chinese regulators have proposed fines totaling about 2.26 billion yuan on Futu Holdings (1.85 billion yuan) and Tiger Brokers (411 million yuan) for unlicensed securities operations in mainland China. The companies are required to rectify or cease these activities. This action highlights China's intensified enforcement against cross-border financial services operating without proper licenses, potentially affecting millions of mainland investors using these platforms for overseas trading. It also signals a tighter regulatory environment for foreign fintech companies. The penalties include confiscation of illegal gains and fines. Futu's founder Li Hua faces a personal fine of 1.25 million yuan. The fines are preliminary and subject to final determination after due process.

telegram · zaihuapd · May 23, 10:58

**Background**: Futu Holdings and Tiger Brokers are Hong Kong-based online brokerages popular among mainland Chinese investors for trading US and Hong Kong stocks. They have been operating without direct licenses from Chinese securities regulators, which typically prohibit offshore brokerages from soliciting mainland clients. The crackdown is part of a broader regulatory push to control capital outflows and ensure compliance with securities laws.

**Tags**: `#fintech`, `#regulation`, `#China`, `#securities`, `#cross-border`

---

<a id="item-7"></a>
## [Corsair begins using Chinese CXMT DRAM chips, DDR5 prices may drop](https://thenextweb.com/news/chinese-dram-cxmt-corsair-ddr5-memory-prices) ⭐️ 8.0/10

Corsair has started using ChangXin Memory Technologies (CXMT) DRAM chips in its DDR5 memory modules, with 6000 MT/s modules already available on the market that match the performance of mainstream international products. This shift signals growing market acceptance of Chinese DRAM suppliers and could lower DDR5 prices for consumers, as the global DRAM supply is strained by the diversion of production capacity to high-bandwidth memory (HBM) for AI applications. The global DRAM giants (Samsung, SK Hynix, Micron) have prioritized HBM production for AI, leading to consumer DRAM shortages. CXMT plans a mass production expansion and an IPO within 2026, with industry experts expecting notable DDR5 price declines by the second half of 2027.

telegram · zaihuapd · May 23, 11:17

**Background**: DRAM (Dynamic Random Access Memory) is a type of volatile memory used in computers and devices. CXMT is a Chinese DRAM manufacturer founded in 2016, headquartered in Hefei. Currently, the DRAM market is dominated by three companies: Samsung, SK Hynix, and Micron. High-Bandwidth Memory (HBM) is a 3D-stacked DRAM interface used primarily in AI accelerators and high-performance computing, which has seen surging demand, causing manufacturers to shift capacity away from standard DDR5 production.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Changxin_Memory_Technologies">ChangXin Memory Technologies - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#DRAM`, `#Corsair`, `#CXMT`, `#memory pricing`, `#supply chain`

---