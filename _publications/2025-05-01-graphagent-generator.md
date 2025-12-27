---
title: "LLM-Based Multi-Agent Systems are Scalable Graph Generative Models"
collection: publications
category: manuscripts
permalink: /publication/2025-05-01-graphagent-generator
excerpt: 'This work introduces GraphAgent-Generator (GAG), a scalable framework for generating social graphs using LLM-based multi-agent systems.'
date: 2025-05-01
venue: 'ACL-2025(findings)'
# slidesurl: 'http://arxiv.org/abs/2410.09824'
paperurl: 'https://aclanthology.org/2025.findings-acl.78/'
bibtexurl: 'https://scholar.googleusercontent.com/scholar.bib?q=info:nsle65QInv0J:scholar.google.com/&output=citation&scisdr=Crylu7caEPSxxoZU1fM:ALhkC2QAAAAAaU9SzfPLAOv-QYDm-vP58gvjpQU&scisig=ALhkC2QAAAAAaU9Szf1vSj9M40V3_vUP97bYRVQ&scisf=4&ct=citation&cd=-1&hl=zh-CN'
# citation: 'Jiarui Ji, You. (2025). &quot;LLM-Based Multi-Agent Systems are Scalable Graph Generative Models.&quot; <i>To Appear in Journal of Scalable Graph Models</i>.'
---


<!-- Traditional social graph generation methods are primarily divided into two categories: rule-based methods and deep learning-based methods. Rule-based methods, such as the Erdős–Rényi model and the Barabási–Albert model, simulate certain macroscopic network properties, such as power-law degree distributions. 
Deep learning-based methods, such as GraphRNN and GraphVAE, leverage self-supervised learning to automatically capture complex patterns in graph structures.

While these methods perform well in modeling small-scale graph structures, they face significant challenges when dealing with large-scale, dynamic, and attributed social networks. Since they heavily rely on training data and often suffer from overfitting when generating graphs at scales beyond the training set, making it difficult to generalize to larger graphs with reasonable macroscopic properties. -->

In this work, we propose **GraphAgent-Generator (GAG)**, a social simulation framework tailored for generating social graphs. Inspired by the bipartite modeling approach of affiliation networks, GAG simulates the dynamic expansion of social networks by modeling pairwise interactions between agents and items. We designed the S-RAG algorithm, combined with parallel acceleration, to efficiently generate social graphs. <a href="https://github.com/Ji-Cather/GraphAgent">Source Code.</a>
