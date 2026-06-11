Hi, I'm Prithvi Naga Simha 👋

Welcome to my GitHub. This is where I document the tools, solvers, and simulation frameworks I build — most of them grounded in aerodynamics and computational fluid dynamics.

My M.Sc. in Aerospace Engineering at TU Munich is centered on fluid and aerodynamics — boundary layer theory, turbulent flows, turbomachinery CFD, and aerothermodynamics. I am drawn to problems where physical understanding and numerical method go hand in hand.

Here you will find a viscous-inviscid airfoil solver built from first principles, a parametric turbomachinery design tool that was designed by modifying the PyTurbo framework by NASA, a OpenFOAM RANS wing case, and documentation of the large-scale parallel MD framework I built for my master's thesis.

What I work with: OpenFOAM · Ansys CFX/Fluent · C++ · MPI · Python · MATLAB · LAMMPS · SLURM/HPC workflows

---

## Featured projects

### [2D Vortex Panel Method with Boundary Layer Coupling](https://github.com/Prithvi1352/Vortex_panel_method)
A from-scratch viscous-inviscid airfoil solver in Python. Linear-strength vortex panel method coupled with integral boundary layer methods. Validated against XFOIL to 0.57% agreement on NACA 0012.

### [3D Turbomachinery Blade Design Tool](https://github.com/Prithvi1352/3D_Turbomachinery_Tool_Semester_thesis)
Semester thesis at the TUM Chair of Turbomachinery and Flight Propulsion. Meanline design and parametric centrifugal compressor impeller geometry generation built on NASA's PyTurbo, extended with custom hub and shroud contour generation.

### [OpenFOAM Wing Case](https://github.com/Prithvi1352/OpenFOAM-simple-wing-case)
Steady RANS simulation setup for a 3D wing using snappyHexMesh and simpleFoam, serving as the high fidelity reference for the panel method solver above.

### [LAMMPS Framework Modification for Parallel Replica Dynamics](https://github.com/Prithvi1352/LAMMPS_Master_Thesis)
Master's thesis at the TUM Chair of Thermodynamics. Custom bond-breaking based event detection algorithm in LAMMPS for Parallel Replica Dynamics with spatial domain decomposition, enabling long timescale simulations of ablative thermal protection materials on HPC systems — the atomistic side of aerothermodynamic reentry modeling.
