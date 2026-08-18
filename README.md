# Robust Chart Information Extraction via an LVLM Ensemble and Pairwise Reasoning

[![Paper](https://img.shields.io/badge/Paper-ACM%20CIKM%202026-blue)]()
[![Code](https://img.shields.io/badge/Code-GitHub-orange)](https://github.com/TIBHannover/chart-information-extraction)
[![License](https://img.shields.io/badge/License-GPL%203.0-green)](./LICENSE)

This is the official GitHub page for the paper.

Accepted at the **35th ACM International Conference on Information and Knowledge Management (CIKM 2026)**.

---

## Abstract

Data visualizations are essential for communicating findings in scientific literature since they convey significant insights such as experimental results, trends, and distributions. However, due to the diverse nature of charts in real-world settings, automatic chart information extraction (CIE) remains challenging. Current state-of-the-art models demonstrate limited generalization across a variety of charts and benchmarks, performing adequately on basic chart types but failing to recognize complex visualizations, particularly when the characteristics (e.g., resolution, axis, complexity) differ from the datasets used to train them. To address these challenges, we make several contributions. (1) We propose an ensemble-based approach that aims to leverage the synergies of models trained for CIE and general-purpose large vision-language models (LVLMs). (2) We propose several inference strategies for our ensemble approach, including a multiple choice and two binary choice approaches based on league- and tournament-style inference to prevent excessive context length and positional bias of generative AI models. (3) For a fair comparison, we suggest a novel evaluation metric that resolves fundamental problems of existing metrics used for CIE task. (4) Experimental results demonstrate that our proposed ensemble approach can efficiently leverage synergies across various models achieving superior results and generalization across four benchmarks in comparison to the state of the art.

