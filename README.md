# Caltech-Computational-Engineering
An advanced computational nanotech engineering project tracking the design, routing, and coarse-grained molecular dynamics simulation of dynamic DNA origami mechanisms. Developed with academic guidance from Dr. Paul Rothemund (Caltech).

## Structural Design & Biophysical Modeling
The architecture transitions from 2D scaffold routing to a 3D pre-bent equilibrium state to establish the mechanical safety gate geometry.

<p align="center">
  <img src="https://github.com/user-attachments/assets/dde51c71-0798-46f9-925e-ed93feafdcae" width="100%" alt="caDNAno Scaffold and Staple Routing Diagram" />
  <br />
  <em>Figure 1: 2D scaffold-routing lattice path and staple crossover coordinates mapped in caDNAno.</em>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/f1027bc8-9418-4657-83b3-99f4e6a7d590" width="631" height="472" alt="cando-model" />
  <br />
  <em>Figure 2: 3D finite element simulation model (CanDo) displaying the predicted structural curvature and mechanical flexibility profile of the locked C-shape state.</em>
</div>

## Project Overview & Mechanism
The objective of this project is to engineer a dynamic "C-to-straight" structural DNA origami switch that acts as a mechanical safety gate for antimicrobial peptides to prevent off-target toxicity on healthy human cells:
- **Off-Target Protection (Banded C-Shape):** When bent into a tight C-shape, the outer surface stretches, physically separating the peptides to prevent cooperative pore formation on host cells. A secondary PEG bumper layer provides steric hindrance.
- **Targeted Activation (Straightened Grid):** Bacterial targeting antibodies unlock a mechanical latch, causing the structure to flatten. As it straightens, the outer surface helices contract to baseline, forcing the peptides into a high-density, synchronized grid that cooperatively disrupts and pops the target bacterial wall.

## Computational Data Pipeline
To move beyond visual simulations, this project utilizes a custom Python-based data analysis pipeline to evaluate structural integrity:
* **Data Parsing:** Leveraging `Pandas` and `NumPy` to process massive trajectory configuration files and coordinate outputs exported from `oxDNA` and `CanDo`.
* **Quantitative Metrics:** Tracking Root-Mean-Square Deviation (RMSD) over simulation runtimes to evaluate thermodynamic equilibrium.
* **Geometric Analysis:** Calculating real-time fluctuations in the design's C-shape curvature radius to statistically prove the stability of the mechanical gate before physical synthesis.

## Research Milestones & Evaluation
Project progression, risk assessment, and milestone evaluation are strictly structured around the [DARPA Heilmeier Catechism](https://www.darpa.mil/work-with-us/heilmeier-catechism) to ensure rigorous defense for academic track and competition reviews.

### Project Timeline

* **[X] Phase 1: Structural Design & Scaffold Routing (Completed)** Mapped the primary geometric architecture and cross-over points in caDNAno to establish structural boundaries.

* **[-] Phase 2: Transition State Simulations (In Progress)** Setting up environment parameters in `oxDNA` to model relaxation mechanics and verify the mechanical stability of the locked C-shape.

* **[ ] Phase 3: Peptide Grid Optimization** Modeling the cooperative binding constants and local density thresholds required to overwhelm the bacterial membrane.

* **[ ] Phase 4: Synthesis & Research Layout** Compiling simulation transition renders, structural energy profiles, and quantitative logs for final presentation.
