---
layout: page
title: Does RAG Introduce Unfairness in LLMs? Evaluating Fairness in Retrieval-Augmented Generation Systems
description: In this paper, we aim to empirically evaluate fairness in several RAG methods. We propose a fairness evaluation framework tailored to RAG, using scenario-based questions and analyzing disparities across demographic attributes.
img: /assets/img/ragfairness.png
---

<br />

#### Keywords
LLM, RAG, Fairness

<br />

## Abstract

<br />

Retrieval-Augmented Generation (RAG) has recently gained significant attention for its enhanced ability to integrate external knowledge sources into open-domain question answering (QA) tasks. However, it remains unclear how these models address fairness concerns, particularly with respect to sensitive attributes such as gender, geographic location, and other demographic factors. First, as language models evolve to prioritize utility, like improving exact match accuracy, fairness considerations may have been largely overlooked. Second, the complex, multi-component architecture of RAG methods poses challenges in identifying and mitigating biases, as each component is optimized for distinct objectives. In this paper, we aim to empirically evaluate fairness in several RAG methods. We propose a fairness evaluation framework tailored to RAG, using scenario-based questions and analyzing disparities across demographic attributes. Our experimental results indicate that, despite recent advances in utility-driven optimization, fairness issues persist in both the retrieval and generation stages. These findings underscore the need for targeted interventions to address fairness concerns throughout the RAG pipeline. The dataset and code used in this study are publicly available at this GitHub Repository. https://github.com/elviswxy/RAG_fairness

