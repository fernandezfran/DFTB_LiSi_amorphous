# NMR, x-ray and Mössbauer results for amorphous Li-Si alloys using density functional tight-binding method

[![DOI](https://zenodo.org/badge/681853337.svg)](https://zenodo.org/badge/latestdoi/681853337)
[![PRB](https://img.shields.io/badge/PhysRevB-108.144201-b31033)](https://doi.org/10.1103/PhysRevB.108.144201)
[![arXiv](https://img.shields.io/badge/arXiv-2305.11006-b31b1b)](https://arxiv.org/abs/2305.11006)

This is a data repository to support the main work 

> Fernandez, F., Otero, M., Oviedo, M. B., Barraco, D. E., Paz, S. A., Leiva, E. P. M. (2023).
> NMR, x-ray and Mössbauer results for amorphous Li-Si alloys using density functional
> tight-binding method. _Physical Review B, 108_, 144201.
> DOI: https://doi.org/10.1103/PhysRevB.108.144201

The atomic configurations of the structures were obtained using the 
[lithiation_protocol](https://github.com/fernandezfran/lithiation_protocol) code. In the main work, 
these structures are analyzed with nearest neighbor models implemented in the 
[macchiato](https://github.com/fernandezfran/macchiato) Python package.


# Content

The `structures` folder contains the structures of the amorphous LiSi system.
These where obtained using [DFTB+](https://dftbplus.org/) and our previous 
[parameters](https://github.com/alexispaz/DFTB_LiSi) for this system. In 
`LiNSiM.xyz`, where `N` and `M` are the number of Li and Si atoms, respectively,
there is a frame in [xyz format](https://en.wikipedia.org/wiki/XYZ_file_format) 
from which the simulation can be restarted. Also, in `LiNSiM.out` is the DFTB+ 
output of that frame with the box size and other thermodynamic information.


# License

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0
International License. To view a copy of this license, consult the LICENSE file
or visit http://creativecommons.org/licenses/by-sa/4.0/ .

NOTE: The rights holder(s) for this work explicitly require that the attribution
conditions of this license are enforced. Use in part or in whole of this data is
permitted only under the condition that the scientific background of the
Licensed Material will be CITED IN ANY PUBLICATIONS ARISING FROM ITS USE. The
required references are specified in this file and must be included in resulting works.


# Required references

> Fernandez, F., Otero, M., Oviedo, M. B., Barraco, D. E., Paz, S. A., Leiva, E. P. M. (2023).
> NMR, x-ray and Mössbauer results for amorphous Li-Si alloys using density functional
> tight-binding method. _Physical Review B, 108_, 144201.
> DOI: https://doi.org/10.1103/PhysRevB.108.144201
