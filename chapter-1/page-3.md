---
title: Simple Tables
---

The quickest way to write a table is with Markdown pipes.

## Physical constants

| Constant          | Symbol | Value                     | Unit         |
| ----------------- | :----: | ------------------------: | ------------ |
| Speed of light    | $c$    | 299 792 458               | m/s          |
| Planck constant   | $h$    | $6.626 \times 10^{-34}$   | J·s          |
| Gravitational     | $G$    | $6.674 \times 10^{-11}$   | N·m²/kg²     |
| Elementary charge | $e$    | $1.602 \times 10^{-19}$   | C            |

The colons in the separator row set the alignment: the **Symbol** column is centred and the **Value** column is right-aligned.

## Limitations

:::{warning}
Pipe tables cannot have a caption or a label, so they cannot be cross-referenced. Use the `{list-table}` directive when you need either one. See [](../chapter-2/page-2.md) for an example.
:::

## Chapter summary

This chapter covered inline math, a figure, two notes, labelled equations, and a pipe table. Chapter 2 builds on these.
