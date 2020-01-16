# Inverse-Design-Tool-for-Multi-Element-Wing-Sections-in-Ground-Effect

## Background and Motivation
The use of development tools for aerodynamic design in Formula 1 is strictly regulated by the sports governing body FIA [1]. This leads to the design process being limited by the allowed allocation of computational resource, opening up for the use of lower cost, lower fidelity design tools to complement conventional CFD and wind-tunnel testing in the design process. The development of such a tool is the subject of this work.

The tool targets design problems where the solution can be prescribed as a pressure distribution and the corresponding geometry solved for. A potential-flow based panel-method is effectively cost-less on modern computers, making it an ideal formulation for this application. 

* Modified workflow of the wing-design process using this tool:
<p align="center">
<img src="Workflow.png" width="425">
</p>

## Potential Flow Analysis and Design Methodology
The elements in a section and its mirror-image is modelled by vortex sheets discretised into M-panels. Specifying constant streamfunction values on the surface, with a Kutta-condition for each element, a closed linear system is formed and solved for the vortex strengths.


NOTE: This tool was developed for my own personal use and is currently not very user friendly. The idea is to work on it further in the future to make it usable without having to dig into the code so much.  
