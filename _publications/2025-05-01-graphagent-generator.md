---
title: "LLM-Based Multi-Agent Systems are Scalable Graph Generative Models"
collection: publications
category: manuscripts
permalink: /publication/2025-05-01-graphagent-generator
excerpt: 'This work introduces GraphAgent-Generator (GAG), a scalable framework for generating social graphs using LLM-based multi-agent systems.'
date: 2025-05-01
venue: 'To Appear in ACL-2025'
# slidesurl: 'http://arxiv.org/abs/2410.09824'
paperurl: 'http://arxiv.org/abs/2410.09824'
# bibtexurl: 'http://academicpages.github.io/files/bibtex_gag.bib'
# citation: 'Your Name, You. (2025). &quot;LLM-Based Multi-Agent Systems are Scalable Graph Generative Models.&quot; <i>To Appear in Journal of Scalable Graph Models</i>.'
---


<!-- Traditional social graph generation methods are primarily divided into two categories: rule-based methods and deep learning-based methods. Rule-based methods, such as the Erdős–Rényi model and the Barabási–Albert model, simulate certain macroscopic network properties, such as power-law degree distributions. 
Deep learning-based methods, such as GraphRNN and GraphVAE, leverage self-supervised learning to automatically capture complex patterns in graph structures.

While these methods perform well in modeling small-scale graph structures, they face significant challenges when dealing with large-scale, dynamic, and attributed social networks. Since they heavily rely on training data and often suffer from overfitting when generating graphs at scales beyond the training set, making it difficult to generalize to larger graphs with reasonable macroscopic properties. -->

In this work, we propose **GraphAgent-Generator (GAG)**, a social simulation framework tailored for generating social graphs. Inspired by the bipartite modeling approach of affiliation networks, GAG simulates the dynamic expansion of social networks by modeling pairwise interactions between agents and items. We designed the S-RAG algorithm, combined with parallel acceleration, to efficiently generate social graphs. <a href="https://github.com/Ji-Cather/GraphAgent">Source Code.</a>
