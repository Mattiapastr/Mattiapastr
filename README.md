<!--
  Mattia Pastrello - founder of BRILIA, AI marketing operations
  GitHub: https://github.com/Mattiapastr
  Organization: https://github.com/Brilia-it
  Website: https://brilia.it
  Focus: multi-agent marketing systems on Claude Code, verified client delivery, Windows-first tooling for Claude Code
-->

<div align="center">

  <a href="https://brilia.it">
    <picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/brilia22/header-dark-mobile.png" />
  <source media="(max-width: 600px)" srcset="./assets/brilia22/header-light-mobile.png" />
  <source media="(prefers-color-scheme: dark)" srcset="./assets/brilia22/header-dark.png" />
  <img src="./assets/brilia22/header-light.png" width="880" alt="Mattia Pastrello, BRILIA founder. Marketing systems and human review. Charlie, Windows PC, Tortoli, Italy." />
</picture>
  </a>

<img src="./assets/brilia22/ink-workflow-fixed.png" width="880" alt="Ink illustration of connected workstations, a manual document review and a delivery between computers." />

</div>

---

## About me

I run [BRILIA](https://brilia.it), a marketing agency in Italy. Its promise fits in one line: we bring clients to our clients.

I build multi-agent marketing workflows with Claude Code, Codex and Kimi. My work combines marketing strategy, software, automation and human review, with a focus on work that can be checked before delivery.

I build from the terminal and verify the result where people will use it. The rule I care about most: nothing is called delivered until someone has checked it on the channel it was delivered to.

**You will find something useful here if** you run client work with Claude Code or Codex and want the output checked before it leaves: a source for every number, quotes that match the transcript, links that open.

**Probably not, if** you are looking for a no-code template or a prompt pack.

---

## Local AI usage

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/brilia22/stats-dark-mobile.png" />
  <source media="(max-width: 600px)" srcset="./assets/brilia22/stats-light-mobile.png" />
  <source media="(prefers-color-scheme: dark)" srcset="./assets/brilia22/stats-dark.png" />
  <img src="./assets/brilia22/stats-light.png" width="880" alt="CodeBurn, rolling last 30 days, 29 October 2026: 9,119+ sessions; 140,431 model calls; 340.4M input/output tokens; 99.7% cache hit. Estimated cost shares: coding 59%, delegation 11%, features 10%, exploration 9%, debugging 6%, conversation 2%, other 3%." />
</picture>

<sub>Measured with <a href="https://github.com/getagentseal/codeburn">CodeBurn</a> on Charlie, my main Windows PC. Rolling “Last 30 Days” view, captured on 29 October 2026. Session count is a lower bound and includes automated observer sessions. Input/output tokens exclude cache reads and writes: CodeBurn reports those separately as 36.50B read and 1.29B written. The activity bar shows estimated cost share, not turn share. Tools detected: Claude, Codex, Kimi Code and Copilot.</sub>

These usage figures describe workload on one PC; they are not a measure of output quality or client results.


---

## BRILIA organization

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/brilia22/organization-dark-mobile.png" />
  <source media="(max-width: 600px)" srcset="./assets/brilia22/organization-light-mobile.png" />
  <source media="(prefers-color-scheme: dark)" srcset="./assets/brilia22/organization-dark.png" />
  <img src="./assets/brilia22/organization-light.png" width="880" alt="BRILIA, snapshot 5 September 2026: 9 departments, 60 registered units, 21 operational. Content; client intelligence; office; analytics; research; advertising; platform; development; lead generation." />
</picture>

The agency is organized into **9 departments and 60 registered units**. The v5.0 snapshot records **21 operational units** and **5 under construction**. These figures describe the structure documented on **5 September 2026**.

[Explore all 60 units and their recorded status](./docs/brilia-organization.md).

---

## Public project

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/brilia22/k3-dark-mobile.png" />
  <source media="(max-width: 600px)" srcset="./assets/brilia22/k3-light-mobile.png" />
  <source media="(prefers-color-scheme: dark)" srcset="./assets/brilia22/k3-dark.png" />
  <img src="./assets/brilia22/k3-light.png" width="880" alt="K3 plugin for Claude Code: read-only review, adversarial challenge and delegated tasks. Windows support. Apache-2.0 unofficial fork; own Kimi Code subscription required." />
</picture>

<div align="center">

| Project | What it does | License |
|:--------|:-------------|:-------:|
| **[k3-plugin-cc](https://github.com/Brilia-it/k3-plugin-cc)** | Drives Kimi K3 from Claude Code for reviews, adversarial challenges and delegated tasks. A fork of [linxule/kimi-plugin-cc](https://github.com/linxule/kimi-plugin-cc) that fixes the three things that break on Windows. | Apache-2.0 |

</div>

---

## Quickstart

Use Kimi K3 from inside Claude Code for reviews and delegated tasks, Windows included:

```text
# Add the marketplace, then install
/plugin marketplace add Brilia-it/k3-plugin-cc
/plugin install k3@brilia-k3-marketplace

# Then
/k3:review        # read-only review
/k3:challenge     # adversarial review
/k3:rescue        # hand a task to K3
```

You need your own Kimi Code subscription. The plugin never carries a credential.

---


## How I work

Four rules I work by. I call them the Pastrello Method.

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/brilia22/method-dark-mobile.png" />
  <source media="(max-width: 600px)" srcset="./assets/brilia22/method-light-mobile.png" />
  <source media="(prefers-color-scheme: dark)" srcset="./assets/brilia22/method-dark.png" />
  <img src="./assets/brilia22/method-light.png" width="880" alt="Pastrello Method: read existing context, review from the recipient perspective, fix findings, verify delivery on its actual channel." />
</picture>

- Before doing anything, check what we already know.
- Read the work again from the side of whoever receives it.
- What that second read finds, you fix. You don't just flag it.
- "Delivered" is proven on the channel, never assumed from "produced".

---



---

## Stack

### AI & agents
<p align="left">
  <img src="https://img.shields.io/badge/Claude_Code-1F4D3D?style=for-the-badge" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Codex-1F4D3D?style=for-the-badge" alt="OpenAI Codex" />
  <img src="https://img.shields.io/badge/Kimi_K3-1F4D3D?style=for-the-badge" alt="Kimi K3" />
  <img src="https://img.shields.io/badge/Gemma_(Ollama%2C_local)-1F4D3D?style=for-the-badge" alt="Gemma on Ollama, local" />
  <img src="https://img.shields.io/badge/MEM0-1F4D3D?style=for-the-badge" alt="MEM0" />
  <img src="https://img.shields.io/badge/graphify-1F4D3D?style=for-the-badge" alt="graphify" />
</p>

### Marketing
<p align="left">
  <img src="https://img.shields.io/badge/WordPress-b06a2c?style=for-the-badge" alt="WordPress" />
  <img src="https://img.shields.io/badge/Rank_Math-b06a2c?style=for-the-badge" alt="Rank Math" />
  <img src="https://img.shields.io/badge/Meta_Ads-b06a2c?style=for-the-badge" alt="Meta Ads" />
  <img src="https://img.shields.io/badge/DataForSEO-b06a2c?style=for-the-badge" alt="DataForSEO" />
  <img src="https://img.shields.io/badge/Brevo-b06a2c?style=for-the-badge" alt="Brevo" />
  <img src="https://img.shields.io/badge/ClickUp-b06a2c?style=for-the-badge" alt="ClickUp" />
</p>

### Build
<p align="left">
  <img src="https://img.shields.io/badge/Python-4a4a4a?style=for-the-badge" alt="Python" />
  <img src="https://img.shields.io/badge/Playwright-4a4a4a?style=for-the-badge" alt="Playwright" />
  <img src="https://img.shields.io/badge/WeasyPrint-4a4a4a?style=for-the-badge" alt="WeasyPrint" />
  <img src="https://img.shields.io/badge/Google_Workspace_CLI-4a4a4a?style=for-the-badge" alt="Google Workspace CLI" />
  <img src="https://img.shields.io/badge/faster--whisper-4a4a4a?style=for-the-badge" alt="faster-whisper" />
</p>

---

## Connect

<p align="center">
  <a href="https://brilia.it"><img src="https://img.shields.io/badge/Website-brilia.it-3a7d66?style=for-the-badge&labelColor=555555" alt="BRILIA website" /></a>
  <a href="https://github.com/Brilia-it"><img src="https://img.shields.io/badge/GitHub-Brilia--it-3a7d66?style=for-the-badge&labelColor=555555" alt="BRILIA on GitHub" /></a>
  <a href="https://www.linkedin.com/in/mattiapastrello/"><img src="https://img.shields.io/badge/LinkedIn-Mattia_Pastrello-3a7d66?style=for-the-badge&labelColor=555555" alt="Mattia Pastrello on LinkedIn" /></a>
  <a href="https://orcid.org/0009-0003-6709-3723"><img src="https://img.shields.io/badge/ORCID-0009--0003--6709--3723-3a7d66?style=for-the-badge&labelColor=555555" alt="Mattia Pastrello ORCID iD" /></a>
</p>
