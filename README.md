# Orbit Interactive Plots

## Install
- Install Julia 1.6.5
- Install Jupyter Notebook Interface
- Add the path to julia on the bash rc. 
  Ex. On Linux, this is the following command to add to the bash rc. (replace         /home/fausto with your home directory)\
export PATH=$PATH:/home/fausto/julia-1.6.5/bin\
- Next, type in the following commands to connect Julia and Jupyter
  - using Pkg
  - Pkg.add("IJulia")

### Dependencies
These are the following dependencies installed on the local environment. If there is trouble with the local environment (Project.toml and Manifest.toml), try making your own environment and adding the following packages.

- BenchmarkTools v1.3.1
- Colors v0.12.8
- FileIO v1.15.0
- ForwardDiff v0.10.32
- GLMakie v0.6.13
- SatelliteDynamics v0.4.3
- StaticArrays v1.5.4
- DelimitedFiles
- LinearAlgebra

### Run 
Run the using_Makie-v5.ipynb file on jupyter labs for the interactive orbit constellation on Makie. 
