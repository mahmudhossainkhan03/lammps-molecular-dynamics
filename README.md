# Molecular Dynamics Simulations: Tensile Deformation & Fracture Mechanics

Computational molecular dynamics (MD) simulations constructed using **LAMMPS** and visualized via **OVITO** to evaluate atomistic stress-strain responses, crack initiation, and fracture mechanics.

---

## 🔬 Key Projects Included

### 1. Single-Crystal 2D Silicon Carbide (SiC) Tensile & Crack Propagation
* **Simulation Scope:** Uniaxial tensile deformation and progressive fracture modeling of single-crystal 2D SiC sheets.
* **Solvers & Analysis:**
  * Configured customizable LAMMPS input scripts (`in.tensile`, `in.crack`) defining boundary conditions, ensemble dynamics (NPT/NVT), and strain increment rates.
  * Evaluated atomistic stress-strain curves to identify ultimate tensile strength (UTS) and strain-at-break.
  * Extracted atomic trajectories to correlate microstructural lattice defect evolution with macro-scale failure behavior.

### 2. Guaiacyl Lignin Oligomer Tensile Behavior (ReaxFF)
* **Simulation Scope:** Reactive Force Field (ReaxFF) molecular dynamics modeling of guaiacyl lignin oligomers under tensile stretching.
* **Key Focus:** Bond dissociation dynamics, reactive force field energy tracking, and structural deformation behavior under progressive load.

---

## 📁 Repository Structure

```text
├── 2D-SiC-Tensile-Fracture/
│   ├── in.tensile          # LAMMPS script for uniaxial tensile test
│   ├── in.crack            # LAMMPS script for pre-cracked sheet fracture
│   └── data.sic            # Initial atomic coordinate configuration
├── Lignin-ReaxFF-Deformation/
│   ├── in.lignin_stretch   # LAMMPS ReaxFF stretching script
│   └── ffield.reax         # Reactive force field parameter file
└── README.md               # Project documentation
