---
id: 5900f3d21000cf542c50fee4
title: 'Problem 101: Optimum polynomial'
challengeType: 5
forumTopicId: 301725
dashedName: problem-101-optimum-polynomial
---

# --description--

If we are presented with the first k terms of a sequence it is impossible to say with certainty the value of the next term, as there are infinitely many polynomial functions that can model the sequence.

As an example, let us consider the sequence of cube numbers. This is defined by the generating function, $u_n = n^3: 1, 8, 27, 64, 125, 216, \ldots$

Suppose we were only given the first two terms of this sequence. Working on the principle that "simple is best" we should assume a linear relationship and predict the next term to be 15 (common difference 7). Even if we were presented with the first three terms, by the same principle of simplicity, a quadratic relationship should be assumed.

We shall define $OP(k, n)$ to be the $n^{th}$ term of the optimum polynomial generating function for the first k terms of a sequence. It should be clear that $OP(k, n)$ will accurately generate the terms of the sequence for $n ≤ k$, and potentially the first incorrect term (FIT) will be $OP(k, k+1)$; in which case we shall call it a bad OP (BOP).

As a basis, if we were only given the first term of sequence, it would be most sensible to assume constancy; that is, for $n ≥ 2, OP(1, n) = u_1$.

Hence we obtain the following OPs for the cubic sequence:

$$\begin{array}{ll} OP(1, n) = 1          & 1, {\color{red}1}, 1, 1, \ldots     \\\\ OP(2, n) = 7n−6       & 1, 8, {\color{red}{15}}, \ldots     \\\\ OP(3, n) = 6n^2−11n+6 & 1, 8, 27, {\color{red}{58}}, \ldots \\\\ OP(4, n) = n^3        & 1, 8, 27, 64, 125, \ldots \end{array}$$

Clearly no BOPs exist for k ≥ 4. By considering the sum of FITs generated by the BOPs (indicated in $\color{red}{red}$ above), we obtain 1 + 15 + 58 = 74. Consider the following tenth degree polynomial generating function:

$$u_n = 1 − n + n^2 − n^3 + n^4 − n^5 + n^6 − n^7 + n^8 − n^9 + n^{10}$$

Find the sum of FITs for the BOPs.

# --hints--

`optimumPolynomial()` should return `37076114526`.

```js
assert.strictEqual(optimumPolynomial(), 37076114526);
```

# --seed--

## --seed-contents--

```js
function optimumPolynomial() {

  return true;
}

optimumPolynomial();
```

# --solutions--

```js
// solution required
```