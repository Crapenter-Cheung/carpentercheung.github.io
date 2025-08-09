---
title: 'MacDonald polynomial'
date: 2025-08-09
permalink: /posts/2025/08/mac_poly/
tags:
  - 代数学
  - 组合
  

---
MacDonald polynomial
======
主要参考一下基本册子：
* 最初等的MacDonald多项式的入门，也是最开始介绍MacDonald多项式的册子：[Macdonald. Symmetric functions and Hall polynomials](https://math.berkeley.edu/%7Ecorteel/MATH249/macdonald.pdf).
* MacDonald多项式的入门：[The q,t-Catalan Numbers and the Space of Diagonal Harmonics](https://www2.math.upenn.edu/~jhaglund/books/qtcat.pdf).
* Hilbert scheme和MacDonald多项式的内容：看[Haiman的主页](https://math.berkeley.edu/~mhaiman/)中的两者结合的note便可。这套理论最主要的结果便是：
* Shuffle conjecture的内容
  Shuffle conjecture是指如下命题：
  $$
\displaylines{
(-1)^n \nabla e_n[X] = \sum_{\pi} \sum_{w \in WP_{\pi}} t^{\text{area}(\pi)} q^{\text{dinv}(\pi,w)} x_w 
}
 $$
  * 首先,Shuffle conjecture由Carlsson和Mellit证明，[Link](https://arxiv.org/abs/1508.06239)。但是我推荐初学者阅读的是辛国策老师和Haglund写的一个note：[Lecture notes on the Carlsson-Mellit proof of the shuffle conjecture](https://arxiv.org/pdf/1705.11064)。
  *  Carlsson和Mellit在证明过程中首创了\\(d_{+}\\)和\\(d_{-}\\)算子，后来组合学家们发现他有很多的用处，如：
      1. vertical strip 形状的 LLT多项式的e-positivity，由Adderio借助这套算子，给出了一个并不难的[证明](https://arxiv.org/pdf/1906.02633)。同样借助这套算子，Per Alexandersson给出了这个多项式的[组合e展开式](https://www.sciencedirect.com/science/article/pii/S000187082200072X).
      2. 和色对称函数的关系（3+1 猜想）。Hikita提出了q-chromatic symmetric function，后来Hikita在24年[证明](https://arxiv.org/pdf/2410.12758)了3+1猜想。25年，一些人将q-色对称函数和MacDonald多项式相结合，[重新书写](https://arxiv.org/pdf/2504.06936)了3+1猜想的证明，它和Hikita证明过程中的一些结果是相一致的。(至于为什么二者能结合在一起，因为有人发现：Hikita的q-色对称函数和dyck path有关系。)
  * Rational Shuffle conjecture。
  我只知道是借用扭结证明的，但我对这套理论不大懂。
