[![Paper](https://img.shields.io/badge/paper-arXiv%32111.06755-B31B1B.svg)](https://arxiv.org/abs/2111.06755)
[![DOI](https://zenodo.org/badge/427276978.svg)](https://zenodo.org/badge/latestdoi/427276978)


# Measuring post-quench entanglement entropy through density correlations

[Adrian Del Maestro](https://github.com/agdelma), [Hatem Barghathi](https://github.com/HatemBarghathi), and Bernd Rosenow

[arXiv:2111.06755](https://arxiv.org/abs/2111.06755)

### Abstract
Following  a sudden change of interactions in an integrable system of one-dimensional fermions, we analyze the dependence of the static structure factor on the observation time after the quantum quench. At small waiting times after the quench, we map the system to non-interacting bosons such that we are able to extract their occupation numbers from the Fourier transform of the density-density correlation function, and use these to compute a bosonic entropy from a diagonal ensemble. By comparing this bosonic entropy with the asymptotic steady state entanglement entropy per fermion computed with exact diagonalization we find excellent agreement.  

### Description
This repository includes links, code, scripts, and data to perform the analysis and generate the figures described in the above paper. 

### Requirements
The primary data set analyzed in this paper was generated via exact diagonalization.  There is a companion [paper](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.104.195101) and [repository](https://github.com/DelMaestroGroup/papers-code-EntanglementQuantumQuench) which provides complimentary detail of the ED and finite size scaling procedure employed here.  The analysis of the observation time dependence of the static structure factor is based the results in the [data](https://github.com/DelMaestroGroup/papers-code-QuenchStructureFactorEntanglement/tree/main/data) directory.

* [dgutils](https://github.com/DelMaestroGroup/dgutils)

### Support
The creation of these materials was supported in part by the National Science Foundation under Award No. DMR-2041995

[<img width="100px" src="https://www.nsf.gov/images/logos/NSF_4-Color_bitmap_Logo.png">](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2041995&HistoricalAwards=false)

### Figures

#### Figure 01: Momentum Dependence of the Post-Quench Static Structure Factor
<img src="https://github.com/DelMaestroGroup/papers-code-QuenchStructureFactorEntanglement/blob/main/figures/S_vs_q_n_13.svg" width="400px">

#### Figure 02: Waiting Time Dependence of the Post-Quench Static Structure Factor
<img src="https://github.com/DelMaestroGroup/papers-code-QuenchStructureFactorEntanglement/blob/main/figures/nqt_vs_t_with_interp.svg" width="400px">

#### Figure 03: Boson Occupation Numbers in the Small-Momentum Limit
<img src="https://github.com/DelMaestroGroup/papers-code-QuenchStructureFactorEntanglement/blob/main/figures/nq_vs_V.svg" width="400px">

#### Figure 04: Comparing the Fermionic and Bosonic Entropy Density
<img src="https://github.com/DelMaestroGroup/papers-code-QuenchStructureFactorEntanglement/blob/main/figures/entropy_comparison.svg" width="400px">


<!--This figure is relesed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.-->

