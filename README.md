# Eddy Saturation: Barotropic vs Baroclinic

A manuscript investigating the relative importance of baroclinic and barotropic processes for eddy saturation in Southern Ocean-like zonally re-entrant channel on a beta-plane.

> Constantinou, N. C. and Hogg, A. McC. (2019). Eddy saturation of the Southern Ocean: a baroclinic versus barotropic perspective. *Geophys. Res. Lett.*, **46**, 12202–12212. doi:[10.1029/2019GL084117](https://doi.org/10.1029/2019GL084117).

Simulations were performed using GFDL's [Modular Ocean Model version 6][mom6]. Input and configuration files for the simulations can be found in repository [EddySaturation-MOM6][mom6-input].

### Contents

`figures`: folder with jupyter notebooks ([IJulia](https://github.com/JuliaLang/IJulia.jl)) that produce the manuscript figures.

`data`: folder in which the NetCDF (`.nc`) output files are expected to be found. NetCDF files are online, doi:[10.5281/zenodo.3246030](https://doi.org/10.5281/zenodo.3246030). The executable of MOM6 used for these simulations was compiled by cloning [MOM6-examples repo @ commit 6526357](https://github.com/NOAA-GFDL/MOM6-examples/tree/65263572cceeeb18d930ab59fd7f6cddc4642eeb).

`submissions`: folder with all manuscript versions submitted to GRL and to arXiv.


Contributors: [Navid C. Constantinou](http://www.navidconstantinou.com) (@navidcy) and [Andy McC. Hogg](http://rses.anu.edu.au/people/academics/prof-andy-hogg) (@AndyHoggANU).

[mom6]: https://github.com/NOAA-GFDL/MOM6
[mom6-input]: https://github.com/navidcy/EddySaturation-MOM6

