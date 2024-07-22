### Partially Averaged Navier Stokes Simulation Code for OpenFOAM-5.x

#### Simulation Code:
- kEpsilonPANS.C
- kEpsilonPANS.H

where,

#### kEpsilonPANS.H = kEpsilon.H + PANS.H

#### kEpsilonPANS.C = kEpsilon.C + PANS.C

<br>

#### PANS.H & PANS.C
- Custom written code that implementes the Partially Averaged Navier Stokes Equations

<br>

#### kEpsilon.H & kEpsilon.C:
- Standard OpenFOAM kEpsilon Files for Turbulence Model.
- Documentation:
   1. https://www.openfoam.com/documentation/guides/latest/api/TurbulenceModels_2turbulenceModels_2RAS_2kEpsilon_2kEpsilon_8H.html
   2. https://www.openfoam.com/documentation/guides/latest/api/TurbulenceModels_2turbulenceModels_2RAS_2kEpsilon_2kEpsilon_8C.html

<br>
