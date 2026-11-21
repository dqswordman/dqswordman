<a href="https://dqswordman.github.io/">
  <picture>
    <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/dqswordman/dqswordman/main/assets/research-cover-mobile.png">
    <img src="assets/research-cover.png" alt="Wenzhang Du · Data mining, RAG &amp; trustworthy machine learning · Visit the research homepage">
  </picture>
</a>

<p>
  <img align="right" alt="Profile views" src="https://komarev.com/ghpvc/?username=dqswordman&amp;color=1b4d3e&amp;style=flat-square&amp;label=VIEWS">
  <a href="https://dqswordman.github.io/"><img alt="Personal website" src="https://img.shields.io/badge/Personal_website-1B4D3E?style=flat-square"></a>
  <a href="https://dqswordman.github.io/zh/"><img alt="中文主页" src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87%E4%B8%BB%E9%A1%B5-263238?style=flat-square"></a>
  <a href="https://scholar.google.com/citations?user=8nLydvUAAAAJ&amp;hl=en"><img alt="Google Scholar" src="https://img.shields.io/badge/Google_Scholar-263238?style=flat-square"></a>
  <a href="https://huggingface.co/DQSWORDMAN"><img alt="Hugging Face profile" src="https://img.shields.io/badge/Hugging_Face-263238?style=flat-square"></a>
  <br clear="right">
</p>

