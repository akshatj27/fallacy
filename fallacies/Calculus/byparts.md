---
title: Integration By Parts
nav_order: 1
permalink: /calculus/integrationbyparts
parent: Calculus
---

## Integration By Parts

In this proof, we will show that $0=1$ with the help of integration by parts.

We know that $\int u\ dv = uv\ – \int v du$

Let $I=\int \frac{1}{x}dx$

$$ \int \frac{1}{x}dx = x\cdot\frac{1}{x} - \int -\frac{1}{x^2}x\,dx $$

$$ I = 1 + \int \frac{x}{x^2}dx $$

$$ I = 1 + I $$

$$ 0=1 $$

### Solution:

<details markdown="block">
  <summary>
  Reveal Solution
  </summary>
We are neglecting the constants of integration in the integrals. The constants can be different for an integral, even if the integrand is the same.

$$ \int \frac{1}{x}dx = ln(x)+C$$

$$\int \frac{1}{x}dx = 1 + \int \frac{1}{x}dx$$

$$ C_1 = 1 + C_2 $$

Also, due to this, we can say that subtracting two similar indefinite integrals, will not always give $0$. 

$$ \int x dx - \int x dx = \int (x-x) dx = \int 0 dx = C $$

</details>