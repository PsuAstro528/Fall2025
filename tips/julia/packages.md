+++
title = "Commonly used Julia Packages"
tags = ["tips","julia"]
+++

## File I/O
- [CSV.jl](https://github.com/JuliaData/CSV.jl)
- [FITSIO.jl](https://github.com/JuliaAstro/FITSIO.jl) (wrapper for C library)
- [FITSFiles.jl](https://github.com/barrettp/FITSFiles.jl) (up & coming, all julia, but not as mature as FITSio.jl)
- [HDF5.jl](https://github.com/JuliaIO/HDF5.jl)
- [JLD2.jl](https://github.com/JuliaIO/JLD2.jl)
- [FileIO.jl](https://github.com/JuliaIO/FileIO.jl)
- [FortranFiles.jl](https://github.com/JuliaData/FortranFiles.jl)     
- [VOTables.jl](https://github.com/JuliaAstro/VOTables.jl)
- [TOML.jl](https://github.com/JuliaLang/TOML.jl)

## [Data Wrangling](https://github.com/JuliaData)  
- [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl)
- [Query.jl](https://github.com/queryverse/Query.jl)

## [Math](https://github.com/juliamath)
- [LinearAlgebra in Julia standard libary](https://docs.julialang.org/en/v1/stdlib/LinearAlgebra/)
- [LinearSolve.jl](https://github.com/SciML/LinearSolve.jl)
- [SpecialFunctions.jl](https://github.com/JuliaMath/SpecialFunctions.jl)
- [SIMDMathFunctions](https://github.com/ClimFlows/SIMDMathFunctions.jl)
- [Polynomials.jl](https://github.com/JuliaMath/Polynomials.jl)
- [NonlinearSolve.jl](https://github.com/SciML/NonlinearSolve.jl)
- [Interpolations.jl](https://github.com/JuliaMath/Interpolations.jl) (see also list of related packages near bottom of README)
- [DataInterpolations.jl](https://github.com/SciML/DataInterpolations.jl)
- [Surrogates.jl](https://github.com/SciML/Surrogates.jl)

### Time series
- [DSP.jl](https://github.com/JuliaDSP/DSP.jl)
- [FFTW.jl](https://github.com/JuliaMath/FFTW.jl)
- [LombScargle.jl](https://github.com/JuliaAstro/LombScargle.jl)

### Integration
- [QuadGK.jl](https://github.com/JuliaMath/QuadGK.jl):  1-d integration
- [Sobol.jl](https://github.com/JuliaMath/Sobol.jl)
- [Integrals.jl](https://docs.sciml.ai/Integrals/stable/):  unified interface for the numerical approximation of integrals 
- [OrdinaryDiffEq.jl](https://github.com/SciML/OrdinaryDiffEq.jl)

## [Statistics](https://juliastats.org/)
- [Julia standard library](https://docs.julialang.org/en/v1/stdlib/Statistics/)
- [Distributions.jl](https://github.com/JuliaStats/Distributions.jl)
- [StatsBase.jl](https://github.com/JuliaStats/StatsBase.jl)
- [KernelDensity.jl](https://github.com/JuliaStats/KernelDensity.jl)
- [MultivariateStats.jl](https://github.com/JuliaStats/MultivariateStats.jl)
- [GLMs.jl](https://github.com/JuliaStats/GLM.jl)
- [Clustering.jl](https://github.com/JuliaStats/Clustering.jl)

### Bayesian Inference
- [Turing.jl](https://github.com/TuringLang/Turing.jl)
- [Pigeons.jl](https://github.com/Julia-Tempering/Pigeons.jl)
- [RxInfer.jl](https://rxinfer.com/)


### Machine Learning
- [MLBase.jl](https://github.com/JuliaStats/MLBase.jl)
- [Optimizers.jl](https://github.com/FluxML/Optimisers.jl)
- [Lux.jl](https://github.com/LuxDL/Lux.jl)

## Plotting
- [Plots.jl](https://github.com/JuliaPlots/Plots.jl)
- [Mackie.jl](https://docs.makie.org/dev/) ([examples](https://beautiful.makie.org/dev/))
- [ColorSchemes.jl](https://github.com/JuliaGraphics/ColorSchemes.jl)
- [LaTeXStrings.jl](https://github.com/JuliaStrings/LaTeXStrings.jl)

## Coding practices
- [Unitful.jl](https://painterqubits.github.io/Unitful.jl/stable/)
- [UnitfulAstro.jl](https://github.com/JuliaAstro/UnitfulAstro.jl)
- [ArgParse.jl](https://github.com/carlobaldassi/ArgParse.jl)
- [PkgTemplates.jl](https://github.com/JuliaCI/PkgTemplates.jl)

## [Astronomy-specific](https://github.com/JuliaAstro/Planck.jl)
### Building blocks
- [SkyCoords.jl](https://github.com/JuliaAstro/SkyCoords.jl)
- [Planck.jl](https://github.com/JuliaAstro/Planck.jl)
- [AstroTime.jl](https://github.com/JuliaAstro/AstroTime.jl)
- [Ephemeris.jl](https://www.google.com/search?q=https://github.com/JuliaAstro/Ephemeris.jl)
- [PlanetOrbits.jl](https://github.com/sefffal/PlanetOrbits.jl)
- [AstroLib.jl](https://github.com/JuliaAstro/AstroLib.jl)

### Photometry
- [PSFModels.jl](https://github.com/JuliaAstro/PSFModels.jl)
- [Photometry.jl](https://github.com/JuliaAstro/Photometry.jl)
- [BoxLeastSquares.jl](https://github.com/JuliaAstro/BoxLeastSquares.jl)
- [Transits.jl](https://github.com/JuliaAstro/Transits.jl)

## Imaging
- [AstroImages.jl](https://github.com/JuliaAstro/AstroImages.jl)

### Modeling
- [Octofitter.jl](https://github.com/sefffal/Octofitter.jl): Orbit fitting
- [Korg.jl](https://github.com/ajwheeler/Korg.jl): Stellar synthesis
- [StellarModels.jl](https://www.google.com/search?q=https://github.com/ajwheeler/StellarModels.jl)
- [Cosmology.jl](https://github.com/JuliaAstro/Cosmology.jl)
