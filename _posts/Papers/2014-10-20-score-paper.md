---
title: Abstract Semantic Differencing via Speculative Correlation
author: Nimrod Partush
date: Oct 20, 2014
categories: [Papers]
tags: [static-analysis, abstract-interpretation, differential, c]
math: false
---

Another [paper](/assets/publications/score.pdf) dealing with abstract differencing accepted in [OOPSLA 14"](https://2014.splashcon.org/track/oopsla2014).

**[Slides](/assets/presentations/score-oopsla14.pdf)**

**Collaborator(s)**: Eran Yahav

**Abstract**: _We address the problem of computing semantic differences
           between a program and a patched version of the
           program. Our goal is to obtain a precise characterization
           of the difference between program versions, or establish
           their equivalence. We focus on infinite-state numerical programs,
           and use abstract interpretation to compute an overapproximation
           of program differences.
           Computing differences and establishing equivalence under
           abstraction requires abstracting relationships between
           variables in the two programs. Towards that end, we use a
           correlating abstract domain to compute a sound approximation
           of these relationships which captures semantic difference.
           This approximation can be computed over any interleaving
           of the two programs. However, the choice of interleaving
           can significantly affect precision.We present a speculative
           search algorithm that aims to find an interleaving of
           the two programs with minimal abstract semantic difference.
           This method is unique as it allows the analysis to dynamically
           alternate between several interleavings.
           We have implemented our approach and applied it to realworld
           examples including patches from Git, GNU Coreutils,
           as well as a few handpicked patches from the Linux kernel
           and the Mozilla Firefox web browser. Our evaluation shows
           that we compute precise approximations of semantic differences,
           and report few false differences._
