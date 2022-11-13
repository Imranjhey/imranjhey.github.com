---
layout: page
mathjax: true
categories: media
title: ""
---


## Publications and preprints


### An exact quantum hidden subgroup algorithm and applications to solvable groups
Authors: Muhammd Imran & [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/). <br>The paper is available in [Quantum Information and Computation](https://doi.org/10.26421/QIC22.9-10-4) or the preprint version in [arXiv](https://arxiv.org/pdf/2202.04047.pdf).

The natural characteristic of quantul algroithms is probabilistic, since it takes advantage from the quantum principles (superposition, interference, entanglement, etc.). The common technique to boost up the success probability of quantum algorithms is amplitude amplification which is a generalization of Grover's algorithm. Therefore, it is a natural question whether it is possible to boost up the probability to certainty while maintaining the efficiency. In the hidden subgroup problem, the existing of exact quantum algorithms is still limited:
* The exact quantum hidden subgroup algorithm in $\mathbb{Z}_2^n$ by Brassard and Hoyer in [BH97](https://arxiv.org/abs/quant-ph/9704027);
* The exact quantum algorithm for discrete logarithm problem in abelian groups of known order by Mosca and Zalka in [MZ03](https://arxiv.org/abs/quant-ph/0301093).

In this paper, we construct an exact quantum algorithm for the hidden subgroup problem in the infinite family of groups $\mathbb{Z}_{m^k}^n$. Even for $m=3$ and $k=1$, our algorithm is appear to be new. Moreover, we provide the applications of the algorithm in some computational problems in solvable groups such as membership testing, the construction of normal series, etc.

### An exact quantum order finding algorithm and its applications
Author: Muhammad Imran. <br>The preprint version is available in [arXiv](https://arxiv.org/pdf/2205.04240.pdf).

The main key of Shor's algorithm for factoring integers $m$ is a quantum algorithm for finding order of elements in the unit group $\mathbb{Z}_m^*$ of the group of integer modulo $m$. However, the quantum algorithm is polynomial-time in the expected sense, which means it may fail with a small probability and in the unlucky case may take a very long time to succeed, even may never terminate. By the observation that knowing a multiple of the group order $\varphi(m)$ would factor $m$ in randomized classical polynomial time, finding orders of group elements with a known multiple of the order is not necessarily as hard as factoring, so a multiple of the order may be a good help for derandomizition of the quantum algorithm for order finding problem. Some computational problems where such a help available are primality testing problem and the problem of finding primitive elements in arbitrary finite field $\mathbb{F}_q$. However, such a help is not available for factoring problem as $\varphi(m)$ is unknown in general. 
---

## Research in progress

### Zero sum subsets and hidden subgroup problem
Authors: Muhammd Imran & [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/).
  
In this project, we succeed to construct the first exact quantum hidden subgroup algorithm for a class of non-abelian groups, namely nilpotent groups of constant nilpotency class and of smooth order. The main key of the algorithm is by series of reductions to groups of smaller nilpotency class (through its central series) using new zero sum subset algorithm in the group $\mathbb{Z}_p^n$ for prime number $p$.

### An HSP-based quantum attack on isogeny-based cryptography
Author: Muhammad Imran, [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/), & [Péter Kutas](https://sites.google.com/view/peterkutas89/main-page?authuser=0).

In this project, we observe a reduction from isogeny problem to some variants of hidden subgroup problem, namely the Borel hidden subgroup problem ([see here](https://arxiv.org/abs/1105.4416)), the affine hidden subgroup ([see here](https://arxiv.org/abs/quant-ph/0211124)), and multishift problem ([see here](https://drops.dagstuhl.de/opus/volltexte/2018/9529/)). Moreover, we provide a new classical algorithm and also an efficient quantum algorithm for the Borel hidden subgroup problem. This is actually a follow up from the previous result obtained by Péter Kutas et al ([KMPW21](https://eprint.iacr.org/2021/282.pdf)) in which they provide a reduction from isogeny problem to the hidden shift problem where Kuperberg's subexponential algorithm is available ([see here](https://arxiv.org/abs/quant-ph/0302112)). As application, we break a family of isogeny-based cryptography: [$p$SIDH](https://eprint.iacr.org/2021/1600.pdf) that will be presented this December in [ASIACRYPT2022](https://asiacrypt.iacr.org/2022/).
---
## Lecture notes & systematic literature reviews

### Hidden subgroup problem in cryptography: a survey
Author: Muhammad Imran

In this survey, we conduct a systematic literature review on the most recent and important development in classical and quantum algorithms for some instances of finite hidden subgroup problem which have strong connections with cryptography: lattice-based cryptography, isogeny-based cryptography, and some secure cryptographic protocols. The main purpose of this survey is to give cryptographic motivations for further investigations on finite hidden subgroup problem.
---
