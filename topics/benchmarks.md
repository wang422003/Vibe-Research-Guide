<h1 align="center">Vibe Research Guide<br>Benchmarks & Evaluation</h1>

> Benchmarks and Evaluation are **the most overlooked yet most critical part** of Vibe Research. Without rigorous evaluation, we cannot judge whether a research agent truly makes "scientific discoveries." This area focuses on: how to design evaluation tasks, how to measure real capabilities of research agents, and how to verify "reproducible scientific discovery."

<section id="benchmark-papers"></section>

## Paper List

| # | Paper | URL | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|---|
| 12 | ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery | [arXiv](https://arxiv.org/abs/2410.05080) | Benchmark | Rigorously evaluates language agents in data-driven scientific discovery, emphasizing authenticity and rigor. | Intermediate | evaluation rigor, scientific authenticity |
| 13 | FIRE-Bench: Evaluating Agents on the Rediscovery of Scientific Insights | [arXiv](https://arxiv.org/abs/2602.02905) | Benchmark | Core idea of "rediscovery" — tests whether agents can re-derive verified scientific conclusions. Provides a verifiable evaluation paradigm. | Intermediate | rediscovery, verification |
| 14 | AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite | [arXiv](https://arxiv.org/abs/2510.21652) | Benchmark | Larger-scale, more holistic scientific research benchmark suite covering multiple research sub-tasks. | Intermediate | holistic benchmark, scientific research suite |
| 15 | MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering | [arXiv](https://arxiv.org/abs/2410.07095) | Benchmark | By OpenAI. Uses Kaggle competitions to evaluate agent ML engineering capabilities. 75 real tasks covering data processing, feature engineering, model selection. | Intermediate | ML engineering, Kaggle, practical skills |
| 16 | RE-Bench: Evaluating Frontier AI R&D Capabilities of Language Model Agents Against Human Experts | [arXiv](https://arxiv.org/abs/2411.15671) | Benchmark | Evaluates AI on real R&D tasks with direct human expert comparison. Provides a quantitative answer to "how far is AI from replacing researchers." | Intermediate | R&D capability, human expert comparison |

<section id="benchmark-recommendations"></section>

## Recommendations

| # | Rating | Note |
|---|---|---|
| 12 | ★★★★★ | Must-read, evaluation rigor benchmark |
| 13 | ★★★★★ | Must-read, innovative rediscovery paradigm |
| 14 | ★★★★☆ | Highly recommended, large-scale comprehensive evaluation |
| 15 | ★★★★☆ | Highly recommended, ML engineering capability evaluation |
| 16 | ★★★★★ | Must-read, human expert comparison |

<section id="benchmark-comparison"></section>

## Benchmark Comparison

| Dimension | ScienceAgentBench | FIRE-Bench | AstaBench | MLE-bench | RE-Bench |
|---|---|---|---|---|---|
| Core idea | Rigorous data-driven discovery eval | Verify reproducible discoveries | Large-scale comprehensive eval | ML engineering practice | R&D vs human experts |
| Task source | Real research tasks | Published scientific conclusions | Multi-disciplinary research suite | Kaggle competitions | Real R&D tasks |
| Evaluation focus | Agent capability vs human | Can agent "rediscover" known results | End-to-end research ability | Data processing + modeling + optimization | Comprehensive R&D capability |
| Scale | Medium | Medium | Large | 75 tasks | Medium |
| Unique feature | Authenticity | Verifiability | Holistic coverage | Practicality (Kaggle-based) | Human-paired comparison |

<section id="benchmark-reading-tips"></section>

## Reading Tips

1. **Paper #12** is best read after the Systems topic (AI Scientist, etc.) — it helps you critically assess these systems' real capabilities.
2. **Paper #13**'s rediscovery perspective is unique: instead of asking "can the agent make new discoveries," it asks "can the agent rediscover known ones" — a clever evaluation design worth studying.
3. **Paper #14** is good reference when designing your own evaluation methodology.
4. **Paper #15 (MLE-bench)** is more engineering-oriented — it tests practical ML task completion, suited for Builder-track readers.
5. **Paper #16 (RE-Bench)** provides a key answer: "How large is the gap between AI agents and human researchers?" — helps calibrate realistic expectations for Vibe Research.

<section id="benchmark-extended"></section>

## Extended Reading

| Resource | Link | Description |
|---|---|---|
| MLAgentBench | [arXiv](https://arxiv.org/abs/2310.03302) | LLM agent ML research benchmark |
| SWE-bench | [GitHub](https://github.com/princeton-nlp/SWE-bench) | Agent GitHub issue solving benchmark |
| GAIA | [arXiv](https://arxiv.org/abs/2311.12983) | General AI assistant capability evaluation |
| Awesome AI Agent Benchmarks | [repo](https://github.com/agiresearch/awesome-ai-agent-benchmarks) | Comprehensive agent benchmark list |

---

> **Home**: [README](../README.md) · **Prev**: [Writing & Review](./writing-review.md)
