## Hi, I’m Alon 👋

Physics PhD student focused on **scientific software, simulation, algorithm development, and collaborative workflows**.
Experienced with large production codebases, cross-institution workflows, and research-grade debugging.
Comfortable working at the intersection of physics and software engineering.

---

## Selected Projects

### CLAS12 Sample Tools
**Configurable sample preparation and HPC job submission for detector simulation**

- Developed a unified workflow for creating simulation input from uniformly sampled particle kinematics or existing GENIE event output
- Centralized configuration validation, target vertex sampling, file handling, and run metadata across both input paths
- Automated Slurm job-array submission for GEMC detector simulation and COATJAVA reconstruction at Jefferson Lab
- Structured the code to support additional event-generator formats without duplicating the common workflow
- Tech stack: C++, Python, C shell, ROOT, CMake, Slurm

**Repositories:** [Personal](https://github.com/alons126/CLAS12-sample-tools) · [e4ν collaboration](https://github.com/e4nu/CLAS12-sample-tools)  
**Documentation:** [Personal wiki](https://github.com/alons126/CLAS12-sample-tools/wiki) · [Collaboration wiki](https://github.com/e4nu/CLAS12-sample-tools/wiki)

---

### GEMC / CLAS12 Target Implementation (RG-M)
**Production geometry implementation merged into an international, multi-institutional simulation framework**

- Implemented Ar, C, and Sn target geometries and configurations
- Code merged into the official repositories
- Author of a published CLAS12 technical note documenting the implementation (CLAS12 Note 2026-001)
- Tech stack: Perl, CAD-based geometry workflows, GEANT4 / GEMC simulation framework

**PR (clas12Tags):** https://github.com/gemc/clas12Tags/pull/64  
**PR (clas12-config):** https://github.com/JeffersonLab/clas12-config/pull/119  
**Technical note:** https://misportal.jlab.org/mis/physics/clas12/viewFile.cfm/2026-001.pdf?documentId=185

---

### SuSA Electron-Mode Validation (GENIE)
**Bug identification and fix in a production neutrino–nucleus interaction generator**

- Identified a bug where the GENIE event generator (v3.2) generated only 1n1p final states for 2p2h SuSA-MEC
- Traced the issue to missing/misused hadronic tensor tables and incorrect pair selection logic
- Integrated new tensor tables, fixed probability calculations, and restored 2p / 2n final states
- Corrections merged into the official GENIE codebase (v3.4+); contributor within the GENIE collaboration

**PR:** https://github.com/GENIE-MC/Generator/pull/242  
Detailed validation in MSc thesis, Section 9.1.3

---

## Skills
- **Languages:** C++, Python, Perl
- **Scripting:** Bash, C shell (csh)
- **Build tools:** CMake, Make
- **Configuration and data formats:** XML, JSON, GEMC gcard files
- **Frameworks:** ROOT, CLAS12ROOT, GENIE, GEANT4, GEMC
- **Development tools:** Git / GitHub (pull requests, code reviews)
- **Software engineering:** Modular software design, workflow automation, configuration validation, debugging, technical documentation
- **Domains:** Monte Carlo simulation, scientific validation, particle physics software, detector geometry, data analysis, event reconstruction, algorithm development
- **Systems:** Linux, HPC environments, Slurm job arrays
