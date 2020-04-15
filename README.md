# The Incredible Solutions

Solutions to the [Incredible Proof Machine](http://incredible.pm/).

- [Session 1](#session-1)
- [Session 2](#session-2)
- [Session 3](#session-3)
- [Session 4](#session-4)
- [Session 5](#session-5)
- [Session 6](#session-6)
- [Session 7](#session-7)
- [Hilbert System](#hilbert-system)
- [NAND Calculus](#nand-calculus)
- [Simply Type Lambda Calculus](#simply-type-lambda-calculus)

## Session 1
<!-- 1.1 -->
$$
A \above 2pt A
$$

<!-- 1.2 -->
$$
A \quad B \above 2pt A
$$

<!-- 1.3 -->
$$
A \quad B \above 2pt B \quad A
$$

<!-- 1.4 -->
$$
A \quad B \above 2pt A\land B
$$

<!-- 1.5 -->
$$
A \above 2pt A\land A
$$

<!-- 1.6 -->
$$
A\land B \above 2pt A
$$

<!-- 1.7 -->
$$
A\land B \above 2pt A \quad B
$$

<!-- 1.8 -->
$$
A\land B \above 2pt A\land B
$$

<!-- 1.9 -->
$$
A\land B \above 2pt B\land A
$$

<!-- 1.10 -->
$$
(A\land B)\land C \above 2pt A \quad B \quad C
$$

<!-- 1.11 -->
$$
(A\land B)\land C \above 2pt A\land C
$$

<!-- 1.12 -->
$$
(A\land B)\land C \above 2pt A\land (B\land C)
$$


## Session 2
<!-- 2.1 -->
$$
A \quad A\to B \above 2pt B
$$

<!-- 2.2 -->
$$
A \quad A\to B \quad B\to C \above 2pt C
$$

<!-- 2.3 -->
$$
A \quad A\to B \quad A\to C \quad B\to D \quad C\to D \above 2pt D
$$

<!-- 2.4 -->
$$
A \quad A\to A \above 2pt A
$$

<!-- 2.5 -->
$$
A\to B \quad B\to C \above 2pt A\to C
$$

<!-- 2.6 -->
$$
A\to B \quad A\to (B\to C) \above 2pt A\to C
$$

<!-- 2.7 -->
$$
{} \above 2pt A\to A
$$

<!-- 2.8 -->
$$
A\to C \quad B\to C \quad A\land B \above 2pt C
$$

<!-- 2.9 -->
$$
A\to C \quad B\to C \above 2pt A\land B\to C
$$

<!-- 2.10 -->
$$
B \above 2pt A\to B
$$

<!-- 2.11 -->
$$
A\land B\to C \above 2pt A\to (B\to C)
$$

<!-- 2.12 -->
$$
A\to (B\to C) \above 2pt A\land B\to C
$$

<!-- 2.13 -->
$$
(A\to B)\land (A\to C) \above 2pt A\to B\land C
$$

<!-- 2.14 -->
$$
A\to (A\to B) \quad (A\to B)\to A \above 2pt B
$$

## Session 3
<!-- 3.1 -->
$$
A \quad B \above 2pt A\lor B
$$

<!-- 3.2 -->
$$
A \above 2pt A\lor B
$$

<!-- 3.3 -->
$$
B \above 2pt A\lor B
$$

<!-- 3.4 -->
$$
A \above 2pt A\lor A
$$

<!-- 3.5 -->
$$
A\lor B \above 2pt B\lor A
$$

<!-- 3.6 -->
$$
A\lor (B\lor C) \above 2pt (A\lor B)\lor C
$$

<!-- 3.7 -->
$$
A\land B \above 2pt A\lor B
$$

<!-- 3.8 -->
$$
(A\land B)\lor C \above 2pt (A\lor C)\land(B\lor C)
$$

<!-- 3.9 -->
$$
(A\lor B)\land C \above 2pt (A\land C)\lor (B\land C)
$$

<!-- 3.10 -->
$$
(A\to C)\land (B\to C) \above 2pt A\lor B\to C
$$

<!-- 3.11 -->
$$
A\lor B\to C \above 2pt (A\to C)\land (B\to C)
$$

<!-- 3.12 -->
$$
(A\to B)\lor (A\to C) \above 2pt A\to B\lor C
$$

## Session 4
<!-- 4.1 -->
$$
\perp \above 2pt A
$$

<!-- 4.2 -->
$$
\perp \above 2pt A\quad B
$$

<!-- 4.3 -->
$$
A \above 2pt \perp \lor A
$$

<!-- 4.4 -->
$$
\perp \lor A \above 2pt A
$$

<!-- 4.5 -->
$$
\perp \and A \above 2pt \perp
$$

<!-- 4.6 -->
$$
{} \above 2pt \perp\to A
$$

<!-- 4.7 -->
$$
A\to B \above 2pt (B\to \perp)\to (A\to \perp)
$$

<!-- 4.8 -->
$$
A\lor B\to \perp \above 2pt (A\to \perp)\land (B\to \perp)
$$

<!-- 4.9 -->
$$
(A\to \perp)\land (B\to \perp) \above 2pt A\lor B\to \perp
$$

<!-- 4.10 -->
$$
(A\to \perp)\lor (B\to \perp) \above 2pt A\land B\to \perp
$$

<!-- 4.11 -->
$$
((A\to \perp)\to \perp)\to\perp \above 2pt A\to \perp
$$

<!-- 4.12 -->
$$
(A\to \perp)\lor B \above 2pt A\to B
$$

<!-- 4.13 -->
$$
A\to \perp \quad B\to A \above 2pt B\to \perp
$$

<!-- 4.14 -->
$$
((A\to \perp)\lor (B\to \perp))\lor (C\to \perp) \above 2pt (A\land B)\land C\to \perp
$$

<!-- 4.15 -->
$$
{} \above 2pt (A\lor (A\to \perp)\to \perp)\to \perp
$$

## Session 5
<!-- 5.1 -->
$$
{} \above 2pt A\lor (A\to \perp)
$$

<!-- 5.2 -->
$$
(B\to \perp)\to (A\to \perp) \above 2pt A\to B
$$

<!-- 5.3 -->
$$
A\land B\to \perp \above 2pt (A\to \perp)\lor (B\to \perp)
$$

<!-- 5.4 -->
$$
(A\to \perp)\to \perp \above 2pt A
$$

<!-- 5.5 -->
$$
A\to B \above 2pt (A\to \perp)\lor B
$$

<!-- 5.6 -->
$$
A\to B \quad B\to C \above 2pt (A\to \perp)\lor C
$$

<!-- 5.7 -->
$$
{} \above 2pt ((A\to B)\to A)\to A
$$

<!-- 5.8 -->
$$
(A\land B)\land C\to \perp \above 2pt ((A\to \perp)\lor (B\to \perp))\lor (C\to \perp)
$$

<!-- 5.9 -->
$$
(A\to B)\to \perp \above 2pt A\land (B\to \perp)
$$

## Session 6
<!-- 6.1 -->
$$
\forall x. P(x) \above 2pt P(a)
$$

<!-- 6.2 -->
$$
\forall x. P(x) \above 2pt P(a)\land P(b)
$$

<!-- 6.3 -->
$$
P(a) \above 2pt \exists x.\ P(x)
$$

<!-- 6.4 -->
$$
\forall x.\ P(x) \above 2pt \exists x.\ P(x)
$$

<!-- 6.5 -->
$$
\forall x.\ A \above 2pt A
$$

<!-- 6.6 -->
$$
\exists x.\ A \above 2pt A
$$

<!-- 6.7 -->
$$
A\land (\forall x.\ P(x)) \above 2pt \forall x.\ A\land P(x)
$$

<!-- 6.8 -->
$$
(\forall x.\ P(x))\land (\forall x.\ Q(x)) \above 2pt \forall x.\ P(x)\land Q(x)
$$

<!-- 6.9 -->
$$
(\exists x.\ P(x))\lor (\exists x.\ Q(x)) \above 2pt \exists x.\ P(x)\lor Q(x)
$$

<!-- 6.10 -->
$$
(\exists x.\ P(x))\to A \above 2pt \forall x.\ P(x)\to A
$$

<!-- 6.11 -->
$$
\forall x.\ P(x)\to Q(x) \quad P(a) \above 2pt Q(a)
$$

<!-- 6.12 -->
$$
\forall x.\ \forall y.\ P(x, y) \above 2pt \forall y.\ \forall x.\ P(x, y)
$$

<!-- 6.13 -->
$$
\exists x.\ \exists y.\ P(x, y) \above 2pt \exists y.\ \exists x.\ P(x, y)
$$

<!-- 6.14 -->
$$
\exists x.\ \forall y.\ P(x, y) \above 2pt \forall y.\ \exists x.\ P(x, y)
$$

<!-- 6.15 -->
$$
\forall x.\ P(x) \above 2pt (\exists x.\ P(x)\to \perp)\to \perp
$$

<!-- 6.16 -->
$$
(\forall x.\ P(x))\to \perp \above 2pt \exists x.\ P(x)\to \perp
$$

<!-- 6.17 -->
$$
(\forall x.\ P(x))\to A \above 2pt \exists x.\ P(x)\to A
$$


## Session 7
<!-- 7.1 -->
$$
{} \above 2pt \exists x.\ t(x)\to (\forall x_1.\ t(x_1))
$$

<!-- 7.2 -->
$$
\forall x.\ (r(x)\to \perp)\to r(f(x)) \above 2pt \exists x.\ r(x)\land r(f(f(x)))
$$

## Hilbert System
<!-- 8.1 -->
$$
{} \above 2pt A\to A
$$

<!-- 8.2 -->
$$
{} \above 2pt (B\to C)\to ((A\to B)\to (A\to C))
$$

<!-- 8.3 -->
$$
{} \above 2pt (A\to (B\to C))\to (B\to (A\to C))
$$

<!-- 8.4 -->
$$
{} \above 2pt \neg A\to (A\to B)
$$

<!-- 8.5 -->
$$
{} \above 2pt (\neg A\to A)\to A
$$

<!-- 8.6 -->
$$
{} \above 2pt \neg\neg A\to A
$$

<!-- 8.7 -->
$$
{} \above 2pt A\to \neg\neg A
$$

<!-- 8.8 -->
$$
{} \above 2pt (B\to A)\to (\neg A\to \neg B)
$$

<!-- 8.9 -->
$$
{} \above 2pt (A\to B)\to ((\neg A\to B)\to B)
$$


## NAND Calculus
<!-- 9.1 -->
$$
A\uparrow B \above 2pt B\uparrow A
$$

<!-- 9.2 -->
$$
A \above 2pt (A\uparrow A)\uparrow (A\uparrow A)
$$

<!-- 9.3 -->
$$
{} \above 2pt (A\uparrow A)\uparrow A
$$

<!-- 9.4 -->
$$
(A\uparrow A)\uparrow (A\uparrow A) \above 2pt A
$$

<!-- 9.5 -->
$$
A \quad B \above 2pt (A\uparrow B)\uparrow (A\uparrow B)
$$

<!-- 9.6 -->
$$
(A\uparrow B)\uparrow (A\uparrow B) \above 2pt A \quad B
$$

## Simply Type Lambda Calculus
<!-- 10.1 -->
$$
{} \above 2pt (\lambda x.\ x):\ a\to a
$$

<!-- 10.2 -->
$$
{} \above 2pt (\lambda x.\ \lambda y.\ x):\ a\to (b\to a)
$$

<!-- 10.3 -->
$$
{} \above 2pt (\lambda x.\ \lambda y.\ \lambda z.\ (x\cdot z)\cdot (y\cdot z)): (a\to (b\to c))\to ((a\to b)\to (a\to c))
$$


## Copyright

(c) Haoze Zhang 2020

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
