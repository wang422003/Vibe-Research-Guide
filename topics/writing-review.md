<h1 align="center">Vibe Research Guide<br>Writing & Review</h1>

> Writing & Review focuses on how LLMs assist with **scientific paper writing, structural organization, and automated peer review**. This is the final step of the Vibe Research pipeline — transforming research results into publishable academic papers, and using AI feedback to improve paper quality.

<section id="writing-papers"></section>

## Paper List

| # | Paper | URL | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|---|
| 1 | Can Large Language Models Provide Useful Feedback on Research Papers? A Large-Scale Empirical Analysis | [arXiv](https://arxiv.org/abs/2310.01783) | Evaluation | Large-scale empirical study analyzing GPT-4's review feedback quality. Finds significant overlap with human reviewers, but gaps in deep insight. Essential data for understanding AI review boundaries. | Intermediate | LLM review, peer review, empirical study |
| 2 | MARG: Multi-Agent Review Generation for Scientific Papers | [arXiv](https://arxiv.org/abs/2401.04259) | System | Multi-agent review system simulating different roles (primary reviewer, secondary reviewer, meta-reviewer). Shows multi-agent coordination in academic review. | Intermediate | multi-agent, review generation, role-playing |
| 3 | SciMON: Scientific Inspiration Machines Optimized for Novelty | [arXiv](https://arxiv.org/abs/2305.14259) | System | Uses LLMs to help with "novelty positioning" — helping researchers better position their paper's contributions through automated literature analysis. | Intermediate | novelty, writing assistance, positioning |
| 4 | Automated Peer Reviewing in Paper SEA: Standardization, Evaluation, and Analysis | [arXiv](https://arxiv.org/abs/2407.12857) | Benchmark | Systematic framework for evaluating automated review methods. Proposes standardized evaluation and analyzes different LLM performance on review tasks. | Intermediate | automated review, standardization, evaluation |

<section id="writing-recommendations"></section>

## Recommendations

| # | Rating | Note |
|---|---|---|
| 1 | ★★★★★ | Must-read, authoritative LLM review capability assessment |
| 2 | ★★★★☆ | Highly recommended, innovative multi-agent review design |
| 3 | ★★★★☆ | Highly recommended, unique writing assistance perspective |
| 4 | ★★★★☆ | Highly recommended, standardized review evaluation |

<section id="writing-comparison"></section>

## Writing Assistance vs Automated Review

| Dimension | Writing Assistance | Automated Review |
|---|---|---|
| Representative work | SciMON | LLM Review Feedback, MARG, Paper SEA |
| Target user | Paper authors | Reviewers / conference organizers |
| Core task | Structure optimization, novelty positioning, language polishing | Generate review opinions, assess paper quality |
| Input | Paper draft + related literature | Complete paper |
| Output | Improvement suggestions, restructuring, novelty positioning | Review report (strengths/weaknesses/questions) |
| Challenges | Maintaining author intent, avoiding hallucination | Deep insight, fairness, consistency |
| Maturity | Newer, experimental | More active, multiple systems |

<section id="writing-landscape"></section>

## Method Taxonomy

```
LLM in Academic Writing & Review
├── Writing Assistance
│   ├── Structure organization (SciMON)
│   ├── Language polishing (Writefull, Paperpal)
│   └── Novelty positioning
├── Automated Review
│   ├── Single-agent review (GPT-4 as Reviewer)
│   ├── Multi-agent review (MARG)
│   └── Review evaluation (Paper SEA)
└── Review Assistance
    ├── Review opinion generation
    ├── Meta-review aggregation
    └── Review quality assessment
```

<section id="writing-repos"></section>

## Code Repositories

| Project | Link | Description |
|---|---|---|
| MARG | [GitHub](https://github.com/allenai/marg-reviewer) | Allen AI multi-agent review system |
| Automated Reviewer | [GitHub](https://github.com/liang-peng-jd/ReviewerGPT) | GPT-based automated review tool |
| SciMON | [GitHub](https://github.com/allenai/SciMON) | Allen AI novelty positioning system |

<section id="writing-reading-tips"></section>

## Reading Tips

1. **Paper #1** is the best entry point for "Can LLMs be reviewers?" — large-scale data, rigorous analysis, sets realistic expectations.
2. **Paper #2 (MARG)** demonstrates an interesting application of multi-agent collaboration — a great case study if you're interested in multi-agent systems.
3. **Paper #3 (SciMON)** takes a different angle: not "AI reviews your paper" but "AI helps you write better." Good for anyone currently writing papers.
4. **Paper #4 (Paper SEA)** is for researchers who want to design review evaluation systems — it provides a standardized framework.

<section id="writing-extended"></section>

## Extended Reading

| Resource | Link | Description |
|---|---|---|
| ReviewAdvisor | [arXiv](https://arxiv.org/abs/2303.14857) | Early work on automated review suggestions |
| GPT-4 as Reviewer (NeurIPS 2023) | [blog](https://blog.neurips.cc/) | NeurIPS 2023 experiment report on LLM review |
| Writefull | [website](https://www.writefull.com/) | Academic writing AI tool |
| Paperpal | [website](https://paperpal.com/) | AI writing assistant by Springer Nature |
| Grammarly Academic | [website](https://www.grammarly.com/) | General writing tool with academic mode |

---

> **Home**: [README](../README.md) · **Prev**: [Experiment](./experiment.md) · **Next**: [Benchmarks](./benchmarks.md)
