---
title: A benchmark comparison of deterministic and probabilistic methods for defining
  manual review datasets in duplicate records reconciliation
authors:
- Erel Joffe
- Michael J. Byrne
- Phillip Reeder
- Jorge R. Herskovic
- Craig W. Johnson
- Allison B. McCoy
- Dean F. Sittig
- Elmer V. Bernstam
date: '2014-01-01'
publishDate: '2024-02-20T22:32:19.134720Z'
publication_types:
- article-journal
publication: '*Journal of the American Medical Informatics Association: JAMIA*'
doi: 10.1136/amiajnl-2013-001744
abstract: 'INTRODUCTION: Clinical databases require accurate entity resolution (ER).
  One approach is to use algorithms that assign questionable cases to manual review.
  Few studies have compared the performance of common algorithms for such a task.
  Furthermore, previous work has been limited by a lack of objective methods for setting
  algorithm parameters. We compared the performance of common ER algorithms: using
  algorithmic optimization, rather than manual parameter tuning, and on two-threshold
  classification (match/manual review/non-match) as well as single-threshold (match/non-match).
  METHODS: We manually reviewed 20,000 randomly selected, potential duplicate record-pairs
  to identify matches (10,000 training set, 10,000 test set). We evaluated the probabilistic
  expectation maximization, simple deterministic and fuzzy inference engine (FIE)
  algorithms. We used particle swarm to optimize algorithm parameters for a single
  and for two thresholds. We ran 10 iterations of optimization using the training
  set and report averaged performance against the test set. RESULTS: The overall estimated
  duplicate rate was 6%. FIE and simple deterministic algorithms allowed a lower manual
  review set compared to the probabilistic method (FIE 1.9%, simple deterministic
  2.5%, probabilistic 3.6%; ptextless0.001). For a single threshold, the simple deterministic
  algorithm performed better than the probabilistic method (positive predictive value
  0.956 vs 0.887, sensitivity 0.985 vs 0.887, ptextless0.001). ER with FIE classifies
  98.1% of record-pairs correctly (1/10,000 error rate), assigning the remainder to
  manual review. CONCLUSIONS: Optimized deterministic algorithms outperform the probabilistic
  method. There is a strong case for considering optimized deterministic methods for
  ER.'
tags:
- Algorithms
- Benchmarking
- Electronic Health Records
- Fuzzy Logic
- Humans
- Medical Record Linkage
- Medical Record Linkage [N04.452.859.564.550]
- Medical Records Systems
- Computerized [L01.700.508.300.695]
- Probability
---
