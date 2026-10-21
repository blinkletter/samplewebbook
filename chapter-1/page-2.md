---
title: Equations
downloads:
  - file: page-2.md
    title: Source File
---

This page shows display equations and how to cross-reference them.

## The Gaussian integral

The Gaussian integral appears throughout probability and physics:

```{math}
:label: eq-gaussian
\int_{-\infty}^{\infty} e^{-x^2} \, dx = \sqrt{\pi}
```

Dividing [](#eq-gaussian) by $\sqrt{\pi}$ shows that the normal density integrates to one.

## Euler's identity

A display equation can also be written with dollar signs and a label:

$$
e^{i\pi} + 1 = 0
$$ (eq-euler)

Equation [](#eq-euler) links the five most important constants in mathematics. Both [](#eq-gaussian) and [](#eq-euler) are numbered automatically.

## Fourier series

A periodic function such as the wave in [](#fig-wave) can be written as a sum of sines and cosines:

$$
f(x) = \frac{a_0}{2} + \sum_{n=1}^{\infty} \left( a_n \cos nx + b_n \sin nx \right)
$$ (eq-fourier)

:::{tip}
Hover over a cross-reference such as [](#eq-fourier) to preview the equation without leaving the page.
:::
