# Hi, I'm Prithvi Naga Simha 👋

Welcome to my GitHub. This is where I document the tools, solvers, and simulation studies I build, most of them grounded in aerodynamics and computational fluid dynamics.

My M.Sc. in Aerospace Engineering at TU Munich is centered on fluids and aerodynamics: boundary layer theory, turbulent flows, turbomachinery CFD, and aerothermodynamics. I am drawn to problems where physical understanding and numerical method go hand in hand, building solvers from first principles alongside production tools like OpenFOAM and Ansys CFX.

Here you will find my two theses alongside a set of solvers and CFD studies spanning external aerodynamics, turbomachinery, heat transfer, and machine learning applied to design. Each project has its own story, so the README is worth reading.

---

### 🛠️ Tech Stack

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![MPI](https://img.shields.io/badge/MPI-5C2D91?style=for-the-badge)
![OpenFOAM](https://img.shields.io/badge/OpenFOAM-052B4E?style=for-the-badge)
![Ansys](https://img.shields.io/badge/Ansys%20CFX-FFB71B?style=for-the-badge&logo=ansys&logoColor=black)
![LAMMPS](https://img.shields.io/badge/LAMMPS-4B4B4B?style=for-the-badge)
![HPC](https://img.shields.io/badge/HPC%20%2F%20SLURM-darkgreen?style=for-the-badge)

---

## 📘 Theses

### 🧬 [LAMMPS Framework Modification for Parallel Replica Dynamics](https://github.com/Prithvi1352/LAMMPS_Master_Thesis)
**Master's thesis — TUM Chair of Thermodynamics.** Custom bond-breaking based event detection algorithm in LAMMPS for Parallel Replica Dynamics with spatial domain decomposition, enabling long timescale simulations of ablative thermal protection materials on HPC systems. Validated for first-order escape kinetics and scaled to 112 replicas on the LRZ cluster: the atomistic side of aerothermodynamic reentry modeling.

### ⚙️ [3D Turbomachinery Blade Design Tool](https://github.com/Prithvi1352/3D_Turbomachinery_Tool_Semester_thesis)
**Semester thesis — TUM Chair of Turbomachinery and Flight Propulsion.** Meanline design and parametric centrifugal compressor impeller geometry generation built on NASA's PyTurbo, extended with custom hub and shroud contour generation. Station-wise aerothermodynamics through to a full 3D impeller.

---

## 🔬 Projects

### 🌀 [2D Vortex Panel Method with Boundary Layer Coupling](https://github.com/Prithvi1352/Vortex_panel_method)
A from-scratch viscous-inviscid airfoil solver in Python. Linear-strength vortex panel method coupled with integral boundary layer methods. Validated against XFOIL to 0.57% agreement on NACA 0012.

### 🔄 [Compressor Rotor Relief Study — Ansys CFX](https://github.com/Prithvi1352/Rotor_relief)
Comparative 3D CFD study of rotor blade relief in an axial compressor stage at TUM. Full speed lines from surge to choke for 35 and 39 blade configurations: blade loading, tip vortex strength, separation behavior, and stage performance.

### 🔥 [Cooling Fin Optimisation — Physics-Informed ML](https://github.com/Prithvi1352/cooling-fin-piml)
Surrogate-assisted optimisation of aircraft engine cooling fin geometry in MATLAB. A 2D finite difference heat solver provides ground-truth data, a neural network surrogate replaces expensive solves during optimisation, and adaptive refinement concentrates sampling in the promising design region. Standard aerospace MDO workflow, built end to end.

### 🛩️ [OpenFOAM Wing Sweep Study](https://github.com/Prithvi1352/OpenFOAM-simple-wing-case)
Transient RANS study of a NACA 2412 wing comparing zero sweep and 15° sweep configurations. Parametric STL geometry generation in Python, snappyHexMesh workflow, pimpleFoam with k-omega SST: the high fidelity reference for the panel method solver above.

---

## 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prithvi-n-simha/)

Open to PhD positions and engineering roles in aerodynamics, CFD, and turbomachinery across Europe
