### Partially Averaged Navier Stokes Simulation Code for OpenFOAM-5.x

#### Simulation Code:
- kEpsilonPANS.C
- kEpsilonPANS.H

where,
- kEpsilonPANS.H is the amalgamation of kEpsilon.H & PANS.H (kEpsilon.H + PANS.H), and
- kEpsilonPANS.C is the amalgamation of kEpsilon.C & PANS.C (kEpsilon.C + PANS.C)

<br>

#### PANS.H & PANS.C
- Custom written OpenFOAM-5.x code.
- Implementes the Partially Averaged Navier Stokes Equations on the Turbulence Model.

<br>

#### kEpsilon.H & kEpsilon.C:
- Standard OpenFOAM kEpsilon Files for Turbulence Model.
  
- kEpsilon.H
   - Source: https://www.openfoam.com/documentation/guides/latest/api/TurbulenceModels_2turbulenceModels_2RAS_2kEpsilon_2kEpsilon_8H_source.html
   - Documentation: https://www.openfoam.com/documentation/guides/latest/api/TurbulenceModels_2turbulenceModels_2RAS_2kEpsilon_2kEpsilon_8H.html
   
- kEpsilon.C
   - Source: https://www.openfoam.com/documentation/guides/latest/api/TurbulenceModels_2turbulenceModels_2RAS_2kEpsilon_2kEpsilon_8C_source.html
   - Documentation: https://www.openfoam.com/documentation/guides/latest/api/TurbulenceModels_2turbulenceModels_2RAS_2kEpsilon_2kEpsilon_8C.html

<br>
