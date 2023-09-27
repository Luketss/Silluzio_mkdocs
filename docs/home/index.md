# Admonitions

## Configuration

```
markdown_extensions:
  - admonition
  - pymdownx.details
  - pymdownx.superfences
```

# Using **abbr** from markdown_extensions

```
markdown_extensions:
  - abbr
```

The HTML specification
is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium

---

# Using **admonition** from markdown_extensions

```
markdown_extensions:
  - admonition
```

!!! type "optional explicit title within double quotes"
    Any number of other indented markdown elements.

    This is the second paragraph.

---

Collapsible blocks¶

When Details is enabled and an admonition block is started with ??? instead of !!!, the admonition is rendered as a collapsible block with a small toggle on the right side:

??? note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
  

``` { .yaml .annotate }
# Code block content
name: PyYAML CI

on:
  push:
  pull_request:
    types: [opened, synchronize, reopened]
  workflow_dispatch:

env:
  LIBYAML_REPO: https://github.com/yaml/libyaml
  LIBYAML_REF: 0.2.5

```