<h1 align="center">Vibe Research Guide<br>文献综合篇 Literature Synthesis</h1>

> Literature Synthesis 关注如何**让 LLM 系统性地阅读、理解和综合大量科学文献**，产出有引用支撑的综述性回答或报告。这是 Vibe Research 中最接近"文献阅读自动化"的方向——它不只是问答，而是要做到 citation-backed、factual、comprehensive 的文献综合。

<section id="synthesis-papers"></section>

## 论文列表

| # | Paper | URL | Type | Why read / 为什么读 | Stage | Keywords |
|---|---|---|---|---|---|---|
| 11 | OpenScholar: Synthesizing Scientific Literature with Retrieval-Augmented Language Models | [arXiv](https://arxiv.org/abs/2411.14199) | RAG / Synthesis | 高质量 scientific literature synthesis 的代表工作。使用 RAG 从海量文献中检索相关段落，生成有引用支撑的综合性回答，在多个科学问答 benchmark 上大幅超越基线。 | Intermediate | RAG, citation-backed synthesis, grounded generation |

<section id="synthesis-recommendations"></section>

## 推荐度

| # | 推荐度 | 说明 |
|---|---|---|
| 11 | ★★★★★ | Must-read，文献综合方向的标杆 |

<section id="synthesis-architecture"></section>

## 核心技术栈

OpenScholar 的核心流程可以理解为：

```
大规模科学文献库
    ↓ (检索)
Retrieval-Augmented Generation (RAG)
    ↓ (生成)
Citation-backed Synthesis Response
    ↓ (验证)
Factual Grounding Check
```

关键设计点：
- **检索**：从大规模科学文献语料中精准检索相关段落
- **生成**：基于检索结果生成综合性回答，每句主张附带引用
- **验证**：确保生成内容有文献支撑，减少幻觉

<section id="synthesis-repos"></section>

## 相关代码仓库

| 项目 | 链接 | 说明 |
|---|---|---|
| OpenScholar | [GitHub](https://github.com/allenai/OpenScholar) | Allen AI 官方开源实现 |

<section id="synthesis-reading-tips"></section>

## 阅读建议

1. 建议先理解 RAG（Retrieval-Augmented Generation）的基本原理再阅读此论文。
2. 重点关注它如何解决科学文献场景下的特有挑战：引用准确性、跨论文信息综合、长文档处理。
3. 如果你想构建 research copilot，OpenScholar 的架构是很好的参考起点。

<section id="synthesis-extended"></section>

## 延伸阅读

| 资源 | 链接 | 说明 |
|---|---|---|
| Semantic Scholar Open Data | [website](https://www.semanticscholar.org/product/api) | Allen AI 的科学文献 API，OpenScholar 底层数据源 |
| PaperQA2 | [GitHub](https://github.com/Future-House/paper-qa) | 另一个科学文献问答系统，强调精确引用 |
| ScholarCopilot | [arXiv](https://arxiv.org/abs/2504.00824) | 检索增强的学术写作助手 |
| Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks | [arXiv](https://arxiv.org/abs/2005.11401) | RAG 原论文，理解底层技术 |
| Awesome RAG | [repo](https://github.com/hymie122/RAG-Survey) | RAG 方向综述与论文列表 |
| Elicit | [website](https://elicit.com/) | 面向研究者的 AI 文献助手产品 |
| Consensus | [website](https://consensus.app/) | AI 驱动的科学文献搜索引擎 |
