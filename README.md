# Modelling of the optical properties of gold & silver nanoparticles with alternating morphologies using finite element method
The code is written in plain text, and is meant to be copy/pasted into the MATLAB editor. Only the '.m' files containing refractive indices have to be installed.
## Analytical model for spherical nanoparticles
  1. Ensure that files nrau.m, nrag.m, niau.m and niag.m are installed and visible in matlab folder.
  2. Run the absorption calculation code. [link](a)
## Finite element method
### Pulse expansion:
  1. Ensure that files nrau.m, nrag.m, niau.m and niag.m are installed and visible in the MATLAB folder.
  2. Run the 3D model for either spheres, rods or prisms.
  3. Run the absorption calculation code. Make sure that the variables from the 3D model haven't been cleared.
  
notes: Choose between gold or silver nanoparticles by choosing permitivitty on line 61 in the absorption calculation code, the direction of the E-field is chosen on line 58. The prism model can be rotated around the z-axis on line 278 in its source code.

![3D_point_model_of_prism](3D_point_model_of_prism.png) ![Ag_rods_plot](Ag_rods_plot.png)
### Linear expansion (not yet finished)
  1. Ensure that files nrau.m, nrag.m, niau.m and niag.m are installed and visible in the MATLAB folder.
  2. Ensure that the MATLAB add-on 'Partial Differential Equation Toolbox' is installed.
