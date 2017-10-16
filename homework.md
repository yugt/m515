## Math 515 homework

### Homework 6. Due Wednesday, October 18
* Ex 11.1 = Tao ex 1.3.13. Let $f$ be a nonnegative measurable function on $\RR$. Show that $\int f$ is equal to the $2$-dimensional Lebesgue measure of the region ${(x,y)\mid 0\leq y\leq f(x)}$
* Ex 11.2 = Tao ex 1.3.18. Let $f$ be an nonnegative measurable function on $\RR^d$.
  * Show that if $\int f&lt;\infty$ then $f$ is finite almost everywhere. Give a counterexample to show that the converse is false.
  * Show that $\int f=0$ if and only if $f=0$ almost everywhere.
* Ex 11.3. Give an example of a nonnegative function which is measurable, but has different lower and upper Lebesgue integrals.
* Ex 12.1 = Tao ex 1.3.25(i). Let $f$ be absolutely integrable. Show that for any $\epsilon&gt;0$ there exists a bounded measurable set $A$ such that $\int |f|\chi\_{A^c}&lt;\epsilon$.
* Ex 12.2 = Tao ex 1.3.25(ii).Let $f$ be a measurable set with finite measure support. Show that for any $\epsilon&gt;0$, there exists a measurable set $A$ such that $m(A)&lt;\epsilon$ and $f$ is locally bounded outside of $A$. In other words, for every $n$ there exists $M$ such that for all $x\in[-n,n]^d\setminus A$ we have $f(x)\leq M$.

### Homework 5. Due Wednesday, October 11

* Ex 9.1 Show that a function $f$ is simple if and only if it can be expressed as $f=\sum\_1^kc_i\chi\_{A\_i}$, where $A\_i$ are (not necessarily disjoint) Lebesgue measurable sets.
* Ex 9.2 ~ Tao Ex 1.3.1. Show that the simple integral satisfies the properties:
  * (finiteness) $\sint f\<\infty$ if and only if $f$ is finite almost everywhere and supported on a set of finite measure
  * (vanishing) $\sint f=0$ if and only if $f=0$ almost everywhere
  * (normality) $\sint\chi_A=m(A)$ for any Lebesgue measurable set $A$
* Ex 10.1. Show that $\lim x\_n=x$ if and only if $\liminf x\_n=x=\limsup x\_n$.
* Ex 10.3 = Tao Ex 1.3.4. Show that if $f$ is a bounded, nonnegative measurable function on $\RR^d$, then there is a sequence of bounded simple functions $f_n$ which converges uniformly to $f$ (not just pointwise).
* Ex 10.4 = Tao Ex 1.3.5. Let $f$ be a nonnegative function on $\RR^d$. Show that $f$ is simple if and only if $f$ is measurable and takes on at most finitely many values.

### Homework 4. Due Friday, September 29

* Ex 7.1 ~ Tao Ex 1.2.7. (a) Show that $A$ is measurable iff for all $\epsilon>0$ there exists a closed set $F\subset A$ such that $m^\*(A\setminus F)&lt;\epsilon$. (b) Show that $A$ is measurable iff for all $\epsilon>0$ there exists a measurable set $B$ such that $m^\*(A\triangle B)<\epsilon$.
* Ex 7.2 = Tao Ex 1.2.14. Show that any set $A$ is contained in a Lebesgue measurable set $B$ such that $m(B)=m^\*(A)$.
* Ex 7.3 = Tao Ex 1.2.15. Show the \emph{inner regularity} property: If $A$ is Lebesgue measurable, then m(A)=\sup\set{m(K)\mid K\subset A,\text{ $K$ compact}}
* Ex 8.1 = Tao Ex 1.2.11(iii). Give a counterexample showing that the hypothesis that some $A_n$ has finite measure is necessary for the downwards MCT.
* Ex 8.2 = Tao Ex 1.2.12. Suppose you know that $m$ satisfies $m(\emptyset)=0$ and the countable additivity property. Show that $m$ satisfies the monotonicity property and the countable subadditivity property (for measurable sets).

### Homework 3. Due Friday, September 15

* Ex 5.1 = Tao ex 1.2.1. Show that the countable union of Jordan measurable sets need not be Jordan measurable, even when bounded. Show that the countable intersection of Jordan measurable sets need not be Jordan measurable.
* Ex 5.2 = Tao ex 1.2.2. Give an example of a sequence of uniformly bounded, Riemann integrable functions on $[0,1]$ which converges pointwise to a function that is not Riemann integrable. Is it possible to give an example which converges uniformly?
* Ex 5.3. Show that $m^\*(A)\\leq m^{\*j}(A)$. Give an example of a set $A$ such that $m^\*(A)&lt;m^{\*j}(A)$.
* Ex 5.4. Show that Jordan outer measure does not satisfy countable subadditivity.
* Ex 6.1 = Tao ex 1.2.5. Suppose $A$ is expressible as a countable union of pairwise almost disjoint boxes. Show that $m^\*(A)=m_{\*j}(A)$.

### Homework 2. Due Friday, September 8

* Ex 3.2 ~ Tao ex 1.1.5. Show that $A$ is Jordan measurable iff for all $\epsilon>0$ there is an elementary set $E$ such that $m^{\*j}(E\triangle A)&lt;\epsilon$.
* Ex 3.4 = Tao ex 1.1.12. Say that $A$ is \emph{Jordan null} if $A$ is Jordan measurable and $m(A)=0$. Show that any subset of a Jordan null set is a Jordan null set.
* Ex 3.5. Show that the outer Jordan measure $m^{*j}(A)$ is equal to: inf{\vol(B\_1)+\cdots+\vol(B\_k) : B\_1,\ldots,B\_k are boxes and A\subset B\_1\cup\cdots\cup B\_k}.
* Ex 4.2 = Tao ex 1.1.23. Let $f\colon[a,b]\to\RR$. Show that if $f$ is continuous, then $f$ is Riemann integrable. Show that if $f$ is bounded and piecewise continuous, then $f$ is Riemann integrable.
* Ex 4.3 = Tao ex 1.1.24. Show that the Riemann integral satisfies the linearity and monotonicity properties. (Hint: first establish these properties for the pc integral.)

### Homework 1. Due Friday, September 1

* Ex 1.1. Show that the properties (a)--(c) of a measure imply finite addivitity: If $A$ and $B$ are disjoint then $m(A\cup B)=m(A)+m(B)$.
* Ex 1.2. Show that the properties (a)--(c) of a measure imply the inclusion--exclusion principle: For any sets $A,B$ we have $m(A\cup B)+m(A\cap B)=m(A)+m(B)$.
* Ex 1.3. Complete the details of the proof that if there is a measure on $\RR$ satisfying properties (a)--(c), then there is a measure on $[0,1)$ (with additional modulo $1$) satisfying properties (a)--(c).
* Ex 2.1 = Tao ex 1.1.1. Show that the class of elementary sets is closed under the operations: union, intersection, set difference, symmetric difference, and translation.
* Ex 2.2. Prove the elementary measure satisfies the monotonicity and finite subadditivity properties.
