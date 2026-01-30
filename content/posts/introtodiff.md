---
title: "A Friendly Introduction to Differential Equations"
categories: ["Differential Equations","Archive"]
date: 2026-01-20
author: "Selim Kaan Ozsoy, Middle East Technical University"
math: true
draft: false
---
The key to jump into differential equations is to first understand the meaning of differentials in the first place. Consider $ dx $ or $ dy $, do they have a considerable meaning alone? The answer to this question is both yes and no, and this is actually one of some concepts which mathematicians and engineers, or applied mathematicians prefer dealing in different ways. 
In prereqruisite calculus, the reader studied differentiation and is familiar with the expression $\frac{dy}{dx}$. This mathematical expression tells us how fast the dependent variable $y$ changes.  
&emsp;In the study of differential equations, the symbols $dx$ and $dy$ will be treated as if they were fractions rather than operators, and we will assume that basic algebraic manipulations apply to these expressions.   
&emsp;It should be understood, however, that each such manipulation is ultimately justified by fundamental results of calculus, such as the chain rule or the manipulations of the limit definition of derivatives. Here, for simplicity, these justifications will not be proved, and will rely instead on intuitive reasoning. From now on, under these circumstances, we call $dx$, where $x$ is the expression of any variable, a differential.   
&emsp;Now, let's talk about the equations that involve differentials, which are evidently called differential equations. Consider $$\frac{dy}{dx}=2$$
This is a familiar expression. We infer, here, letting $y$ be the dependent variable, that an infinitesimal change in $x$, say $dx$, results in a change of $2dx$ in $y$. But also, we can infer that the derivative of such $y$ is equal to 2 in the corresponding domain, everywhere. Considering these, we can furthermore evolve our understanding and say $y$ is a function of $x$ and it is of the form $y(x)= 2x + C $, where C is a constant. Apparently, C can take any value, so long as it is a arbitrary constant, since the derivative of C with respect to $x$ is identically zero.  

&emsp;But now, let's go beyond the usual. Consider: $$\frac{dy}{dx}=2x$$ Here, the rate of change of the variable $y$ is given by an expression of another variable, $x$. That is, the behaviour of $y$ at each point depends explicitly on the value of $x$ at that point.  



<div style="text-align: center; margin: 2em auto; width: 100%; max-width: 500px;">
<svg viewBox="0 0 400 300" xmlns="http://www.w3.org/2000/svg" 
style="width: 100%; height: auto; font-family: 'Times New Roman', Times, serif;">

<g stroke="currentColor" stroke-width="1.5">
<line x1="20" y1="150" x2="380" y2="150" /> <polygon points="380,150 370,145 370,155" fill="currentColor" stroke="none" />
<line x1="200" y1="280" x2="200" y2="20" /> <polygon points="200,20 195,30 205,30" fill="currentColor" stroke="none" />
</g>

<line x1="120" y1="280" x2="280" y2="20" stroke="currentColor" stroke-width="1" stroke-opacity="0.6" />

<g fill="currentColor" font-size="16">

<g text-anchor="middle" dominant-baseline="hanging">
    <text x="100" y="165">-4</text>
    <text x="150" y="165">-2</text>
    <text x="250" y="165">2</text>
    <text x="300" y="165">4</text>
    <text x="370" y="165" font-style="italic" font-weight="bold">x</text>
</g>

<g text-anchor="end" dominant-baseline="middle">
    <text x="190" y="270">-4</text>
    <text x="190" y="220">-2</text>
    <text x="190" y="100">2</text>
    <text x="190" y="50">4</text>
    <text x="190" y="30" font-style="italic" font-weight="bold">dy/dx</text>
</g>

</g>
</svg>
</div>

Considering these, the reader is encouraged to explore direction fields.