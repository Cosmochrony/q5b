# Q5b — BFS Shell Stratification and the Emergence of Four-Dimensional Lorentzian Geometry

This repository contains the source of the **Q5b Cosmochrony paper**
*BFS Shell Stratification and the Emergence of Four-Dimensional Lorentzian
Geometry*.

**Status revision (version 2.0).** Version 3.0 of the companion paper Q5a withdraws its
earlier derivation of a spatial limit operator $L_\Pi = -A\partial_x^2$ on $L^2(\mathbb{R})$:
the canonical filtration is exactly a growing toric Fourier window, the published
admissibility form converges to the zero form on it, and no common scalar normalisation
produces a non-trivial toric differential operator. The spatial input of this paper is
therefore formalised as an explicit, unestablished hypothesis **[H-L]** (existence of the
spatial limit operator), and every result consuming $L_\Pi$ is stated conditionally on it.
The geometric convergence results (Carnot limit, $D_{\mathrm{hom}} = 4$) are independent of
[H-L] and stand.

## Core Results

1. **Four-dimensional limit geometry**: the BFS shell stratification of
   $\mathrm{Heis}_3(\mathbb{Z}/q)$ converges, in the pre-saturation regime, to the
   Carnot–Carathéodory sphere foliation of $\mathrm{Heis}_3(\mathbb{R})$; the homogeneous
   dimension $D_{\mathrm{hom}} = 4$ (Bass–Guivarc'h) gives the limiting geometry the spectral
   and volume-growth properties of a four-dimensional space.
2. **Metric extraction (conditional on [H-L])**: under [H-L], $L_\Pi$ is the image, under
   the Schrödinger representation, of the kinetic sector of the sub-Riemannian Laplacian
   $\Delta_H$; an effective co-metric is read off the principal symbol of the effective
   operator.

The lifting hypothesis [H-lift] has been proved in Q9, so the conditionality of the metric
result reduces to [H-L] alone. The coefficients are determined by companion papers:
$A_H = 2$ (Q10), $A_z = 2$ (Q8), $A_\tau = 2$ (Q11) — all readings conditional on [H-L].
Establishing [H-L], or replacing it, is the open content of Q5.

## Keywords

BFS stratification, Carnot–Carathéodory geometry, sub-Riemannian Laplacian, homogeneous
dimension, Mosco convergence, Lorentzian signature, emergent spacetime.

## Repository Contents

```
q5b/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── out/         # Compiled paper PDF (q5b.pdf)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 🔗 DOI: [10.5281/zenodo.19686700](https://doi.org/10.5281/zenodo.19686700)
- 🌐 Website: https://cosmochrony.org/science/emergent-geometry/q5/b/

## Citation

> J. Beau, *BFS Shell Stratification and the Emergence of Four-Dimensional Lorentzian
> Geometry*, Zenodo, 2026. DOI: 10.5281/zenodo.19686700.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations remain
the sole responsibility of the author.
