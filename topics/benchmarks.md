<h1 align="center">Vibe Research Guide<br>评测篇 Benchmark & Evaluation</h1>

> Benchmark 与 Evaluation 是 Vibe Research 中**最容易被忽视但最决定研究质量的部分**。没有严格的评测，我们无法判断一个 research agent 是否真正"做了科学发现"。这个方向关注：如何设计评测任务、如何衡量科研 agent 的真实能力、以及如何验证"可重复的科学发现"。

<section id="benchmark-papers"></section>

## 论文列表

| # | Paper | URL | Type | Why read / 为什么读 | Stage | Keywords |
|---|---|---|---|---|---|---|
| 12 | ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery | [arXiv](https://arxiv.org/abs/2410.05080) | Benchmark | 严格评测 language agents 在 data-driven scientific discovery 中的能力，强调评测的真实性和严谨性。 | Intermediate | evaluation rigor, scientific authenticity |
| 13 | FIRE-Bench: Evaluating Agents on the Rediscovery of Scientific Insights | [arXiv](https://arxiv.org/abs/2602.02905) | Benchmark | 以"rediscovery"为核心——测试 agent 能否重新发现已验证的科学结论，提供了可验证的评测范式。 | Intermediate | rediscovery, verification |
| 14 | AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite | [arXiv](https://arxiv.org/abs/2510.21652) | Benchmark | 更大规模、更 holistic 的科研 benchmark suite，覆盖多个科研子任务。 | Intermediate | holistic benchmark, scientific research suite |

<section id="benchmark-recommendations"></section>

## 推荐度

| # | 推荐度 | 说明 |
|---|---|---|
| 12 | ★★★★★ | Must-read，评测严谨性标杆 |
| 13 | ★★★★★ | Must-read，rediscovery 范式创新 |
| 14 | ★★★★☆ | 强烈推荐，大规模综合评测 |

<section id="benchmark-comparison"></section>

## Benchmark 对比

| 维度 | ScienceAgentBench | FIRE-Bench | AstaBench |
|---|---|---|---|
| 核心理念 | 严谨评测 data-driven discovery | 验证可重复科学发现 | 大规模综合科研评测 |
| 任务来源 | 真实科研任务 | 已发表的科学结论 | 多学科科研任务集 |
| 评测重点 | Agent 能力 vs 人类表现 | 能否重新"发现"已知结论 | 端到端科研能力 |
| 规模 | 中等 | 中等 | 较大 |
| 特色 | 真实性（authenticity） | 可验证性（verifiability） | 覆盖面（holistic） |

<section id="benchmark-reading-tips"></section>

## 阅读建议

1. **论文 #12** 建议在读完系统篇（AI Scientist 等）之后阅读——它帮助你批判性地审视这些系统的真实能力。
2. **论文 #13** 的 rediscovery 视角非常独特：不问"agent 能不能做新发现"，而问"agent 能不能重新发现已知的发现"——这个评测设计值得学习。
3. **论文 #14** 适合在你准备设计自己的评测方案时参考。

<section id="benchmark-extended"></section>

## 延伸阅读

| 资源 | 链接 | 说明 |
|---|---|---|
| MLAgentBench | [arXiv](https://arxiv.org/abs/2310.03302) | 评测 LLM Agent 做 ML 研究的 benchmark |
| MLE-bench | [arXiv](https://arxiv.org/abs/2410.07095) | 评测 Agent 在 Kaggle 竞赛中的表现 |
| SWE-bench | [GitHub](https://github.com/princeton-nlp/SWE-bench) | 评测 Agent 解决真实 GitHub Issue 的能力 |
| RE-Bench | [arXiv](https://arxiv.org/abs/2411.15671) | 评测 AI 在研究工程任务上的能力 |
| Awesome AI Agent Benchmarks | [repo](https://github.com/agiresearch/awesome-ai-agent-benchmarks) | Agent Benchmark 综合列表 |
