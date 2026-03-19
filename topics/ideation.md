<h1 align="center">Vibe Research Guide<br>Research Ideation</h1>

> Research Ideation focuses on a core question: **Can LLMs help researchers discover new research ideas?** This area covers finding research gaps from literature, iteratively generating ideas, evaluating novelty and feasibility, and human-AI collaborative ideation. It's the sub-field of Vibe Research most directly related to "scientific creativity."

<section id="ideation-papers"></section>

## Paper List

| # | Paper | URL | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|---|
| 7 | ResearchAgent: Iterative Research Idea Generation over Scientific Literature with Large Language Models | [arXiv](https://arxiv.org/abs/2404.07738) | Ideation | Iteratively generates ideas from literature, closely mirroring the real research process of "find gap → propose idea." | Intermediate | ideation, iteration |
| 8 | Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers | [arXiv](https://arxiv.org/abs/2409.04109) | Evaluation / Ideation | Large-scale human evaluation (100+ NLP researchers) of LLM-generated idea novelty and feasibility. Key empirical evidence. | Intermediate | novelty, feasibility, human evaluation |
| 9 | Chain of Ideas: Revolutionizing Research Via Novel Idea Development with LLM Agents | [arXiv](https://arxiv.org/abs/2410.13185) | Ideation | Uses Chain-of-Ideas to organize literature threads and Idea Arena to rank quality ideas, improving structured ideation. | Intermediate | Chain-of-Ideas, Idea Arena |
| 10 | Scideator: Human-LLM Scientific Idea Generation Grounded in Research-Paper Facet Recombination | [arXiv](https://arxiv.org/abs/2409.14634) | Human-LLM Ideation | Mixed-initiative (human-AI collaboration) ideation via paper facet recombination with novelty checking. | Intermediate | mixed-initiative, novelty check, facet recombination |
| 11 | AI-Researcher: Automating Scientific Discovery Through Multi-Agent Collaboration | [arXiv](https://arxiv.org/abs/2404.04573) | Ideation + System | Multi-agent collaboration for the full pipeline from literature survey to idea generation. Shows how to embed ideation in a complete research pipeline. | Intermediate | multi-agent, full pipeline, collaboration |
| 12 | Nova: An Iterative Planning and Search Approach to Enhance Novelty and Diversity of LLM Generated Ideas | [arXiv](https://arxiv.org/abs/2410.14255) | Ideation | Significantly improves novelty and diversity of LLM-generated ideas through iterative planning and search. Solves the common "all ideas look the same" problem. | Intermediate | novelty, diversity, iterative planning |

<section id="ideation-recommendations"></section>

## Recommendations

| # | Rating | Note |
|---|---|---|
| 7 | ★★★★★ | Must-read, representative iterative ideation |
| 8 | ★★★★★ | Must-read, empirical evaluation benchmark |
| 9 | ★★★★☆ | Highly recommended, structured ideation |
| 10 | ★★★★☆ | Highly recommended, human-AI collaboration |
| 11 | ★★★★☆ | Highly recommended, full-pipeline ideation |
| 12 | ★★★★☆ | Highly recommended, diversity improvement |

<section id="ideation-landscape"></section>

## Ideation Method Comparison

| Dimension | ResearchAgent | Can LLMs Generate...? | Chain of Ideas | Scideator | AI-Researcher | Nova |
|---|---|---|---|---|---|---|
| Core mechanism | Iterative generation + literature-based | Human comparative evaluation | Literature chain + Idea Arena | Facet recombination | Multi-agent collaboration | Iterative planning + search |
| Human involvement | Low (automatic) | High (evaluators) | Low (automatic) | High (collaborator) | Low (automatic) | Low (automatic) |
| Evaluation | Automatic | Human (100+ people) | Idea Arena ranking | Novelty check | Automatic | Automatic (novelty + diversity) |
| Output | Research idea | Idea + human scores | Ranked ideas | Grounded idea | Idea + experiment plan | Diverse idea set |
| Focus | Literature grounding | Empirical validation | Structured organization | Human-AI collaboration | End-to-end pipeline | Novelty + diversity |

<section id="ideation-reading-tips"></section>

## Reading Tips

1. **Paper #7** is the most intuitive entry point — the iterative process from literature to idea closely mirrors how you actually find research gaps.
2. **Paper #8** answers a key question: "Are LLM-generated ideas actually novel?" — gives you a clearer picture of LLM creativity boundaries.
3. **Papers #9 and #10** are best read together: Chain of Ideas is more automated, Scideator is more collaborative — two development directions for ideation.
4. **Paper #11 (AI-Researcher)** is for readers interested in the full "idea to experiment" pipeline — shows how ideation fits into larger research systems.
5. **Paper #12 (Nova)** tackles the "all ideas look the same" problem — worth reading if you find LLMs always give similar ideas.

<section id="ideation-extended"></section>

## Extended Reading

| Resource | Link | Description |
|---|---|---|
| IdeaSynth | [arXiv](https://arxiv.org/abs/2410.09274) | Knowledge graph-assisted idea generation |
| Awesome Scientific Idea Generation | [repo](https://github.com/wjie0309/awesome-scientific-idea-generation) | Paper list for scientific idea generation |
| CoI-Agent | [arXiv](https://arxiv.org/abs/2410.13185) | Chain of Ideas agent implementation |
| Eureka: Human-Level Reward Design via Coding LLMs | [arXiv](https://arxiv.org/abs/2310.12931) | LLM creativity in reward design, cross-domain reference |

---

> **Home**: [README](../README.md) · **Prev**: [Systems](./systems.md) · **Next**: [Synthesis](./synthesis.md)
