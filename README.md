<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
  <img src="./assets/hero-light.svg" width="100%" alt="Yardon_Official — 代码如诗，逻辑如词">
</picture>

<div align="center">

[展览说明](#展览说明--note-on-the-collection) · [展品](#展品--works) · [这一年](#这一年--the-year) · [笔记](#笔记--notes) · [通道](#通道--elsewhere)

</div>

## 展览说明 · Note on the Collection

这里收着一批小机器。有的替人核对表格，有的替人写文章，有的只是为了让一段中文在流式输出里不被截成两半。它们被同一个约束塑造：尽量少打扰人。少问、少说、少占屏幕，真需要人的时候只问一个能一句话回答的问题。做这些东西的顺序几乎从不改变，先写清字段、规则和失败之后怎么办，再写第一行代码。跳过这一步省下的时间，后面要用三倍还回去。

*There is a small collection of machines here. Some check spreadsheets so a person doesn't have to, some write, and some exist only to keep a Chinese character from being cut in half mid-stream. All of them are shaped by one constraint: intrude as little as possible. Ask less, say less, take less of the screen, and when a person really is needed, ask one question that can be answered in a single line. The order rarely changes: write down the fields, the rules, and what happens after a failure, then write the first line of code. Time saved by skipping that step gets repaid three times over.*

这些东西大多不是从想法开始的，是从一次具体的麻烦开始的。表格又被填错了，某段中文又乱码了，某个工具每天要多点五次。把麻烦记下来，想清楚它为什么会反复发生，再决定要不要造一台机器去处理它。多数时候结论是不值得造，那就把规则写下来，让下一个人别再踩同一个坑。

*Most of these did not start as ideas. They started as a specific annoyance: a form filled in wrong again, a paragraph of Chinese turned to garbage again, a tool that costs five extra clicks every day. Write the annoyance down, work out why it keeps happening, then decide whether a machine is worth building. Most of the time the answer is no, and the rule gets written down instead, so the next person doesn't fall into the same hole.*

## 展品 · Works

**Ⅰ**
### [for-my-self-skills](https://github.com/YardonYan/for-my-self-skills)

十八件工具，装订成一册。从单页生成到任务编排，都在日常使用。

*Eighteen tools, bound into one volume. From single-page generation to task orchestration, all in daily use.*

<sub>`Agent Skills` · `双语` · `Apache-2.0`</sub>

**Ⅱ**
### [markdown-renderer-fix](https://github.com/YardonYan/markdown-renderer-fix)

专治中文在流式输出里被截断的毛病。这类问题没人愿意碰，但每个人都在遇到。

*For the specific misery of Chinese text sliced in half by streaming output. Nobody wants to work on this. Everybody runs into it.*

<sub>`SSE` · `渲染` · `国际化`</sub>

**Ⅲ**
### [task-skill-orchestrator](https://github.com/YardonYan/task-skill-orchestrator)

把复杂任务拆成依赖图，按波次派给多个执行者，最后收口。一个 Agent 什么都干，结局通常是上下文爆炸。

*Complex tasks as a dependency graph, dispatched in waves to separate executors, then merged. When one agent does everything, the ending is usually a blown context window.*

<sub>`DAG` · `多智能体`</sub>

**Ⅳ**
### [html-skill-effectiveness](https://github.com/YardonYan/html-skill-effectiveness)

零依赖的单页。十三种版式，一个五维评审的回路。目标是打开就能看，不用装任何东西。

*Single pages with zero dependencies. Thirteen layouts and a five-dimension critique loop. The goal is that it opens and it works, with nothing to install.*

<sub>`HTML` · `版式`</sub>

**Ⅴ**
### [daily-log](https://github.com/YardonYan/daily-log)

每天的流水账。不是精选集，只是一直在写。

*A running log. Not a curated collection — just one that keeps running.*

<sub>`笔记` · `片段`</sub>

**Ⅵ · 馆外**
### [五个在公网运行的实验](https://glimmerai.top)

文档检索问答、多智能体协作、代码体检、项目助手、参数调参台。都不在 GitHub 上，在站点里跑着。

*Retrieval over documents, multi-agent collaboration, code checkup, a project assistant, a tuning bench. None of them live on GitHub. They run at the site.*

<sub>`RAG` · `CrewAI` · `LangGraph` · [glimmerai.top](https://glimmerai.top)</sub>

## 这一年 · The Year

按月份拆开的提交记录，每一格是一天。格子越深，那天写得越多；右上角一点是二十四节气，左下角一点是节日，橙色边框是今天。

*The year split into months, one cell per day. The darker the cell, the more got done that day. A dot at the top right marks a solar term, a dot at the bottom left marks a festival, and the orange outline is today.*

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/calendar-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/calendar-light.svg">
  <img src="./assets/calendar-light.svg" width="100%" alt="2026 年按月提交记录">
</picture>

## 笔记 · Notes

**01 关于打扰**

一个会自己干活的 Agent，最大的风险不是干错，是干得太多、说得太勤。判断标准只有一条：这条消息发出去，人能不能立刻做一个动作。

*The risk with an agent that acts on its own is not that it does the wrong thing. It's that it does too much and says too much. There is only one test: after reading this, can the person do something right away?*

**02 关于顺序**

先定字段，再写代码。跳过这步，之后每个 bug 都是在补一张没画完的图纸。

*Define the fields, then write the code. Skip it, and every later bug is a patch on a drawing that was never finished.*

**03 关于完成**

演示是给评委看的，产品是给明天早上还要用它的人看的。这两件事的验收标准不一样，混淆了就两头都不讨好。

*A demo is for judges. A product is for whoever has to use it tomorrow morning. They don't share the same bar, and confusing them pleases neither.*

**04 关于记录**

写下来的才算学会。做完不整理，等于没做。

*If it isn't written down, it wasn't learned. A project you don't write up is a project you didn't do.*

## 工具 · Toolbox

<p align="center">
<sub>AGENT 框架与运行时 / AGENT RUNTIMES</sub>
</p>

<p align="center">
<kbd>DeepSeek Harness</kbd>&nbsp; <kbd>Super Agent</kbd>&nbsp; <kbd>OpenClaw</kbd>&nbsp; <kbd>CrewAI</kbd>&nbsp; <kbd>LangGraph</kbd>&nbsp; <kbd>MCP</kbd>
</p>

<p align="center">
<sub>编码工具 / CODING AGENTS</sub>
</p>

<p align="center">
<kbd>Claude Code</kbd>&nbsp; <kbd>Codex</kbd>&nbsp; <kbd>Cursor</kbd>&nbsp; <kbd>WorkBuddy</kbd>&nbsp; <kbd>CodeBuddy</kbd>&nbsp; <kbd>Qoder</kbd>&nbsp; <kbd>TRAE</kbd>
</p>

<p align="center">
<sub>语言与接口 / LANGUAGE &amp; INTERFACE</sub>
</p>

<p align="center">
<kbd>Python</kbd>&nbsp; <kbd>TypeScript</kbd>&nbsp; <kbd>Rust</kbd>&nbsp; <kbd>FastAPI</kbd>&nbsp; <kbd>pgvector</kbd>&nbsp; <kbd>Feishu</kbd>&nbsp; <kbd>WeCom</kbd>
</p>

## 通道 · Elsewhere

<p>
  <a href="https://glimmerai.top"><img src="https://img.shields.io/badge/站点-glimmerai.top-8B5E34?style=for-the-badge&logo=firefox&logoColor=FFD9A0" alt="站点" /></a>
  <a href="https://github.com/YardonYan"><img src="https://img.shields.io/badge/GitHub-YardonYan-2C2C2A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://github.com/YardonYan/for-my-self-skills"><img src="https://img.shields.io/badge/合集-18%20Skills-C0A276?style=for-the-badge&logo=bookstack&logoColor=3E2418" alt="技能合集" /></a>
</p>

<br>

<div align="center">
<sub>代码如诗，逻辑如词。</sub>
</div>
