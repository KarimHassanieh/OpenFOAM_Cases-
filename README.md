# OpenFOAM_Cases-Diffusion
The below cases were simulated using oepnFOAM. The cases are only concerned with pure diffusion. Each example has a seperate solver.

Variables involved :

\[
{\Gamma} =  Diffusivity
\]
\[
{T} =  Temperature  
\]
\[
{Q} =  Source
\]



## Case of Pure Disffusion :

The below equation describes a state of pure diffusion :

\[
{\Gamma} \frac{\partial^{2} T}{\partial x^2} = 0
\]

![Temp Vs Distance in case of pure diffusion](1D_SteadyDiffusion/Results/Example_1_Diffusion_only/temp.distance.png)
![Initial State](1D_SteadyDiffusion/Results/Example_1_Diffusion_only/initial.png)
Initial State with boundary conditions
![Final State](1D_SteadyDiffusion/Results/Example_1_Diffusion_only/final.png)
Final State
## Case of Pure Disffusion with Source :

The below equation describes a state of pure diffusion with source:

\[
{\Gamma} \frac{\partial^{2} T}{\partial x^2} = Q
\]


![Temp Vs Distance in case of pure diffusion](1D_SteadyDiffusion/Results/Example_2_Diff_with_Source/temp_distance.png)
![Initial State](1D_SteadyDiffusion/Results/Example_2_Diff_with_Source/initial.png)
Initial State with boundary conditions
![Final State](1D_SteadyDiffusion/Results/Example_2_Diff_with_Source/final.png)
Final State
