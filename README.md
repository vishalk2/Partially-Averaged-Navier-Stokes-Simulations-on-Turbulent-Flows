# Partially Averaged Navier Stokes (PANS) Simulations on Turbulent Flows and Effective Comparasion against Large Eddy Simulations (LES)
<br>

### Contents
- [ABOUT](#about)
- [KEYWORDS](#keywords)
- [RESEARCH](#research)
- [CODE](#code)
- [SIMULATIONS](#simulations)

<br>
<hr>
<br>

### ABOUT

This Research Work constitutes:
- Partially Averaged Navier Stokes (PANS) Model Implementation for turbulent flows.
- PANS Simulation on the "PitzDaily" case on OpenFOAM-5.x (pimpleFoam).
- Effective comparison between PANS Simulations and Large Eddy Simulations (LES).

<br>
<hr>
<br>

### KEYWORDS

- Computation Fluid Dynamics (CFD)
- Partially Averaged Navier Stokes (PANS)
- PANS Modelling
- PANS Turbulence Model
- Large Eddy Simulations (LES)
- OpenFOAM-5.x

<br>
<hr>
<br>

### RESEARCH

Partially Averaged navier Stokes (PANS) vs Large Eddy Simulations (LES) for Turbulent Flows:
- Researched the Partially Averaged Navier Stokes (PANS) model.
- Implemented the PANS model using OpenFOAM-5.x (pimpleFoam) for the "PitzDaily" case.
- Implementation of PANS involved developing and validating numerical algorithms to simulate turbulent flows with improved accuracy and computational efficiency.
- Applied numerical techniques to study and accurately capture the movements and interactions of the granular particles.
- Effectively compared the results of PANS simulations against Large Eddy Simulations (LES) based on the velocities of the flows.
- This comparative analysis provided valuable insights into the capabilities and limitations of PANS turbulence modelling approach in predicting flow behaviour.

<br>
<hr>
<br>

### CODE

#### Partially Averaged Navier Stokes Simulation Code for OpenFOAM-5.x

##### Simulation Code:
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
<hr>
<br>

### SIMULATIONS

#### Partially Averaged Navier Stokes (PANS) Simulation compared against the Large Eddy Simulation (LES) for the "PitzDaily" case in OpenFOAM-5.x (pimpleFoam).

<br>

#### - PANS Simulation
<br>

![PANS Simulation](https://github.com/user-attachments/assets/c17eeaf4-65ae-4dc1-945b-8019f4d270ac)

<br>
<br>

#### - LES Simulation
<br>

![LES Simulation](https://github.com/user-attachments/assets/04102345-121e-4395-8798-a27e47b5a49a)

