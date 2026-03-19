<h1 align="center">Vibe Research Guide<br>Literature Synthesis</h1>

> Literature Synthesis focuses on how to **let LLMs systematically read, understand, and synthesize large volumes of scientific literature**, producing citation-backed reviews or reports. This is the closest direction in Vibe Research to "automated literature reading" — going beyond Q&A to achieve citation-backed, factual, comprehensive synthesis.

<section id="synthesis-papers"></section>

## Paper List

| # | Paper | URL | Type | Why read | Stage | Keywords |
|---|---|---|---|---|---|---|
| 1 | OpenScholar: Synthesizing Scientific Literature with Retrieval-Augmented Language Models | [arXiv](https://arxiv.org/abs/2411.14199) | RAG / Synthesis | Benchmark work for scientific literature synthesis. Uses RAG to retrieve relevant passages from massive corpora, generating citation-backed answers. | Intermediate | RAG, citation-backed synthesis, grounded generation |
| 2 | PaperQA: Retrieval-Augmented Generative Agent for Scientific Research | [arXiv](https://arxiv.org/abs/2312.07559) | RAG / QA | By Future House. RAG-based scientific Q&A with full-text retrieval, precise citations, and answer verification. Exceeds human baseline. Open-source and deployable. | Beginner-Intermediate | RAG, question answering, citation verification |
| 3 | AutoSurvey: Large Language Models Can Automatically Write Surveys | [arXiv](https://arxiv.org/abs/2406.10252) | Survey Generation | Automatically generates academic survey papers. Given a topic, it retrieves literature, organizes structure, and produces a complete survey. | Intermediate | automated survey, long-form generation, knowledge organization |
| 4 | ScholarCopilot: Training Large Language Models for Academic Writing with Retrieval-Augmented Generation | [arXiv](https://arxiv.org/abs/2504.00824) | RAG / Writing | Deeply integrates retrieval with academic writing — the model automatically retrieves and cites relevant literature while writing. Represents the synthesis + writing convergence trend. | Intermediate | academic writing, retrieval-augmented, citation generation |
| 5 | RA-ISF: Learning to Answer and Understand from Retrieval Augmentation via Iterative Self-Feedback | [arXiv](https://arxiv.org/abs/2403.06840) | RAG / Reasoning | Improves RAG quality through iterative self-feedback. The agent autonomously evaluates and corrects answer quality in a retrieve→generate→verify loop. | Intermediate | iterative self-feedback, RAG improvement, self-correction |

<section id="synthesis-recommendations"></section>

## Recommendations

| # | Rating | Note |
|---|---|---|
| 1 | ★★★★★ | Must-read, literature synthesis benchmark |
| 2 | ★★★★★ | Must-read, open-source and deployable |
| 3 | ★★★★☆ | Highly recommended, automated survey generation |
| 4 | ★★★★☆ | Highly recommended, writing + retrieval convergence |
| 5 | ★★★★☆ | Highly recommended, general RAG quality improvement |

<section id="synthesis-comparison"></section>

## Method Comparison

| Dimension | OpenScholar | PaperQA2 | AutoSurvey | ScholarCopilot | RA-ISF |
|---|---|---|---|---|---|
| Core task | Multi-document synthesis | Precise literature Q&A | Automated survey generation | Write-as-you-cite | RAG quality improvement |
| Retrieval scope | Large-scale corpora | User-uploaded PDFs | Automatic retrieval | Training-integrated | General |
| Citation accuracy | High (grounding check) | High (source verification) | Medium | High (training-optimized) | High (iterative correction) |
| Output format | Synthesized answer | Q&A answer + citations | Complete survey paper | Academic paragraph + citations | Improved answer |
| Deployability | Open-source | Open-source | Open-source | Open-source | Methodology |
| Best for | Literature review | Daily paper Q&A | Survey writing | Paper writing | RAG system optimization |

<section id="synthesis-architecture"></section>

## Core Architecture

General architecture for literature synthesis systems:

```
                Literature Synthesis System Architecture
┌──────────────────────────────────────────────────────┐
│                                                      │
│  1. Literature Acquisition Layer                     │
│     ├── User-uploaded PDFs (PaperQA2)                │
│     ├── Large-scale corpus retrieval (OpenScholar)   │
│     └── Automatic literature search (AutoSurvey)     │
│                                                      │
│  2. Retrieval-Augmented Layer (RAG)                  │
│     ├── Passage-level retrieval (dense retrieval)    │
│     ├── Reranking                                    │
│     └── Context window management                    │
│                                                      │
│  3. Generation & Synthesis Layer                     │
│     ├── Citation-aware generation                    │
│     ├── Multi-document information fusion            │
│     └── Structured organization (sections, args)     │
│                                                      │
│  4. Verification & Feedback Layer                    │
│     ├── Citation verification (grounding check)      │
│     ├── Factual verification                         │
│     └── Iterative self-correction (RA-ISF)           │
│                                                      │
└──────────────────────────────────────────────────────┘
```

<section id="synthesis-repos"></section>

## Code Repositories

| Project | Link | Description |
|---|---|---|
| OpenScholar | [GitHub](https://github.com/allenai/OpenScholar) | Allen AI official implementation |
| PaperQA2 | [GitHub](https://github.com/Future-House/paper-qa) | Future House, `pip install paper-qa` |
| AutoSurvey | [GitHub](https://github.com/AutoSurveys/AutoSurvey) | Automated survey generation system |
| ScholarCopilot | [GitHub](https://github.com/THUDM/ScholarCopilot) | Tsinghua THUDM retrieval-augmented writing |

<section id="synthesis-reading-tips"></section>

## Reading Tips

1. **Paper #1 (OpenScholar)** is the best entry point for literature synthesis — it demonstrates RAG best practices in the scientific literature domain.
2. **Paper #2 (PaperQA2)** is best for readers who want to "get hands-on" — high quality open-source, just `pip install` and run.
3. **Paper #3 (AutoSurvey)** shows a more ambitious goal: not just answering questions, but automatically writing complete surveys.
4. **Paper #4 (ScholarCopilot)** represents a new trend: deep integration of retrieval and writing.
5. **Paper #5 (RA-ISF)** is a methodological contribution — iterative self-feedback can improve synthesis quality regardless of which system you use.
6. Understanding **RAG (Retrieval-Augmented Generation)** basics is recommended before reading these. See [RAG original paper](https://arxiv.org/abs/2005.11401).

<section id="synthesis-extended"></section>

## Extended Reading

| Resource | Link | Description |
|---|---|---|
| Semantic Scholar Open Data | [website](https://www.semanticscholar.org/product/api) | Allen AI scientific literature API |
| RAG Original Paper | [arXiv](https://arxiv.org/abs/2005.11401) | Foundational RAG paper |
| Awesome RAG | [repo](https://github.com/hymie122/RAG-Survey) | RAG survey and paper list |
| Elicit | [website](https://elicit.com/) | AI literature assistant for researchers |
| Consensus | [website](https://consensus.app/) | AI-powered scientific literature search |
| OpenAlex | [website](https://openalex.org/) | Open academic literature metadata platform |
| Grobid | [GitHub](https://github.com/kermitt2/grobid) | Scientific PDF structured parsing tool |
| LlamaIndex | [GitHub](https://github.com/run-llama/llama_index) | General RAG framework |

---

> **Home**: [README](../README.md) · **Prev**: [Ideation](./ideation.md) · **Next**: [Experiment](./experiment.md)
