---
title: Putting It Together
---

This final page draws on content from across the book.

## Cross-chapter references

References work across pages and chapters:

- The Gaussian integral, [](#eq-gaussian), is defined in Chapter 1.
- The sine wave in [](#fig-wave) and the rings in [](#fig-rings) are the book's two figures.
- [](#tbl-formats) compares the two table syntaxes.

## A combined result

Combining [](#eq-gaussian) with a change of variables $x = t / \sqrt{2}$ gives the normalisation of the standard normal distribution:

$$
\frac{1}{\sqrt{2\pi}} \int_{-\infty}^{\infty} e^{-t^2/2} \, dt = 1
$$ (eq-normal)

:::{important} Key takeaway
:class: dropdown
Labels such as `eq-normal` are global to the project. Choose distinctive names so they don't collide across pages.
:::

:::{warning}
If you rename a label, update every cross-reference to it. Run `myst build` to find broken references; they are reported as warnings.
:::
