# An Information-Theoretic Principle of Prediction: Synchronicity

**Zhenyu Li · Zhejiang University**  
Research preprint, draft v0.2 · November 2, 2026

[Read the paper](paper/synchronicity_v0.2.pdf) · [Download PDF](https://raw.githubusercontent.com/li-zhenyu0511/synchronicity-information-theory/main/paper/synchronicity_v0.2.pdf) · [LaTeX source](latex/) · [Source ZIP](downloads/arxiv_source_v0.2.zip)

## Overview

Prediction is possible when a present record constrains the future continuations of a process. This preprint develops synchronicity through conditional prediction, recoverable distinctions, complex information amplitudes, and the relative phase of alternative response routes. A rhombic propagation–recombination geometry connects these definitions to prediction-error identities and learning from residual information. A proposed informationon construction connects relational amplitudes with interval geometry and phase transport.

## Contents

- `paper/synchronicity_v0.2.pdf`: manuscript with proofs and appendices (11 pages).
- `latex/`: editable manuscript source, bibliography, and ICML preprint style files.
- `figures/figure1.pdf`: vector figure showing the causal diamond, elimination of alternatives, and route-phase comparison.
- `downloads/arxiv_source_v0.2.zip`: self-contained LaTeX source package.

## Build

With a standard TeX Live installation and `latexmk`:

```sh
cd latex
latexmk -pdf main.tex
```

The figure is generated from `figures/diamond.tikz` during compilation. The included ICML 2026 style uses its `preprint` option.

## Citation and contact

Use GitHub's **Cite this repository** entry for the supplied citation metadata.

Zhenyu Li, *An Information-Theoretic Principle of Prediction: Synchronicity*, preprint, 2026.

Contact: [zylics@zju.edu.cn](mailto:zylics@zju.edu.cn).

The bundled ICML style files retain their original notices. [Official ICML template](https://media.icml.cc/Conferences/ICML2026/Styles/icml2026.zip).
