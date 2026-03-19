<h1 align="center">Vibe Research Guide<br>代表系统篇 Representative Systems</h1>

> 代表性系统展示了 LLM Agent 如何**端到端**地参与科学研究：从 idea 生成、实验实现到论文撰写。这些系统是 Vibe Research 从概念走向落地的标志性工作，理解它们的架构设计与工作流程，能帮助你快速判断"能做什么"和"怎么做"。

<section id="system-papers"></section>

## 论文列表

| # | Paper | URL | Type | Why read / 为什么读 | Stage | Keywords |
|---|---|---|---|---|---|---|
| 4 | The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery | [arXiv](https://arxiv.org/abs/2408.06292) | System | 标志性工作，展示端到端科研自动化流程：idea generation → experiment → paper writing → review。理解此系统是理解整个领域的基础。 | Intermediate | AI Scientist, end-to-end workflow |
| 5 | The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search | [arXiv](https://arxiv.org/abs/2504.08066) | System | AI Scientist 的升级版，引入 agentic tree search，更高自主性与搜索能力，产出达到 workshop 级别。 | Intermediate | agentic tree search, autonomy |
| 6 | Agent Laboratory: Using LLM Agents as Research Assistants | [arXiv](https://arxiv.org/abs/2501.04227) | System | 更贴近真实科研场景的 human-in-the-loop 设计，强调人类反馈与协作，实用性更强。 | Intermediate | copilot, human feedback |

<section id="system-recommendations"></section>

## 推荐度

| # | 推荐度 | 说明 |
|---|---|---|
| 4 | ★★★★★ | Must-read，里程碑工作 |
| 5 | ★★★★★ | Must-read，自主性提升 |
| 6 | ★★★★★ | Must-read，落地友好 |

<section id="system-architecture"></section>

## 系统架构对比

| 维度 | AI Scientist | AI Scientist-v2 | Agent Laboratory |
|---|---|---|---|
| 自主性 | 全自动 | 全自动（更强搜索） | Human-in-the-loop |
| 搜索策略 | 线性流程 | Agentic tree search | 人类引导 |
| 产出级别 | 论文级（初步） | Workshop 级 | 研究助手级 |
| 适合场景 | 概念验证 | 自主探索 | 真实科研协作 |

<section id="system-repos"></section>

## 相关代码仓库

| 项目 | 链接 | 说明 |
|---|---|---|
| The AI Scientist (Sakana AI) | [GitHub](https://github.com/SakanaAI/AI-Scientist) | 官方开源实现，可直接复现 |
| Agent Laboratory | [GitHub](https://github.com/SamuelSchmidgall/AgentLaboratory) | 官方代码仓库 |

<section id="system-reading-tips"></section>

## 阅读建议

1. **论文 #4（AI Scientist）** 是入门系统篇的首选——先理解"端到端"意味着什么，再看后续工作如何改进。
2. **论文 #5** 和 **#4** 对比阅读，重点关注 tree search 带来了哪些新能力。
3. **论文 #6** 适合"想动手做"的读者——它的 human-in-the-loop 设计更接近你实际科研中的使用方式。

<section id="system-extended"></section>

## 延伸阅读

| 资源 | 链接 | 说明 |
|---|---|---|
| MLAgentBench | [arXiv](https://arxiv.org/abs/2310.03302) | 评测 LLM Agent 做 ML 实验的能力 |
| SWE-agent | [GitHub](https://github.com/princeton-nlp/SWE-agent) | Agent 自动修复 GitHub Issue，工程能力参考 |
| OpenHands (formerly OpenDevin) | [GitHub](https://github.com/All-Hands-AI/OpenHands) | 通用软件开发 Agent 平台 |
