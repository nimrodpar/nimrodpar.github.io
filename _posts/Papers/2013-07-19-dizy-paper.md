---
title: Abstract Semantic Differencing for Numerical Programs
author: Nimrod Partush
date: Jul 19, 2013
categories: [Papers]
tags: [static-analysis, abstract-interpretation, differential, c]
math: false
---

First [paper](/assets/publications/dizy.pdf) accepted 🥳 in [SAS 13"](https://www.microsoft.com/en-us/research/publication/proceedings-of-the-20th-static-analysis-symposium/)!

**[Slides](/assets/presentations/dizy-sas13.pdf)**

**Collaborator(s)**: Eran Yahav

**Abstract**: _We address the problem of computing semantic differences between
          a program and a patched version of the program. Our goal is to obtain a precise
          characterization of the difference between program versions, or establish their
          equivalence when no difference exists.
          We focus on computing semantic differences in numerical programs where the
          values of variables have no a-priori bounds, and use abstract interpretation to
          compute an over-approximation of program differences. Computing differences
          and establishing equivalence under abstraction requires abstracting relationships
          between variables in the two programs. Towards that end, we first construct a
          correlating program in which these relationships can be tracked, and then use
          a correlating abstract domain to compute a sound approximation of these relationships.
          To better establish equivalence between correlated variables and precisely
          capture differences, our domain has to represent non-convex information
          using a partially-disjunctive abstract domain. To balance precision and cost of
          this representation, our domain over-approximates numerical information while
          preserving equivalence between correlated variables by dynamically partitioning
          the disjunctive state according to equivalence criteria.
          We have implemented our approach in a tool called DIZY, and applied it to a
          number of real-world examples, including programs from the GNU core utilities,
          Mozilla Firefox and the Linux Kernel. Our evaluation shows that DIZY often
          manages to establish equivalence, describes precise approximation of semantic
          differences when difference exists, and reports only a few false differences._
