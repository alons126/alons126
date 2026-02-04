## Hi, I’m Alon 👋

Physics PhD student focused on **scientific software, simulation, algorithm development, and collaborative workflows**.
Experienced with large production codebases, cross-institution workflows, and research-grade debugging.
Comfortable working at the intersection of physics and software engineering.

---

## Selected Projects

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
- **Scripting:** Bash, C shell (csh), Makefile
- **Configuration formats:** XML, GEMC gcard files
- **Frameworks:** ROOT, CLAS12ROOT, GENIE, GEANT4, GEMC
- **Tools:** Git / GitHub (PRs, reviews), CMake
- **Domains:** Monte Carlo simulation, particle physics software, Scientific simulation, detector geometry, data analysis, event reconstruction, algorithm development
- **Systems:** Linux, HPC environments (batch systems, shared clusters), Slurm

<!-- ---

Currently open to **industry roles** in scientific software, simulation, or data-oriented engineering. -->
