---
title: Binary Similarity Detection Using Machine Learning
author: Nimrod Partush
date: Oct 19, 2018
categories: [Papers]
tags: [static-analysis, binary-code, similarity, machine-learning]
math: false
---

[Paper](/assets/publications/zeek.pdf) accepted in [PLAS 18"](http://plas2018.dcc.ufmg.br/).

**Collaborator(s)**: Noam Shalev

**Abstract**: _Finding similar procedures in stripped binaries has various
               use cases in the domains of cyber security and intellectual
               property. Previous works have attended this problem and
               came up with approaches that either trade throughput for
               accuracy or address a more relaxed problem.
               In this paper, we present a cross-compiler-and-architecture
               approach for detecting similarity between binary procedures,
               which achieves both high accuracy and peerless throughput.
               For this purpose, we employ machine learning alongside similarity by composition: we decompose the code into smaller
               comparable fragments, transform these fragments to vectors,
               and build machine learning-based predictors for detecting
               similarity between vectors that originate from similar procedures.
               We implement our approach in a tool called Zeek and
               evaluate it by searching similarities in open source projects
               that we crawl from the world-wide-web. Our results show
               that we perform 250X faster than state-of-the-art without
               harming accuracy._
