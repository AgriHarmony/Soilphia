Soil Physic for water-soil simulation
=====

# How to describe soil?

[Fractal](https://en.wikipedia.org/wiki/Fractal)


# Richard Equation
Definition & understanding
- [] https://www.youtube.com/watch?v=1nNYO9XL6wc
- [] https://arxiv.org/pdf/1706.03381.pdf
- [] https://philippkraft.github.io/cmf/cmf_tut_solute_transport1_d.html
- [] https://www.youtube.com/watch?v=kWpasCiIeOc


## References
### Books & Documents

- [soil physics with python transport in the soil-plant-atmosphere system](https://global.oup.com/academic/product/soil-physics-with-python-9780199683093?cc=tw&lang=en&)
- [HYDRUS1D Manual](https://www.pc-progress.com/Downloads/Pgm_hydrus1D/HYDRUS1D-4.08.pdf)
- [Soil Water Modeling in Python and Excel](http://www.christopherteh.com/soilwaterbook/)


# Research Papers

- [Numerical Solution of Richards’ Equation: A Review of Advances and Challenges](https://www.researchgate.net/publication/320515457_Numerical_Solution_of_Richards'_Equation_A_Review_of_Advances_and_Challenges)
- [An open source massively parallel solver for Richards
equation: Mechanistic modelling of water fluxes at the
watershed scale](https://hal.archives-ouvertes.fr/hal-01881720/document)

# Implementation direction


## 1. Solve richard equation directly

Reference open source project
- [Unsaturated soil water flow model, cbsteh](https://github.com/cbsteh/PyWaterBal)
- [amireson/RichardsEquation_improved](https://github.com/amireson/RichardsEquation_improved)
- [PMFlow/RichardsEquation](https://github.com/PMFlow/RichardsEquation)
https://github.com/nepluno/apic2d


## 2. Non-richard eqautaion
- [SWB2](https://github.com/smwesten-usgs/swb2)
- [] [Richards Equation, simpeg](http://docs.simpeg.xyz/content/flow/index.html#)


## 3. Solve richard equation with CFD framework (OpenFOAM)

- [Permafrost modelling with OpenFOAM®: New advancements of the permaFoam solver](https://www.sciencedirect.com/science/article/pii/S0010465522002600)
- [hydrology](https://develop.openfoam.com/Community/hydrology)
  
## 4. Solve simulation by Geo-based
https://github.com/ARPA-SIMC/CRITERIA1D

https://docs.simpeg.xyz/