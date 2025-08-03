---
title: My First Article
# thumbnail: xref:guide/thumbnails/nice-image.png
date: 2022-05-11
authors:
  - name: Mason Moniker
    affiliations:
      - University of Europe
---
### Heading Level 3

Try changing the number of `#`s to $n$[^math] to change the **depth** of the _heading_.

1. Learn about [Markdown](https://en.wikipedia.org/wiki/Markdown)
   - Go through a [tutorial](https://commonmark.org/help/tutorial/)

[^math]: Where $n \in \mathbb{N}$ with $n \leq 6$, or between an H1 and an H6

:::{figure} https://github.com/rowanc1/pics/blob/main/banff-tall.png?raw=true
:align: right
:width: 40%

The picture would look better if it is `:align: center`-ed!
:::

:::{figure} https://github.com/rowanc1/pics/blob/main/banff-tall.png?raw=true
:align: left
:width: 40%

The picture would look better if it is `:align: center`-ed!
:::

:::{figure} https://github.com/rowanc1/pics/blob/main/banff-tall.png?raw=true
:align: center
:width: 40%

The picture would look better if it is `:align: center`-ed!
:::

Some content {abbr}`MyST (Markedly Structured Text)`


```{figure} https://github.com/rowanc1/pics/blob/main/mountains.png?raw=true
:label: my-fig
:align: center

My **bold** mountain 🏔🚠.
```

Check out [](#my-fig)!!
