# Q5b — Toward Four-Dimensional Lorentzian Geometry from BFS Shell Stratification

This repository contains the source of the **Q5b Cosmochrony paper**
*Toward Four-Dimensional Lorentzian Geometry from BFS Shell Stratification*.

The companion paper Q5a shows that the canonical filtration of the admissible fibre is a growing toric Fourier
window, that the published admissibility form converges to the zero form on it, and that no common scalar
normalisation produces a non-trivial toric differential operator. The spatial input of this paper is therefore an
explicit, unestablished hypothesis **[H-L]** (existence of a spatial limit operator $L_\Pi = -A\partial_x^2$ on
$L^2(\mathbb{R})$), and every result consuming $L_\Pi$ is stated conditionally on it.

## Core Results

1. **Four-dimensional limit geometry (structural)**: the BFS shell stratification of
   $\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$ converges, in the pre-saturation regime, to the Carnot–Carathéodory
   sphere foliation of $\mathrm{Heis}_3(\mathbb{R})$; the homogeneous dimension $D_{\mathrm{hom}} = 4$
   (Bass–Guivarc'h) gives the limiting geometry the spectral and volume-growth properties of a four-dimensional
   space.
2. **Metric extraction (conditional on [H-L] and [H-lift])**: under the lifting hypothesis [H-lift], $L_\Pi$ is the
   image, under the Schrödinger representation, of the kinetic sector of the sub-Laplacian $\Delta_H$, and the
   principal symbol of the effective operator gives the co-metric $\mathrm{diag}(-A_\tau, A_H, A_H, 0)$ in the
   left-invariant frame. It has rank three; no lower-order term fills the central slot.
3. **Signature (conditional also on [H-hyp])**: the Born–Infeld admissibility constraint selects the signature
   $(-,+,+)$ on the non-degenerate block; a full-rank extension with a positive central coefficient is Lorentzian.

## Status of the open inputs

- **[H-lift] is open.** Q9 gives sufficient conditions for a kinetic Mosco limit and does not discharge it.
- **Q5b-O2 is open.** Q8 shows that the Heisenberg commutator supplies no central coefficient: a full-rank extension
  requires a new operator with a term $\tilde Z^2$ of homogeneous degree four, which carries a length scale.
- **No coefficient value is established.** Q10 derives no value of $A_H$; Q8 shows that $\mathfrak{su}(2)$-invariance
  leaves the common value of an isotropic form free; the value $A_\tau = 2$ asserted in Q11 rests on the same Casimir
  normalisation.
- The paper uses the group law $z'' = z + z' + \tfrac12(x'y - xy')$, for which
  $\tilde X = \partial_x + \tfrac{y}{2}\partial_z$ and $\tilde Y = \partial_y - \tfrac{x}{2}\partial_z$ are
  left-invariant and $[\tilde X, \tilde Y] = -\tilde Z$.

Establishing [H-L], or replacing it, and constructing a full-rank extension are the open content of Q5.

## Keywords

BFS stratification, Carnot–Carathéodory geometry, sub-Riemannian Laplacian, homogeneous dimension, Mosco convergence,
Lorentzian signature, emergent spacetime, Cosmochrony.

## Repository Contents

```
q5b/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib + external-refs.bib)
├── compile.sh   # Build script (output in out/, not versioned)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 🔗 DOI: [10.5281/zenodo.19686700](https://doi.org/10.5281/zenodo.19686700)
- 🌐 Website: https://cosmochrony.org/science/emergent-geometry/q5/b/

## Citation

> J. Beau, *Toward Four-Dimensional Lorentzian Geometry from BFS Shell Stratification*, Zenodo, 2026.
> DOI: 10.5281/zenodo.19686700.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large language models, used as
analytical assistants. All claims and final formulations remain the sole responsibility of the author.
