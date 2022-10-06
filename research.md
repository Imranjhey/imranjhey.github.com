---
layout: page
mathjax: true
title: ""
---
<h2><u>Publications and preprints</u></h2>

<h3> <b>An exact quantum hidden subgroup algorithm and applications to solvable groups</b></h3>
Authors: Muhammd Imran & <a href="http://old.sztaki.hu/~ivanyos/">Gábor Ivanyos</a>. <br>The paper is available in <a href="https://doi.org/10.26421/QIC22.9-10-4">Quantum Information and Computation</a> or the preprint version in <a href="https://arxiv.org/pdf/2202.04047.pdf(https://arxiv.org/pdf/2202.04047.pdf)">arXiv</a>.

The natural property of quantum algorithms is probabilistic because we take advantage from the quantum principles (superposition, interference, entanglement, etc.). Therefore, it is a natural question whether a given efficient quantum algorithm can be derandomized and still efficient as it is analogous to derandomizing probabilistic classical algorithms. In the case of hidden subgroup problem, the existing of exact quantum algorithms is still limited:<br>
<li>The exact quantum hidden subgroup algorithm in $\mathbb{Z}_2^n$ by Brassard and Hoyer;</li> 
<li>The exact quantum algorithm for discrete logarithm problem in abelian groups of known order by Mosca. </li>   

The common technique to boost up the success probability of quantum algorithms is amplitude amplification which is a generalization of Grover's algorithm.
In this paper, we construct an exact quantum algorithm for the hidden subgroup in the family of infinite groups $\mathbb{Z}_{m^k}^n$. Even for $m=3$ and $k=1$, our algorithm is appear to be new.

<h3><b>An exact quantum order finding algorithm and its applications</b></h3>
Author: Muhammad Imran. <br>The preprint version is available in <a href="https://arxiv.org/pdf/2202.04047.pdf(https://arxiv.org/pdf/220.04240.pdf)">arXiv</a>.

The main key of Shor's algorithm for factoring integers $m$ is a quantum algorithm for finding order of elements in the unit group of the group of integer modulo $m$. However, the quantum algorithm is polynomial-time in the expected sense, which means it may fail with a small probability
and in the unlucky case may take a very long time to succeed, even may never terminate. By the observation that knowing a multiple of the group oreder $\phi(m)$ would factor $m$ in randomized classical polynomial time, finding orders of group elements with a known multiple of the order is not necessarily as hard as factoring, so a multiple of the order may be a good help for derandomizition of the quantum algorithm for order finding problem. Some computational problems where such a help available are primality testing problem and the problem of finding primitive elements in arbitrary finite field $\mathbb{F}_q$. However, such a help is not available for factoring problem as $\phi(m)$ is unknown in general. 


<h2><u>Research in progress</u></h2>

  <h3> <b>Zero sum subsets and hidden subgroup problem</b></h3>
  Authors: Muhammd Imran & <a href="http://old.sztaki.hu/~ivanyos/">Gábor Ivanyos</a>.
  
  In this project, we succeed to construct the first exact quantum hidden subgroup algorithm for a class of non-abelian groups, namely nilpotent groups of constant nilpotency class and of smooth order. The main key of the algorithm is by series of reductions to groups of smaller nilpotency class (through its central series) using new zero sum subset algorithm in the group $\mathbb{Z_p}^n$ for prim $p$.

<h3><b>An HSP-based quantum attacks on isogeny-based cryptography</b> </h3>
Author: Muhammad Imran, <a href="http://old.sztaki.hu/~ivanyos/">Gábor Ivanyos</a>, & <a href="https://sites.google.com/view/peterkutas89/main-page?authuser=0">Péter Kutas</a>.

In this project, we observe a reduction from isogeny problem to some variants of hidden subgroup problem, namely the Borel hidden subgroup problem. Moreover, we provide a new classical algorithm and also an efficient quantum algorithm for the Borel hidden subgroup problem. This is actually a follow up from the previous result obtained by Péter Kutas et al ([see](https://eprint.iacr.org/2021/282.pdf)) in which they provide a reduction from isogeny problem to hidden shift problem where Kuperberg's subexponential algorithm available.
