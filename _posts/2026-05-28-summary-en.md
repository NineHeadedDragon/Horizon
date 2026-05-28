---
layout: default
title: "Horizon Summary: 2026-05-28 (EN)"
date: 2026-05-28
lang: en
---

> From 40 items, 10 important content pieces were selected

---

1. [Microsoft Copilot Cowork Vulnerability Enables File Exfiltration via Prompt Injection](#item-1) ⭐️ 9.0/10
2. [GitHub Incident Disrupts Pull Requests, Issues, and Git Operations](#item-2) ⭐️ 8.0/10
3. [Go to Implement Generic Methods on Structs](#item-3) ⭐️ 8.0/10
4. [Tech CEOs' AI Hype Criticized as 'Psychosis'](#item-4) ⭐️ 8.0/10
5. [Private equity's takeover of US essential services](#item-5) ⭐️ 8.0/10
6. [SQLite introduces AGENTS.md policy rejecting AI agent code](#item-6) ⭐️ 8.0/10
7. [AI Security Reports Overwhelm curl Maintainers](#item-7) ⭐️ 8.0/10
8. [NASA Reveals Lunar Base Plan Details, Awards Lander Contracts](#item-8) ⭐️ 8.0/10
9. [7-Zip Critical Heap Overflow Vulnerability Patched in 26.01](#item-9) ⭐️ 8.0/10
10. [Changxin Technology IPO Approved on STAR Market, Plans to Raise 295 Billion Yuan](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Microsoft Copilot Cowork Vulnerability Enables File Exfiltration via Prompt Injection](https://simonwillison.net/2026/May/26/copilot-cowork-exfiltrates-files/#atom-everything) ⭐️ 9.0/10

PromptArmor disclosed a vulnerability in Microsoft Copilot Cowork that allows attackers to exfiltrate files by sending compromised emails with external images, which when rendered by the user, trigger network requests leaking data. This attack exploits the automatic approval of agent actions and the rendering of external images, representing a critical security flaw in agentic AI systems. It highlights the ongoing challenge of preventing prompt injection in LLM-based agents that have access to sensitive data. The vulnerability leverages pre-authenticated OneDrive download links, allowing a successful prompt injection to leak those links and enable file downloads by the attacker. The attack achieved a high success rate against state-of-the-art models including Claude Opus 4.7.

rss · Simon Willison · May 26, 15:36

**Background**: Prompt injection is a cybersecurity attack where malicious prompts cause unintended behavior in LLMs. In agentic systems like Copilot Cowork, agents can perform actions such as sending emails, and if external images are rendered, they can exfiltrate data by triggering network requests to attacker-controlled servers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.promptarmor.com/resources/microsoft-copilot-cowork-exfiltrates-files">Microsoft Copilot Cowork Exfiltrates Files</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#security`, `#prompt injection`, `#Microsoft Copilot`, `#exfiltration`, `#AI agents`

---

<a id="item-2"></a>
## [GitHub Incident Disrupts Pull Requests, Issues, and Git Operations](https://www.githubstatus.com/incidents/xy1tt3hs572m) ⭐️ 8.0/10

On an unspecified recent date, GitHub experienced an incident affecting pull requests, issues, git operations, and API requests, causing inconsistent behavior such as pull requests not reflecting all commits or branch changes. This incident is significant because it affects core GitHub features critical for software development collaboration, and it is part of a pattern of recent outages that raise concerns about GitHub's reliability. Users reported that pull requests on both the web UI and API were not reflecting all commits or branch changes consistently, which could lead to merging code without a full review. The incident adds to a series of outages that have occurred over the past month.

hackernews · maxnoe · May 27, 12:15 · [Discussion](https://news.ycombinator.com/item?id=48293080)

**Background**: GitHub is a widely used platform for version control and collaboration using Git. GitOps is an operational framework that uses Git repositories as the single source of truth for infrastructure and application deployment. Outages like this impact developers and teams that rely on GitHub for continuous integration and delivery.

<details><summary>References</summary>
<ul>
<li><a href="https://about.gitlab.com/topics/gitops/">What is GitOps?</a></li>
<li><a href="https://www.redhat.com/en/topics/devops/what-is-gitops">What is GitOps?</a></li>
<li><a href="https://www.atlassian.com/git/tutorials/gitops">What Is GitOps? | Atlassian Git Tutorial</a></li>

</ul>
</details>

**Discussion**: Community comments express frustration and concern about the frequency of recent outages. One user created a site 'isgithubcooked.com' to track reliability, and others highlighted risks such as merging incomplete code due to inconsistent PR state. There are also calls for accountability, including suggestions to fire leadership.

**Tags**: `#github`, `#outage`, `#gitops`, `#reliability`, `#infrastructure`

---

<a id="item-3"></a>
## [Go to Implement Generic Methods on Structs](https://github.com/golang/go/issues/77273) ⭐️ 8.0/10

The Go team is working on implementing support for generic methods on structs, as documented in GitHub issue #77273. This will allow methods to have their own type parameters independent of the receiver's type parameters. This feature closes a significant gap in Go's generics, enabling more expressive library designs like generic data access patterns and monadic interfaces. It addresses a long-standing community request and brings Go closer to parity with other statically typed languages. The implementation will allow type parameters on methods of generic structs, but generic interface methods remain unsupported due to implementation difficulties. The proposal is still under technical discussion within the Go team.

hackernews · f311a · May 27, 09:02 · [Discussion](https://news.ycombinator.com/item?id=48291575)

**Background**: Go introduced generics in version 1.18, but initially did not allow methods to have their own type parameters separate from the receiver. This limitation was acknowledged as 'not now, not never' in the original design. The community has actively requested this feature since generics were introduced.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/golang/go/issues/77273">spec: generic methods for Go · Issue #77273 · golang/go</a></li>
<li><a href="https://go.dev/doc/tutorial/generics">Tutorial: Getting started with generics - The Go Programming Language</a></li>
<li><a href="https://www.digitalocean.com/community/tutorials/how-to-use-generics-in-go">How To Use Generics in Go | DigitalOcean</a></li>

</ul>
</details>

**Discussion**: Community reaction is largely positive, with users like xena excited about building a monad library and nasretdinov noting the surprise at the lack of generic methods initially. Some commenters like h1fra wryly observe that Go is now implementing features previously deemed unnecessary, while reactordev approves the direction for bridging gaps with other languages.

**Tags**: `#Go`, `#generics`, `#programming languages`, `#open source`

---

<a id="item-4"></a>
## [Tech CEOs' AI Hype Criticized as 'Psychosis'](https://techcrunch.com/2026/05/27/tech-ceos-are-apparently-suffering-from-ai-psychosis/) ⭐️ 8.0/10

An opinion piece on TechCrunch and a Hacker News discussion accuse tech CEOs of suffering from 'AI psychosis,' characterized by irrational overconfidence in AI capabilities. The article argues that CEOs often lack technical understanding yet make sweeping claims about what AI can achieve. This critique highlights a growing concern about hype-driven decision-making in the tech industry. Inflated expectations can lead to misallocated resources and unrealistic product promises, affecting investors, employees, and end-users. The article likens CEOs' behavior to psychosis, where they act on beliefs without understanding the underlying technology. Community comments note that similar dynamics occurred with previous tech bubbles like cloud computing and mobile, and that the phenomenon is not unique to AI.

hackernews · IAmGraydon · May 27, 15:20 · [Discussion](https://news.ycombinator.com/item?id=48295679)

**Background**: This opinion piece is part of an ongoing debate about the AI hype cycle, where companies rush to incorporate AI into products despite limited practical understanding. Historically, similar exuberance has accompanied technologies like blockchain and the metaverse. The term 'psychosis' is used metaphorically to critique the irrational exuberance and overpromising seen among tech leaders.

**Discussion**: The Hacker News community largely agrees with the critique, with many noting that such over-hype is not new to the tech industry. Some users share personal anecdotes of successful AI applications but caution against extrapolating from those examples. A key point is that leadership often lacks technical depth, leading to unrealistic expectations and poor decision-making.

**Tags**: `#AI`, `#tech industry`, `#critique`, `#hype`, `#community discussion`

---

<a id="item-5"></a>
## [Private equity's takeover of US essential services](https://rubbishtalk.com/economy/how-private-equity-bought-americas-essential-services/) ⭐️ 8.0/10

The article analyzes how private equity firms have acquired control over critical infrastructure in the U.S., driven largely by pension fund demands for high returns. This development has systemic implications for the economy, as essential services become profit-driven, potentially reducing quality and increasing costs for consumers. The article notes that pension funds require around 7% annual returns to remain solvent, pushing them into private equity investments, which often lead to cost-cutting and reduced service quality.

hackernews · NoRagrets · May 27, 12:00 · [Discussion](https://news.ycombinator.com/item?id=48292941)

**Background**: Private equity firms raise capital from institutional investors like pension funds to acquire companies, often using debt. They aim to improve and sell at a profit, sometimes prioritizing short-term gains. Pension funds invest in PE to meet return targets, but this model can strain the delivery of essential services.

**Discussion**: Commenters note the irony that pension funds drive PE, transferring value from current living standards to retirement. Some draw historical parallels to Crassus' fire brigade, while others lament the strip-mining of social capital as PE acquires small businesses.

**Tags**: `#private equity`, `#economy`, `#pensions`, `#essential services`, `#investment`

---

<a id="item-6"></a>
## [SQLite introduces AGENTS.md policy rejecting AI agent code](https://simonwillison.net/2026/May/27/sqlite-agents/#atom-everything) ⭐️ 8.0/10

SQLite added an AGENTS.md file to its repository stating that it does not accept agentic code contributions, while welcoming bug reports and documentation patches. Additionally, the project created a separate bug forum to handle the influx of AI-generated bug reports. This policy sets a clear precedent for open-source governance regarding AI-generated contributions, directly addressing the challenges many projects face with low-quality AI submissions. It could influence other major projects to adopt similar guidelines. The AGENTS.md also requires prior agreement and legal paperwork for pull requests, and the most recent commit removed the word '(currently)' to strengthen the rejection of agentic code. SQLite's forum was flooded with AI bug reports, leading to the creation of a dedicated bug forum maintained by D. Richard Hipp.

rss · Simon Willison · May 27, 23:44

**Background**: Agentic coding refers to the use of autonomous AI agents that plan, write, test, and modify code with minimal human intervention. SQLite is a widely deployed embedded database engine known for its conservative development practices. The policy clarifies the project's stance on AI-generated code, distinguishing between automated code contributions and human-reviewed bug reports.

<details><summary>References</summary>
<ul>
<li><a href="https://cloud.google.com/discover/what-is-agentic-coding">What is agentic coding? How it works and use cases | Google Cloud</a></li>

</ul>
</details>

**Tags**: `#sqlite`, `#AI agents`, `#open-source governance`, `#software engineering`

---

<a id="item-7"></a>
## [AI Security Reports Overwhelm curl Maintainers](https://simonwillison.net/2026/May/26/the-pressure/#atom-everything) ⭐️ 8.0/10

Daniel Stenberg, the maintainer of curl, reported that the project is facing 4-5 times more security reports than in 2024 and double the rate of 2025, with more than one report per day on average, all of which are highly detailed and often AI-assisted. This surge highlights the escalating pressure on open-source maintainers from AI-generated security research, threatening maintainer well-being and project sustainability, especially for critical infrastructure like curl. Although the number of reports has skyrocketed, the vulnerabilities found are almost all of LOW or MEDIUM severity, with the last HIGH severity CVE (CVE-2023-38545) published in October 2023.

rss · Simon Willison · May 26, 23:48

**Background**: curl is a widely used command-line tool and library for transferring data with URLs, supporting protocols like HTTP, FTP, and many others. It is a critical component in countless systems and applications. The project is maintained by a small team led by Daniel Stenberg, who now faces unprecedented mental pressure and work-life imbalance due to the flood of AI-assisted security reports.

**Tags**: `#curl`, `#open source`, `#security`, `#AI`, `#maintenance`

---

<a id="item-8"></a>
## [NASA Reveals Lunar Base Plan Details, Awards Lander Contracts](https://www.bbc.com/news/articles/c39228nxyr4o) ⭐️ 8.0/10

NASA has announced new details for its lunar base plan, aiming for a semi-permanent outpost at the south pole by 2032. Multiple companies including Blue Origin, Intuitive Machines, and Astrobotic have been awarded contracts to build landers, rovers, and communication equipment. This plan represents a concrete step toward sustained human presence on the Moon, with implications for resource extraction and Mars missions. However, delays in SpaceX's crewed lunar lander and competition from China add political urgency. The plan includes 25 launches by 2029 to deliver 4 tons of cargo, using robotic landers and hopping drones to survey the south pole. The base will be powered by a combination of nuclear reactors and solar energy.

telegram · zaihuapd · May 27, 03:08

**Background**: NASA's Artemis program aims to return humans to the Moon and establish a sustainable presence. The lunar base would serve as a staging point for future Mars missions. Nuclear power is considered essential for long-term lunar operations due to the harsh environment and long lunar nights.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bbc.com/future/article/20240417-the-nuclear-reactors-that-could-power-moon-bases">The nuclear reactors that could power bases on the Moon</a></li>
<li><a href="https://phys.org/news/2025-03-firm-moon-drill-rovers-drone.html">US firm targets Moon landing with drill, rovers, hopping drone</a></li>

</ul>
</details>

**Tags**: `#NASA`, `#lunar base`, `#space exploration`, `#Blue Origin`, `#SpaceX`

---

<a id="item-9"></a>
## [7-Zip Critical Heap Overflow Vulnerability Patched in 26.01](https://socprime.com/blog/cve-2026-48095-7-zip-heap-overflow-flaw/) ⭐️ 8.0/10

A critical heap buffer write overflow vulnerability (CVE-2026-48095) in 7-Zip's NTFS handler has been publicly disclosed, allowing arbitrary code execution via specially crafted archives. The issue was fixed in version 26.01 released on April 27, 2026. 7-Zip is one of the most widely used file archivers globally, and this vulnerability can be triggered through signature-based fallback, meaning even archives with common extensions like .7z or .zip can be weaponized. Immediate updating is crucial to prevent remote code execution or application crashes. The vulnerability exists in the NTFS archive handler (NTFSHandler.cpp) and allows heap buffer overflow when parsing crafted NTFS images. The flaw has a CVSS score of 8.8, affects 7-Zip 26.00 and all prior versions, and was discovered by Jaroslav Lobačevski of GitHub Security Lab.

telegram · zaihuapd · May 27, 08:01

**Background**: A heap buffer overflow occurs when a program writes data beyond the allocated memory region in the heap, potentially overwriting critical data structures. Attackers can exploit this to execute arbitrary code or crash the application. 7-Zip uses a signature-based fallback mechanism: if the file extension-based handler fails, it tries all remaining handlers by file signature. This allows a crafted NTFS image disguised as a .7z or .zip file to reach the vulnerable NTFS handler.

<details><summary>References</summary>
<ul>
<li><a href="https://securitylab.github.com/advisories/GHSL-2026-140_7-Zip/">GHSL-2026-140: Heap Buffer Write Overflow in 7-Zip | GitHub Security Lab</a></li>
<li><a href="https://blog.gridinsoft.com/7-zip-cve-2026-48095/">7-Zip CVE-2026-48095: Update to 26.01 and Handle Archives Safely</a></li>
<li><a href="https://socprime.com/blog/cve-2026-48095-7-zip-heap-overflow-flaw/">CVE-2026-48095: 7-Zip Heap Overflow Flaw</a></li>

</ul>
</details>

**Tags**: `#security`, `#vulnerability`, `#CVE`, `#7-Zip`, `#heap overflow`

---

<a id="item-10"></a>
## [Changxin Technology IPO Approved on STAR Market, Plans to Raise 295 Billion Yuan](https://static.sse.com.cn/stock/disclosure/announcement/c/202605/000001_20260527_SPLE.pdf) ⭐️ 8.0/10

Changxin Technology's IPO on the Shanghai Stock Exchange's STAR Market was approved by the listing committee, with plans to raise 295 billion yuan for DRAM manufacturing upgrades and advanced technology R&D. This IPO is a major milestone for China's domestic DRAM industry, providing substantial capital to upgrade memory manufacturing and reduce reliance on foreign suppliers. It signals continued government support for semiconductor self-sufficiency. The funds will be used for technology upgrades in memory wafer mass production lines, DRAM technology improvements, and forward-looking technology R&D. The company is one of China's leading DRAM manufacturers.

telegram · zaihuapd · May 27, 09:12

**Background**: DRAM (Dynamic Random-Access Memory) is a type of volatile memory widely used as main memory in computers and other devices. The global DRAM market is currently dominated by Samsung, SK Hynix, and Micron. China has been working to develop domestic DRAM production to reduce import dependence, with companies like Changxin (CXMT) leading the effort. The STAR Market is a special board on the Shanghai Stock Exchange designed to support high-tech and innovative companies.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dynamic_random-access_memory">Dynamic random-access memory - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#DRAM`, `#IPO`, `#China technology`, `#memory manufacturing`

---