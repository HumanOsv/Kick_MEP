# Kick-MEP Algorithm

A novel program to looking for global minimum structures of atomic clusters and molecules in gas phase is introduced in this work. This methodology involves calculating the Coulombic integral between the maximum and minimum values of the molecular electrostatic potential, identified on a density isosurface (0.001 Eh, atomic units) between two molecular fragments, to estimate their interaction energy and rapidly select the most suitable configurations at low computational cost. The method operates by constructing a large initial population, stochastically combining (using the Kick method) two fragments that, upon union, achieve the formula of the target system. A subset of candidates is then identified based on the minimum Coulombic integral value between the electrostatic potentials of the fragments. These candidates are further refined through gradient-based optimization and density functional theory calculations. We have assessed the method’s effectiveness by exploring the potential energy surface of silicon-lithium atomic clusters and molecular clusters of H2O. In all cases, the lowest energy structure (global minimum) has been identified. Additionally, this strategy facilitates the pinpointing of local minima that closely approximate the energy of the global minimum. Furthermore, through tests involving Thymol encapsulated within Cucurubut[7]uril, our results demonstrate that KICK-MEP is comparable to Molecular Docking in identifying more stable conformations, while providing a more cost-effective computational solution for exploring the potential energy surface.

<p align="center">
  <img src="https://github.com/HumanOsv/Logos/blob/master/Imagen1.jpg" width="50%">
</p>


    Last update: August, 01-2024
