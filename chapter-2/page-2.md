---
title: Structured Tables
# lapreprint-typst requires authors and an abstract
authors:
  - name: Sample Author
abstract: |
  A short comparison of MyST's two table syntaxes, with examples of captioned, labelled list tables.
exports:
  - format: pdf
    template: lapreprint-typst
    output: exports/page-2.pdf
    id: page-pdf
downloads:
  - id: page-pdf
    title: Download as PDF
---

Use the `{list-table}` directive when a table needs a caption, a label, or complex cell content.

## Comparing the formats

```{list-table} Comparison of MyST table syntaxes
:label: tbl-formats
:header-rows: 1

* - Feature
  - Pipe table
  - `{list-table}`
* - Caption
  - No
  - Yes
* - Cross-reference label
  - No
  - Yes
* - Multi-paragraph cells
  - No
  - Yes
* - Easy to read in source
  - Yes
  - Moderately
```

As [](#tbl-formats) shows, list tables cost a little readability in the source and give you much more flexibility in return.

:::{important}
Every row of a `{list-table}` must have the same number of items. A missing cell causes a build error rather than an empty cell.
:::

## Formulas in tables

```{list-table} Areas of common shapes
:label: tbl-areas
:header-rows: 1

* - Shape
  - Area
* - Circle
  - $\pi r^2$
* - Annulus
  - $\pi (r_2^2 - r_1^2)$
* - Triangle
  - $\tfrac{1}{2} b h$
```

This page is also exported as a PDF. Use the download button at the top of the page to get it.
