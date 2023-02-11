---
layout: page
mathjax: true
categories: media
title: ""
---


## Publications and preprints

---
### An exact quantum hidden subgroup algorithm and applications to solvable groups
Authors: [Muhammd Imran](https://muh-imran.github.io) & [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/). <br>The paper is available in [Quantum Information and Computation](https://doi.org/10.26421/QIC22.9-10-4) or the preprint version in [arXiv](https://arxiv.org/pdf/2202.04047.pdf).

The natural characteristic of quantul algroithms is probabilistic, since it takes advantage from the quantum principles (superposition, interference, entanglement, etc.). The common technique to boost up the success probability of quantum algorithms is amplitude amplification which is a generalization of Grover's algorithm. Therefore, it is a natural question whether it is possible to boost up the probability to certainty while maintaining the efficiency. In the hidden subgroup problem, the existing of exact quantum algorithms is still limited:
* The exact quantum hidden subgroup algorithm in $\mathbb{Z}_2^n$ by Brassard and Hoyer in [BH97](https://arxiv.org/abs/quant-ph/9704027);
* The exact quantum algorithm for discrete logarithm problem in abelian groups of known order by Mosca and Zalka in [MZ03](https://arxiv.org/abs/quant-ph/0301093).

In this paper, we construct an exact quantum algorithm for the hidden subgroup problem in the infinite family of groups $\mathbb{Z}_{m^k}^n$. Even for $m=3$ and $k=1$, our algorithm is appear to be new. Moreover, we provide the applications of the algorithm in some computational problems in solvable groups such as membership testing, the construction of normal series, etc.

---
### An exact quantum order finding algorithm and its applications
Author: [Muhammad Imran](https://muh-imran.github.io). <br>The preprint version is available in [arXiv](https://arxiv.org/pdf/2205.04240.pdf).

The main key of Shor's algorithm for factoring integers $m$ is a quantum algorithm for finding order of elements in the unit group $\mathbb{Z}_m^*$ of the group of integer modulo $m$. However, the quantum algorithm is polynomial-time in the expected sense, which means it may fail with a small probability and in the unlucky case may take a very long time to succeed, even may never terminate. By the observation that knowing a multiple of the group order $\varphi(m)$ would factor $m$ in randomized classical polynomial time, finding orders of group elements with a known multiple of the order is not necessarily as hard as factoring, so a multiple of the order may be a good help for derandomizition of the quantum algorithm for order finding problem. Some computational problems where such a help available are primality testing problem and the problem of finding primitive elements in arbitrary finite field $\mathbb{F}_q$. However, such a help is not available for factoring problem as $\varphi(m)$ is unknown in general. 

---

## Research in progress

---
### Zero sum subsets and hidden subgroup problem
Authors: [Muhammd Imran](https://muh-imran.github.io) & [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/).
  
In this project, we succeed to construct the first exact quantum hidden subgroup algorithm for a class of non-abelian groups, namely nilpotent groups of constant nilpotency class and of smooth order. The main key of the algorithm is by series of reductions to groups of smaller nilpotency class (through its central series) using new zero sum subset algorithm in the group $\mathbb{Z}_p^n$ for prime number $p$.

---
### On the endomorphism ring group action evaluation problem
Author: [Muhammad Imran](https://muh-imran.github.io), [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/), [Péter Kutas](https://sites.google.com/view/peterkutas89/main-page?authuser=0), & [Antonin Leroux](http://www.lix.polytechnique.fr/Labo/Antonin.LEROUX/).

This paper studies the problem of computing the endomorphism ring of the codomain of a secret isogeny between supersingular curves in characteristic $p$ given a representation for this isogeny, i.e. a way to evaluate this isogeny on any torsion point. This problem that we call IsERP (for Isogeny to Endomorphism Ring Problem) plays a central role in isogeny-based cryptography. Some special version of it (where the degree is smooth) is at the heart of the recent attacks that broke the SIDH key exchange, and these attacks exploit an efficient algorithm to solve the IsERP in the smooth-degree case. 

However, no efficient algorithm is known to solve the IsERP for a generic degree, and the hardest case seems to be when the degree is prime. The key exchange pSIDH recently proposed by Leroux bases its security on the prime-degree version of the IsERP.   

In this paper, we study the security of the generic IsERP by proving a quantum polynomial-time reduction from the Quaternion Powersmooth Lifting Problem (PQLP), a problem of finding elements of powersmooth norm and specific shape in maximal orders of the quaternion algebra ramified at $p$ and $\infty$, to the IsERP. A special easy version of the PQLP appears in the context of the KLPT algorithm from Kohel, Lauter, Petit and Tignol, but the generic case remains hard. Our best algorithm has sub-exponential complexity and thus does not reduce the hardness of the generic IsERP, but our reduction does provide a new angle, based on different objects, to attack the IsERP. Moreover, we prove that solving the PQLP can be done efficiently after solving a logarithmic number of related instances, thus providing a way to solve the IsERP (with fixed degree and starting curve) efficiently after a sub-exponential precomputation.   
    
Our reduction is obtained through an interesting intermediate result : a quantum equivalence between the IsERP and a group action evaluation problem that already appeared in the context of the cryptanalysis of SIDH.

---

## Lecture notes & systematic literature reviews

---
### Hidden subgroup problem in cryptography: a survey
Author: Muhammad Imran

In this survey, we conduct a systematic literature review on the most recent and important development in classical and quantum algorithms for some instances of finite hidden subgroup problem which have strong connections with cryptography: lattice-based cryptography, isogeny-based cryptography, and some secure cryptographic protocols. The main purpose of this survey is to give cryptographic motivations for further investigations on finite hidden subgroup problem.

---
### Recommended Source for Isogeny-based Cryptography
* <b>Isogeny-Based Cryptography School 2021</b> [[link]](https://isogenyschool2020.co.uk/).
* <b>Leuven Isogeny Days 2022</b> [[link]](https://www.esat.kuleuven.be/cosic/projects/isocrypt/workshops/)

---
