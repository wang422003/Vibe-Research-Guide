<h1 align="center">Vibe Research Guide<br>Representative Systems</h1>

> Representative systems demonstrate how LLM Agents participate **end-to-end** in scientific research: from idea generation to experiment execution to paper writing. These landmark systems mark Vibe Research's transition from concept to practice. Understanding their architecture and workflow helps you quickly assess "what's possible" and "how to build it."

<section id="system-papers"></section>

## Paper List

| # | Paper | URL | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|---|
| 4 | The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery | [arXiv](https://arxiv.org/abs/2408.06292) | System | Landmark work demonstrating end-to-end research automation: idea generation → experiment → paper writing → review. Foundational for understanding the field. | Intermediate | AI Scientist, end-to-end workflow |
| 5 | The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search | [arXiv](https://arxiv.org/abs/2504.08066) | System | Upgraded AI Scientist with agentic tree search, achieving higher autonomy and workshop-level output quality. | Intermediate | agentic tree search, autonomy |
| 6 | Agent Laboratory: Using LLM Agents as Research Assistants | [arXiv](https://arxiv.org/abs/2501.04227) | System | Human-in-the-loop design closer to real research scenarios, emphasizing human feedback and collaboration. More practical. | Intermediate | copilot, human feedback |
| 7 | SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering | [arXiv](https://arxiv.org/abs/2405.15793) | System | Princeton's Agent-Computer Interface (ACI) for efficient code repository interaction. Directly applicable to research experiment agents. | Intermediate | ACI, code interaction, software engineering |
| 8 | OpenHands: An Open Platform for AI Software Engineers | [arXiv](https://arxiv.org/abs/2407.16741) | Platform | Open-source full-stack agent platform with Docker sandbox. Ideal infrastructure for building research experiment systems. | Intermediate | open-source, full-stack agent, sandbox |
| 9 | EvoScientist: Towards Multi-Agent Evolving AI Scientists for End-to-End Scientific Discovery | [arXiv](https://arxiv.org/abs/2603.08127) | System | Self-evolving multi-agent framework (Researcher + Engineer + Evolution Manager) with persistent memory. Outperforms 7 SOTA systems in idea generation. | Intermediate | multi-agent, self-evolution, persistent memory |

<section id="system-recommendations"></section>

## Recommendations

| # | Rating | Note |
|---|---|---|
| 4 | ★★★★★ | Must-read, milestone work |
| 5 | ★★★★★ | Must-read, autonomy upgrade |
| 6 | ★★★★★ | Must-read, practical and deployable |
| 7 | ★★★★☆ | Highly recommended, pioneering ACI design |
| 8 | ★★★★☆ | Highly recommended, benchmark open-source agent platform |
| 9 | ★★★★★ | Must-read, latest self-evolving multi-agent approach |

<section id="system-architecture"></section>

## Architecture Comparison

| Dimension | AI Scientist | AI Scientist-v2 | Agent Laboratory | SWE-agent | OpenHands | EvoScientist |
|---|---|---|---|---|---|---|
| Autonomy | Fully automatic | Fully automatic (stronger search) | Human-in-the-loop | Fully automatic | Fully automatic / interactive | Fully automatic (self-evolving) |
| Search strategy | Linear pipeline | Agentic tree search | Human-guided | ACI-driven | Multi-strategy | Evolution-driven |
| Output level | Paper-level (preliminary) | Workshop-level | Research assistant | Code patch | Code + PR | Paper-level (evolved) |
| Best for | Proof of concept | Autonomous exploration | Real research collaboration | Code-intensive research | General research engineering | Continuous improvement |
| Code execution | Built-in | Built-in | Built-in | Sandbox | Docker Sandbox | Built-in |
| Open-source | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |

<section id="system-repos"></section>

## Code Repositories

| Project | Link | Description |
|---|---|---|
| The AI Scientist (Sakana AI) | [GitHub](https://github.com/SakanaAI/AI-Scientist) | Official open-source implementation |
| Agent Laboratory | [GitHub](https://github.com/SamuelSchmidgall/AgentLaboratory) | Official repository |
| SWE-agent | [GitHub](https://github.com/princeton-nlp/SWE-agent) | Princeton's official implementation |
| OpenHands | [GitHub](https://github.com/All-Hands-AI/OpenHands) | Open-source full-stack agent platform |
| EvoScientist | [GitHub](https://github.com/EvoScientist/EvoScientist) | Self-evolving AI scientist framework |

<section id="system-reading-tips"></section>

## Reading Tips

1. **Paper #4 (AI Scientist)** is the best entry point — understand what "end-to-end" means before looking at improvements.
2. **Paper #5** and **#4** are best read together — focus on what tree search brings as new capability.
3. **Paper #6** is for readers who want to "build things" — its human-in-the-loop design is closest to real research usage.
4. **Papers #7 (SWE-agent)** and **#8 (OpenHands)** focus on code execution, suited for the Builder track. Their open-source implementations can directly serve as base components.
5. **Paper #9 (EvoScientist)** is the latest advance — its self-evolution and persistent memory approach represents the next frontier.

<section id="system-extended"></section>

## Extended Reading

| Resource | Link | Description |
|---|---|---|
| MLAgentBench | [arXiv](https://arxiv.org/abs/2310.03302) | Benchmark for LLM agent ML experimentation |
| MetaGPT | [GitHub](https://github.com/geekan/MetaGPT) | Multi-agent software development framework with Data Interpreter |
| Aider | [GitHub](https://github.com/paul-gauthier/aider) | CLI AI programming assistant with multi-file editing |

---

> **Home**: [README](../README.md) · **Prev**: [Surveys](./surveys.md) · **Next**: [Ideation](./ideation.md)
