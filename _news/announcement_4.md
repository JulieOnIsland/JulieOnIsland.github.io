---
layout: post
title: Evaluation and optimization of sequence-based gene regulatory deep learning models
date: 2023-04-28 09:00:00-0400
inline: false
related_posts: true
---


## Evaluation and optimization of sequence-based gene regulatory deep learning models

<a href="https://www.biorxiv.org/content/10.1101/2023.04.26.538471v1">[paper]</a>

#### Abstract

Neural networks have proven to be an immensely powerful tool in predicting functional genomic regions, in particular with many recent successes in deciphering gene regulatory logic. However, how model architecture and training strategy choices affect model performance has not been systematically evaluated for genomics models. To address this gap, we held a DREAM Challenge where competitors trained models on a dataset of millions of random promoter DNA sequences and corresponding experimentally determined expression levels to best capture the relationship between regulatory DNA and gene expression in yeast. To robustly evaluate the models, we designed a comprehensive suite of benchmarks encompassing various sequence types. While some benchmarks produced similar results across all models, others differed substantially. For some sequence types, model performances exhibited correlation scores as high as 0.98, while for others, substantial improvement is still required. The top performing models were all neural networks, which demonstrated substantial performance gains by customizing model architectures to the nature of the experiment and utilizing novel training strategies tailored to genomics sequence data. Overall, our DREAM Challenge highlights the need to benchmark genomics models across different scenarios to uncover their limitations. 


