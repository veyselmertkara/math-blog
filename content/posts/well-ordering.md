---
title: "Well Ordering Principle"
date: 2026-01-30T19:59:00+03:00
author: "Selim Kaan Ozsoy, Middle East Technical University"
categories: ["Elementary Number Theory","Archive"]
draft: false
---

&emsp;**Well Ordering Principle:** Every nonempty subset of $\mathbb{N}$ has a least element, i.e., there exists $a \in S$ such that $x \geq a$ for all $x \in S$.  
&emsp;This principle may seem a little obvious. The conditions, however, are considerable. Notice that, firstly, we need a nonempty set. The reason is trivial to comprehend, as the empty set has no elements and therefore it cannot have a least element. Furthermore, the set must be a subset of $\mathbb{N}$.  
&emsp;We can consider some sets and determine whether they satisfy the Well Ordering Principle, i.e., they are well ordered.
<br>
&emsp;<span style="color: blue">Example:</span> Consider the set

$$
S=\\{ x \in \mathbb{N} \mid x>4\\}.
$$

&emsp;Here, from the set notation, we conclude that $S$ is a subset of $\mathbb{N}$. Also, we can show that the set is nonempty, as $10 \in \mathbb{N}$ and $10>4$ and therefore $10 \in S$. Hence, the set $S$ satisfies the conditions of Well Ordering Principle and therefore $S$ is well ordered.

Moreover, the least element of $S$ is 5. Since $5 \in S$ and for all $x \in S$, $x \geq 5$.

<br>

&emsp;<span style="color: blue">Example:</span> Consider the set

$$
\\{\dots, -3, -2, -1, 0, 1,2,3,\dots\\}.
$$

&emsp;We can easily see that, letting $S=\\{\dots, -3, -2, -1, 0, 1,2,3,\dots\\}$, $S$ is not a subset of $\mathbb{N}$. We can show this by the fact that $-3 \in S$ and $-3 \notin \mathbb{N}$ and therefore there exists some $x \in S$ such that $x \notin \mathbb{N}$, which implies that $S$ is not a subset of $\mathbb{N}$, by definition of subsets.

However, we cannot deduce that $S$ is not well ordered just because $S$ does not satisfy a condition of Well Ordering Principle. This is a common mistake in mathematical reasoning. Well Ordering Principle says that if a set satisfies some conditions, then it is guaranteed that it has a least element and thus it is a well ordered set, but it does not assert that if a set does not satisfy at least one condition, then it cannot be well ordered.

Here, the reader may say "But $\\{\dots, -3, -2, -1, 0, 1,2,3,\dots\\}$ does not seem well ordered to me." and one could be right. In fact, $\\{\dots, -3, -2, -1, 0, 1,2,3,\dots\\}$ is not well ordered. Then how can we prove it?  
<br>
&emsp;**Well Ordering Proofs:**  
&emsp;Well Ordering proofs mainly consist of two types of proofs. In the first one, we show that a set is well ordered by showing the corresponding set satisfies the conditions of Well Ordering Principle. In the latter one, we show that the set is not well ordered by a contradiction, i.e., we first assume that the set is well ordered, and then obtain a contradiction from such an assumption.

<br>

<span style="color: blue">Example:</span> Show that

$$
S=\\{\dots, -3, -2, -1, 0, 1,2,3,\dots\\}
$$

is not well ordered.

&emsp;<span style="color: orange">Solution:</span>  
&emsp;Assume towards a contradiction that $S$ is a well ordered set. Then $S$ has a least element. Let $x$ be the least element of $S$. Then, we get $x \in S$ and for all $a \in S$, $a \geq x$.

Here, it is clear that $S=\mathbb{Z}$ and since $x \in S$, $x-1 \in S$, as both $x$ and $x-1$ are integers. But then, $x-1 < x$, which is a contradiction to the fact that "for all $a \in S$, $a \geq x$". Therefore, by proof by contradiction, $S$ is not well ordered.

<br>

**Definition.** Theorem is a statement which is true and can be proven.

<br>

**Theorem.** If $a,b \in \mathbb{N}$, then there exists $n \in \mathbb{N}$ such that $na \geq b$.

This theorem is also called the Archimedean Property of Integers.

**Proof.**
Suppose towards a contradiction that the theorem is false and therefore there exist some natural numbers $a,b$ such that $na < b$ for all $n \in \mathbb{N}$.  
&emsp;Let $S$ be the set given by

$$
S=\\{b-na \mid n \in \mathbb{N}, b-na>0\\}.
$$

Observe that $S$ is a subset of $\mathbb{N}$, since $b,n,a \in \mathbb{N}$ and so $b-na \in \mathbb{Z}$ (and since it is $>0$, it is in $\mathbb{N}$). Furthermore, assuming that $n=1 \in \mathbb{N}$ and $b>a$ and so $b-a>0$, we have $b-a \in S$. Therefore, $S$ is nonempty. Hence, according to Well Ordering Principle, $S$ has a least element.

Let $x$ be the least element of $S$. Hence, by definition of $S$, $x=b-\tilde{n}a$ for some arbitrary $\tilde{n} \in \mathbb{N}$. But then, $b-(\tilde{n}+1)a$ is also an element of $S$. It follows that $b-(\tilde{n}+1)a < b-\tilde{n}a$, which contradicts the fact that $b-\tilde{n}a$ is the least element of $S$.

{{< pdf "Well_Ordering_Principle.pdf" >}}