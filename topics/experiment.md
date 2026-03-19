<h1 align="center">Vibe Research Guide<br>Experiment Execution</h1>

> Experiment Execution focuses on how LLM Agents **automate the design and execution of scientific experiments**: from generating experiment plans, writing code, analyzing data, to interpreting results. This directly determines whether a Vibe Research system can truly "run experiments" rather than just "discuss them."

<section id="experiment-papers"></section>

## Paper List

| # | Paper | URL | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|---|
| 1 | MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation | [arXiv](https://arxiv.org/abs/2310.03302) | Benchmark + Agent | First systematic benchmark for LLM agent ML experimentation. Defines 13 ML tasks testing data processing, model training, and optimization. | Intermediate | ML experimentation, agent evaluation |
| 2 | Data Interpreter: An LLM Agent for Data Science | [arXiv](https://arxiv.org/abs/2402.18679) | System | MSRA's data science agent using dynamic planning and tool integration. Automates data cleaning, visualization, and modeling. Shows agent potential in data-intensive research. | Intermediate | data science, dynamic planning, tool use |
| 3 | OpenHands: An Open Platform for AI Software Engineers | [arXiv](https://arxiv.org/abs/2407.16741) | Platform | Open-source full-stack agent platform supporting the complete code generation, execution, and debugging cycle. Its architecture directly applies to research experiment agents. | Intermediate | code agent, software engineering, open-source |
| 4 | SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering | [arXiv](https://arxiv.org/abs/2405.15793) | System | Princeton's Agent-Computer Interface (ACI) for efficient code repository interaction. Demonstrates how agents can handle complex tasks in real code environments. | Intermediate | ACI, repository interaction, code repair |

<section id="experiment-recommendations"></section>

## Recommendations

| # | Rating | Note |
|---|---|---|
| 1 | ★★★★★ | Must-read, experiment automation benchmark |
| 2 | ★★★★☆ | Highly recommended, data science automation |
| 3 | ★★★★★ | Must-read, benchmark open-source agent platform |
| 4 | ★★★★☆ | Highly recommended, pioneering ACI design |

<section id="experiment-comparison"></section>

## Experiment Automation Comparison

| Dimension | MLAgentBench | Data Interpreter | OpenHands | SWE-agent |
|---|---|---|---|---|
| Core focus | ML experiment evaluation | Data science automation | General code agent | Code repair agent |
| Automation level | Fully automatic | Fully automatic | Fully automatic / interactive | Fully automatic |
| Code execution | ✓ sandbox | ✓ Jupyter | ✓ Docker sandbox | ✓ sandbox |
| Domain applicability | ML experiments | Data analysis, visualization | General software tasks | GitHub issue fixing |
| Human involvement | Evaluation phase | Optional | Optional | Evaluation phase |
| Tool integration | Python / ML libraries | Dynamic tool registration | Multi-language, multi-tool | CLI + editor |
| Output | Results + metrics | Analysis report + visualizations | Code + PR | Code patch |

<section id="experiment-repos"></section>

## Code Repositories

| Project | Link | Description |
|---|---|---|
| MLAgentBench | [GitHub](https://github.com/snap-stanford/MLAgentBench) | Stanford, 13 ML tasks |
| MetaGPT / Data Interpreter | [GitHub](https://github.com/geekan/MetaGPT) | MSRA multi-agent framework with Data Interpreter |
| OpenHands | [GitHub](https://github.com/All-Hands-AI/OpenHands) | Open-source full-stack agent platform |
| SWE-agent | [GitHub](https://github.com/princeton-nlp/SWE-agent) | Princeton ACI implementation |

<section id="experiment-reading-tips"></section>

## Reading Tips

1. **Paper #1 (MLAgentBench)** is the best entry point for understanding "agent experimentation capability" — it defines what "successfully completing an ML experiment" means.
2. **Paper #2 (Data Interpreter)** shows agent design patterns for data-intensive tasks — ideal for data analysis scenarios.
3. **Papers #3 + #4** are for Builders — their open-source implementations can directly serve as base components for your system.
4. Read alongside the [Systems](./systems.md) topic to understand how experiment execution fits into end-to-end research systems.

<section id="experiment-extended"></section>

## Extended Reading

| Resource | Link | Description |
|---|---|---|
| MLE-bench | [arXiv](https://arxiv.org/abs/2410.07095) | Kaggle-based ML engineering benchmark |
| TaskBench | [arXiv](https://arxiv.org/abs/2311.18760) | Agent tool use and task decomposition benchmark |
| Jupyter AI | [GitHub](https://github.com/jupyterlab/jupyter-ai) | JupyterLab AI extension |
| AutoML | [PapersWithCode](https://paperswithcode.com/task/automl) | Automated ML paper index |
| Awesome Code LLM | [repo](https://github.com/huybery/Awesome-Code-LLM) | Code LLM papers and tools |

---

> **Home**: [README](../README.md) · **Prev**: [Synthesis](./synthesis.md) · **Next**: [Writing & Review](./writing-review.md)
