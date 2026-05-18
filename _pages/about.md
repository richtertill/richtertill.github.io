---
layout: about
title: about
permalink: /
subtitle: Ph.D. researcher in self-supervised learning for cell biology &middot; TUM &middot; Helmholtz Munich

profile:
  align: right
  image: Till_lab_min.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p><strong>Till Richter</strong></p>
    <p>Ph.D. Candidate, Machine Learning</p>
    <p>TUM &middot; Helmholtz Munich</p>
    <p>MUDS &middot; MCML &middot; MDSI</p>

news: true # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

keywords: Till Richter, self-supervised learning, SSL, single-cell genomics, computational biology, foundation models, virtual cell, multimodal learning, flow matching, neural ODEs, TUM, Helmholtz Munich, MUDS, MCML, Fabian Theis, Niki Kilbertus, Yoshua Bengio
description: Till Richter is a Ph.D. researcher at TU Munich and Helmholtz Munich working on self-supervised learning, multimodal foundation models, and generative dynamics for single-cell and spatial omics. Advised by Fabian Theis, Niki Kilbertus, and Yoshua Bengio.
---

I am **Till Richter**, a [MUDS](https://www.mu-ds.de/) Ph.D. researcher at the [Technical University of Munich (TUM)](https://www.tum.de/) and [Helmholtz Munich](https://www.helmholtz-munich.de/), advised by [Fabian Theis](https://www.helmholtz-munich.de/en/icb/fabian-theis), [Niki Kilbertus](https://nikikilbertus.info/), and [Yoshua Bengio](https://yoshuabengio.org/). I am also a member of the [Munich Center for Machine Learning (MCML)](https://mcml.ai/) and the [Munich Data Science Institute (MDSI)](https://www.mdsi.tum.de/en/mdsi/home/), and I collaborate with the [Causal Cell Dynamics Lab](https://www.causalcelldynamics.org/) (Helmholtz Munich &middot; MILA Montreal). In 2025 I was a research intern at [Microsoft Research](https://www.microsoft.com/en-us/research/) in Cambridge, MA, working with Lorin Crawford on multimodal cell foundation models.

#### What I work on &mdash; self-supervised learning as a design principle for biology

Biological systems are **multimodal, multiscale, and dynamic**, and most of their structure is conditional rather than marginal: which genes are co-regulated, how morphology constrains transcription, how a cell state evolves into the next. Traditional unsupervised methods optimize the marginal likelihood of the data and end up allocating capacity to whatever dominates variance &mdash; often library size, batch, or donor &mdash; rather than to the conditional dependencies that define biological mechanism.

My research argues for a shift from *describing* the data distribution to *predicting* within it: **structured self-supervised learning (SSL) as a unifying inductive bias** for cellular biology. Concretely, I build models across three increasingly complex scales:

- **Static representations.** Masked-prediction SSL learns transcriptomic representations that transfer across donors, tissues, and technologies because the objective forces the model to encode gene&ndash;gene regulatory dependencies rather than technical correlations [(*Nature Machine Intelligence*, 2024)](https://www.nature.com/articles/s42256-024-00934-3).
- **Compositional multimodal models.** Paired multimodal data is orders of magnitude scarcer than unimodal atlases. I work on **compositional foundation models** that fuse frozen unimodal experts through learned interfaces [(*Cell Systems*, 2026)](https://www.sciencedirect.com/science/article/pii/S2405471226000165), and show theoretically and empirically that standard alignment objectives collapse to *linear redundancy* &mdash; motivating **synergy-aware integration** measured with the Synergistic Information Score (SIS) [(preprint, 2026)](https://www.biorxiv.org/content/10.64898/2026.02.23.707420v3).
- **Cellular dynamics.** I extend self-supervision into time with hybrid symbolic-neural models and flow matching, where orthogonality and sparsity constraints recover identifiable, mechanistically meaningful vector fields from snapshot data [(*Communications Biology*, 2026)](https://www.nature.com/articles/s42003-026-09758-w).

Together, these projects target a single thesis: representations that capture **predictive structure** transfer; representations that merely compress **distributional structure** do not. This is the foundation I am building toward predictive, *in silico* models of the cell.

#### Beyond research

I co-organize the [**Learning Meaningful Representations of Life (LMRL)**](https://www.lmrl.org/) workshop at ICLR ([2025 Singapore](https://www.lmrl.org/), [2026 Rio de Janeiro](https://www.lmrl.org/)), and I have co-organized the Explainable ML in Bioinformatics workshop at ECCB. At TUM I teach the **Statistical Learning** master's course (SS24, WS25) and organize the **Deep Learning Seminar** (since WS24, currently SS26). I mentor interns, working students, and thesis students at Helmholtz Munich. Through the [Manage&amp;More](https://www.manageandmore.de/) scholarship at UnternehmerTUM I work on innovation projects at the intersection of AI and industry, and I volunteer with [KI macht Schule!](https://ki-macht-schule.de/) to teach AI in high schools.

Feel free to reach out about research, collaborations, or PhD/internship questions &mdash; you can find my email and socials below.
