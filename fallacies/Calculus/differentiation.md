---
title: Differentiation
nav_order: 1
permalink: /calculus/differentiation
parent: Calculus
---

## Differentiation

In this proof, we will show that $2=1$ with the help of derivatives.

Let $x$ be a real number, Then

$$ x^2=\underbrace{x+x+x+\cdots+x}_{x\text{ times}} $$

$$ \frac{d}{dx}(x^2)=\frac{d}{dx}(\underbrace{x+x+x+\cdots+x}_{x\text{ times})}) $$

$$ \frac{d}{dx}(x^2)=\underbrace{\frac{d}{dx}x +\frac{d}{dx}x+\cdots+\frac{d}{dx}x}_{x\text{ times}}$$

$$ 2x = \underbrace{1+1+1+\cdots+1}_{x\text{ times}}$$

$$ 2x=x $$

$$ 2=1 $$

Can you find the mistake in the proof?

### Solution:

<details markdown="block">
  <summary>
  Reveal Solution
  </summary>
The whole problem lies in the fact that we are considering the number of terms to be constant. The number of terms depends on $x$ which is a variable. Hence we cannot simply *distribute* the derivative over the sum. We need to use the product rule to find the derivative of the sum.
</details>
