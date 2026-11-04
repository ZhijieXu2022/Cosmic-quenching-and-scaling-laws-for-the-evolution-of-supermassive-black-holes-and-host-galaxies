# Supermassive black hole and host galaxy data and manuscript: cosmic quenching and scaling laws

Data and manuscript for **Xu, Z. (2025), *Cosmic quenching and scaling laws for the evolution of supermassive black holes and host galaxies*, MNRAS 536(4), 3554–3587, doi:[10.1093/mnras/stae2766](https://doi.org/10.1093/mnras/stae2766), arXiv:[2501.07608](https://arxiv.org/abs/2501.07608)**.

The complete archive, with the same files, is on Zenodo: [doi:ZENODO_DOI_PENDING](https://doi.org/ZENODO_DOI_PENDING).

[![DOI](https://zenodo.org/badge/DOI/ZENODO_DOI_PENDING.svg)](https://doi.org/ZENODO_DOI_PENDING)

## Major findings

- A single parameter ε<sub>b</sub> (unit m²/s³), the rate of mass and energy flow in the gas of a bulge, regulates the coevolution of supermassive black holes (SMBHs) and host galaxies; with Illustris simulations and observations it varies as ε<sub>b</sub> ∝ (1+z)<sup>5/2</sup>.
- Host galaxies follow the mass–size relation M<sub>b</sub> ∝ ε<sub>b</sub><sup>2/3</sup> r<sub>b</sub><sup>5/3</sup> G<sup>-1</sup>, with bulge size r<sub>b</sub> ∝ (1+z)<sup>-1</sup>, the dispersion–size relation σ<sub>b</sub><sup>2</sup> ∝ (ε<sub>b</sub> r<sub>b</sub>)<sup>2/3</sup> ∝ (1+z), and the mass–dispersion relation M<sub>b</sub> ∝ ε<sub>b</sub><sup>-1</sup> G<sup>-1</sup> σ<sub>b</sub><sup>5</sup>.
- SMBHs pass through three phases: a rapid initial growth with L<sub>B</sub> ∝ (ε<sub>b</sub> M<sub>BH</sub>)<sup>4/5</sup> G<sup>-1/5</sup> c, a transition with L<sub>B</sub> ∝ ε<sub>b</sub><sup>2</sup> M<sub>BH</sub> ∝ (1+z)<sup>5</sup>, and a dormant stage with L<sub>B</sub> ∝ (ε<sub>b</sub> M<sub>BH</sub>)<sup>4/3</sup> G<sup>1/3</sup> c<sup>-5/3</sup>.
- The rapid initial growth is limited by a redshift-dependent luminosity limit L<sub>X</sub> ∝ ε<sub>b</sub><sup>4/5</sup> M<sub>BH</sub><sup>4/5</sup> G<sup>-1/5</sup> c, which replaces the Eddington limit as the bound on super-Eddington growth.
- The analytical BH mass function, AGN mass function and quasar duty cycle predict Φ<sub>L</sub> ∝ L<sup>-1/5</sup> at the faint end of the luminosity function, Φ<sub>AGN</sub> ∝ M<sup>-1/5</sup> at the small-mass end of the AGN mass function, and a duty cycle U ∝ M<sup>-1/5</sup> at high redshift.

## Contents

| Path | Content |
|---|---|
| `manuscript.pdf` | Manuscript (MNRAS article) |
| `csv/` | 39 CSV files: the plotted data of the figures (`Fig…`, `FigA…`), the table (`TableB1…`) and the result sets of the checks (`Result_…`) |
| `CITATION.cff`, `LICENSE` | citation metadata and licence |

## Format of the CSV files

Each file starts with comment lines beginning with `#`, then a header row, then data.

- `# Publisher`: author and contact.
- `# Updated`: date of the last update.
- `#Name`: what the file contains.
- `#Ref.`: the figure or table of the paper the data belong to, with the DOI.
- `#Note`: processing notes, where needed.

Figure files are named by the figure number of the article (for example `Fig09_Bulg_size_vs_mass_z0_2.csv`). Where a figure has more than one panel or series, the columns are named in the header row.

## Related dataset

- Super-Eddington growth of supermassive black holes and scaling laws for SMBH-host coevolution: doi:[10.5281/zenodo.7490501](https://doi.org/10.5281/zenodo.7490501)

## Citation

Please cite the article (doi:10.1093/mnras/stae2766) and this archive (doi:ZENODO_DOI_PENDING). GitHub's "Cite this repository" button uses `CITATION.cff`.

## Licence

The text, figures and data in this repository are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See `LICENSE`.