[Selected research](https://dqswordman.github.io/research/#selected) · [Technical reports](https://dqswordman.github.io/technical-reports/) · [Open-source projects](https://dqswordman.github.io/open-source/) · [Open Research Reports](https://dqswordman.github.io/open-research/)

## Selected research

### [Complex Utility, Simple Calibration: Decision Sufficiency in RAG Evidence Selection](https://github.com/dqswordman/rag-decision-sufficiency)

**WSDM 2027** · Accepted · [Project overview](https://dqswordman.github.io/research/decision-sufficiency/) · [Publication record](https://dqswordman.github.io/#paper-decision-sufficiency)

Across **180 questions and 1,440 matched settings**, checking the proposed evidence set reduced mean normalized regret from **0.272 to 0.162** as mean scoring calls rose from **9 to 9.61**. Taking the best already-measured set at nine calls gave **0.213**. This offline evaluation uses reference answers.

[Read the report](https://dqswordman.github.io/technical-reports/decision-sufficiency/) · [中文伴读](https://dqswordman.github.io/zh/technical-reports/decision-sufficiency/) · [Reproduce on CPU](https://github.com/dqswordman/rag-decision-sufficiency/blob/main/docs/reproduction.md)

<p>
  <a href="https://github.com/dqswordman/rag-decision-sufficiency"><img alt="GitHub repository and star count" src="https://img.shields.io/github/stars/dqswordman/rag-decision-sufficiency?style=flat-square&amp;label=GitHub%20stars&amp;labelColor=263238&amp;color=1B4D3E"></a>
  <a href="https://huggingface.co/spaces/DQSWORDMAN/rag-decision-sufficiency"><img alt="Hugging Face Space" src="https://img.shields.io/badge/Hugging_Face-Space-1B4D3E?style=flat-square&amp;labelColor=263238"></a>
  <a href="https://github.com/dqswordman/rag-decision-sufficiency/releases/latest"><img alt="Latest reproducibility release" src="https://img.shields.io/github/v/release/dqswordman/rag-decision-sufficiency?style=flat-square&amp;label=Release&amp;labelColor=263238&amp;color=1B4D3E"></a>
</p>

### [When Is Program Structure Required? Certificate-Grounded Calibration of Program-Induction Difficulty](https://github.com/dqswordman/program-structure-certificates)

**arXiv preprint · November 2026** · [Paper](https://arxiv.org/abs/2611.24975) · [Project overview](https://dqswordman.github.io/research/program-structure-certificates/)

Across **120 reference families**, changing one demonstration can raise the certified minimum program length from one rule to two. With five shared examples, Qwen3-8B completed **67/120** control tasks and **12/120** separation tasks. Its success on a separate hidden witness pair increased by **9.17 percentage points**.

[Technical report](https://dqswordman.github.io/technical-reports/program-structure-certificates/) · [中文伴读](https://dqswordman.github.io/zh/technical-reports/program-structure-certificates/) · [Hugging Face explorer](https://huggingface.co/spaces/DQSWORDMAN/program-structure-certificates) · [GitHub release](https://github.com/dqswordman/program-structure-certificates/releases/tag/v1.0.0)

## Other open-source papers

### [PAIRSAFE: Proxy-Resistant Paired Safety Evaluation for Refusal Boundaries](https://github.com/dqswordman/pairsafe)

**AACL-IJCNLP 2026 · Long Paper** · [Project overview](https://dqswordman.github.io/research/pairsafe/) · [ACL Anthology](https://aclanthology.org/2026.aacl-long.124/)

Qwen ranked **148 of 150** matched pairs correctly. A threshold learned on other pairs classified both members correctly in **132**, and the separate generation check succeeded on **105**.

[Read the report](https://dqswordman.github.io/technical-reports/pairsafe/) · [中文伴读](https://dqswordman.github.io/zh/technical-reports/pairsafe/) · [Reproduce on CPU](https://github.com/dqswordman/pairsafe/blob/v1.0.0/docs/reproduction.md)

<p>
  <a href="https://github.com/dqswordman/pairsafe"><img alt="PAIRSAFE GitHub repository and stars" src="https://img.shields.io/github/stars/dqswordman/pairsafe?style=flat-square&amp;label=GitHub%20stars&amp;labelColor=263238&amp;color=1B4D3E"></a>
  <a href="https://huggingface.co/spaces/DQSWORDMAN/pairsafe"><img alt="PAIRSAFE interactive threshold explorer" src="https://img.shields.io/badge/Hugging_Face-Space-1B4D3E?style=flat-square&amp;labelColor=263238"></a>
  <a href="https://github.com/dqswordman/pairsafe/releases/latest"><img alt="PAIRSAFE versioned CPU release" src="https://img.shields.io/github/v/release/dqswordman/pairsafe?style=flat-square&amp;label=Release&amp;labelColor=263238&amp;color=1B4D3E"></a>
</p>

## Open Research Reports

I share completed studies here when I consider their evidence too narrow for the conference I had in mind. Each release includes the manuscript, its measured results and a CPU reproduction path. [Browse the collection](https://dqswordman.github.io/open-research/) · [中文目录](https://dqswordman.github.io/zh/open-research/) · [Hugging Face collection](https://huggingface.co/collections/DQSWORDMAN/open-research-reports-6b019707aeffeec0b0f43136)

### [From Evidence Scores to RAG Answers: Budget, Search, and Presentation](https://github.com/dqswordman/rag-evidence-selection-paths)

Follow the same RAG question as two passages change order. Across 539 questions, relaxing the passage budget accounts for 4.79 of Mistral’s 5.91 token-F1-point gain.

[PDF](https://dqswordman.github.io/assets/reports/rag-evidence-selection-paths/manuscript.pdf) · [Technical report](https://dqswordman.github.io/technical-reports/rag-evidence-selection-paths/) · [中文技术报告](https://dqswordman.github.io/zh/technical-reports/rag-evidence-selection-paths/) · [Hugging Face](https://huggingface.co/spaces/DQSWORDMAN/rag-evidence-selection-paths) · [Release](https://github.com/dqswordman/rag-evidence-selection-paths/releases/tag/v1.0.1)

### [Beyond Pairwise Overlap: Shared-Value Observations for Compositional Text Embeddings](https://github.com/dqswordman/shared-value-embeddings)

Two 23-state observation plans differ in which city their edits share. On atomic text the shared-value plan reduces reconstruction error by 53.4% for BGE and 36.0% for E5.

[PDF](https://dqswordman.github.io/assets/reports/shared-value-embeddings/manuscript.pdf) · [Technical report](https://dqswordman.github.io/technical-reports/shared-value-embeddings/) · [中文技术报告](https://dqswordman.github.io/zh/technical-reports/shared-value-embeddings/) · [Hugging Face](https://huggingface.co/spaces/DQSWORDMAN/shared-value-embeddings) · [Release](https://github.com/dqswordman/shared-value-embeddings/releases/tag/v1.0.1)

### [When Does Document Replay Help Evidence-State Question Answering?](https://github.com/dqswordman/document-replay-evidence-qa)

On 32 paired worlds, document replay leads closed-book replay by 19.25 percentage points with synthetic attachments and trails by 7.92 points with WikiText. Sixteen fresh worlds preserve both directions.

[PDF](https://dqswordman.github.io/assets/reports/document-replay-evidence-qa/manuscript.pdf) · [Technical report](https://dqswordman.github.io/technical-reports/document-replay-evidence-qa/) · [中文技术报告](https://dqswordman.github.io/zh/technical-reports/document-replay-evidence-qa/) · [Hugging Face](https://huggingface.co/spaces/DQSWORDMAN/document-replay-evidence-qa) · [Release](https://github.com/dqswordman/document-replay-evidence-qa/releases/tag/v1.0.1)

## Research experience

- **Independent Researcher** · Late April 2026 – Present
- **Research Intern, Earth and Space Center** · July 2025 – Late April 2026
