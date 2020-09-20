---
layout: post
title: Probability and Measure - 1
tags: [sigma-algebra, measure, measurable, measure space, measurable-function]
author: mjyoo2
---

### Sigma-algebra
---
##### Definition
주어진 $$Set\ X$$에 대하여, $$X$$의 모든 $$subset$$의 $$collection$$인 $$C$$의 부분집합 $$S$$가 있을 때, 아래의 조건을 만족하면 $$\sigma\text{-}algebra\ on\ X$$라 한다.

$$ 1.\ S \neq \emptyset$$
$$ 2.\ For\ all\ s \in S, s^c \in S$$
$$ 3.\ Let\ s_1,\ s_2, ... \in S, then\ \bigcup_{i} s_i \in S$$

### Measure
---
##### Definition
주어진 $$Set\ X$$에 대하여 $$S$$를 $$\sigma\text{-}algebra\ on\ X$$라 하자, 함수 $$\mu$$가 있어서, $$\mu : S \to \mathbb{R} \cup \left\{\infty\right\}$$이면, 일 때, 아래와 같은 특성을 가지면 이를 $$measure$$라고 한다.

$$1.\ 모든\ S의\ element\ E에\ 대하여, \mu\left(E\right)\geq 0$$
$$2.\ \mu\left(\emptyset\right) = 0$$
$$3.\ 모든\ pairwise\ disjoint\ set의\ countable한$ $\ collection$$ $$\left\{E_k\right\}_{k=1}^{\infty} 에\ 대하여\ \mu\left(\bigcup_{k=1}^{\infty}E_k\right) = \sum_{k=1}^{\infty} \mu\left(E_k\right)$$

$$위\ 3번을\ 가산가법적\ 특성\ 이라\ 한다.\ (contable\ additivity)$$

이 때, $$\left(X, S\right)$$ 를 $measurable\ space$라 하고, $$\left(X, S, \mu\right)$$ 를 $$measure\ space$$라 한다.

### Measurable function
---
##### Definition
주어진 $$Set\ X,\ Y$$ 위의 $$\sigma\text{-}algebra\ S,\ T$$ 가 존재한다. ($$measurable\ space\ (X, S),\ (Y, T)$$) 이 때, 아래 조건의 만족하는 함수 $$f: X \to Y$$ 를 $$measurable\ function$$이라고 한다.
$$for\ every\ E\in T\ the\ pre\text{-}image\ of\ E\ under\ f\ is\ in\ S,$$ $$,f^{-1}\left(E\right):= \left\{x \in X|f\left(x\right)\in E\right\} \in S$$
