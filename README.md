[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18007057.svg)](https://doi.org/10.5281/zenodo.18007057)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# `PHCosseratRods`

This repository contains the simulation results of the paper
_Kinon, P. L., Eugster, S. R. & Betsch, P. (2026): 
[Mixed formulation and structure-preserving discretization of Cosserat rod dynamics in a port-Hamiltonian framework](https://doi.org/10.1016/j.cma.2026.118966)_.
This repository is licensed under the [MIT License][url_license].

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#citation">Citation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#references">References</a></li>
  </ol>
</details>

## Citation

If you found our work helpful and you have used it in your academic work, please cite it as:

```bibtex
@misc{kinon_eugster_betsch_2026,
  title   = {Mixed formulation and structure-preserving discretization of Cosserat rod dynamics in a port-Hamiltonian framework},
  author  = {Philipp L. Kinon and Simon R. Eugster and Peter Betsch},
  journal = {Computer Methods in Applied Mechanics and Engineering},
  year    = {2026},
  volume  = {458},
  pages   = {118966},
  doi     = {https://doi.org/10.1016/j.cma.2026.118966},
}
```
see also the [CITATION.bib](CITATION.bib) file for download.


## Usage

The implementation has been done in the finite element code base [`moofeKIT`][moofekit_repo]. The results are documented here for reproducibility and verification purposes.

1. [Clone][url_how_to_clone] this repository to your machine.
2. Open a terminal and navigate to your local clone.
3. Extract your desired result data as `.csv`-file data from the [results folder](results). This folder contains subfolders for each experiment documented in the manuscript.
4. Use your favorite plotting tool to visualize the data.

## References
In the manuscript, we compare our formulation to two other approaches from the literature: [Herrmann & Kotyczka (2024)][doi_herrmann_kotyczka_2024] and [Herrmann et al. (2025)][doi_herrmann_etal_2025]. The analytical reference solution in example 03 is due to [Harsch et al. (2021)][doi_harsch_etal_2021]. The data are available in [this folder](reference_results) for your convenience. Please cite those works appropriately if you use the data.


[moofekit_repo]: https://github.com/kit-ifm/moofeKIT
[url_license]: LICENSE
[url_how_to_clone]: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
[doi_herrmann_kotyczka_2024]: https://doi.org/10.1016/j.cma.2024.117367
[doi_herrmann_etal_2025]: 
https://doi.org/10.48550/arXiv.2507.01552
[doi_harsch_etal_2021]: https://doi.org/10.1177/10812865211000790
