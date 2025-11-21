# Quantum Curve Version 0.1.1

## 🍰1. About



Quantum Curve is a free middleware application for computational chemistry. We plan to continuously expand the list of supported programs and input formats in future releases. 💐

<img width="1665" height="933" alt="image" src="https://github.com/user-attachments/assets/d81f679e-4708-4dcd-b035-c30b1000c19d" />


Changes in Quantum Curve version 0.1.1:

1. Updated the right-click pan interaction to avoid strange rotation centers after panning. Ctrl + right-click behavior is unchanged.
2. Added support for reading vibrational frequencies and structures from ORCA .out/.hess files, viewable under Results → IR, and exporting frequency data as .txt/.csv.
3. Added support for reading frequency and structure information from Gaussian .out/.log output files.
4. Added support for extracting per-step structures from ORCA geometry optimizations in .out files.
5. Added support for reading ORCA .molden files (generated from .gbw) and exporting HOMO/LUMO orbitals as .cube files.
6. Added support for reading structure and cell information from .cif files, editing cell parameters in a panel, exporting .cif files, and converting between .gjf and .cif with embedded structural data.
7. Added support for extracting energy changes along optimization paths from ORCA/Gaussian output files.
8. Changed carbon atom labels to render in white.
9. Added stick and line display models, plus a bond coloring toggle that colors bonds using neighboring atom colors when enabled.
10. Added export of the viewer content as .jpg/.svg/.pdf.
11. Added support for changing the viewer background color.
12. Added parsing of molecular structures from POSCAR, STRU, .wfn, and .wfx files.
13. Added support for reading molecular structures from QE .in files.
14. Added visualization of ghost atoms in Gaussian/ORCA outputs and a ghost atom entry in the periodic table.
15. Added an Application font setting for customizing the app font.
16. Added SSH connections to remote servers.








## 🌸2. Supported input/output files



| V 0.1.1  |     Format     | Atom coordinates (I/O) | Cell | Vibrations (I) | Optimization (I) | GTFs | Version |
| :------: | :------------: | :--------------------: | ---- | :------------: | :--------------: | :--: | :-----: |
|          |      .xyz      |          ✅/✅           |      |                |                  |      |  Beta   |
|          |      .mol      |          ✅/❌           |      |                |                  |      |  Beta   |
|          |     .mol2      |          ✅/❌           |      |                |                  |      |  Beta   |
|          |      .pdb      |          ✅/✅           |      |                |                  |      |  Beta   |
|          |      .cif      |          ✅/✅           | ✅    |                |                  |      |  Beta   |
|          |   .cube/.cub   |          ✅/❌           |      |                |                  |      |  Beta   |
|          |      .wfn      |          ✅/❌           |      |                |                  |      |  Beta   |
|   ORCA   |      .inp      |          ✅/✅           |      |                |                  |      |  Beta   |
|   ORCA   |      .out      |          ✅/❌           |      |       ✅        |        ✅         |      |  Beta   |
|   ORCA   |     .hess      |          ✅/❌           |      |       ✅        |                  |      |  Beta   |
|   ORCA   | .molden/.input |          ✅/❌           |      |                |                  |  ✅   |  Beta   |
| Gaussian |      .gjf      |          ✅/✅           | ✅    |                |                  |      |  Beta   |
| Gaussian |   .out/.log    |          ✅/❌           |      |       ✅        |        ✅         |      |  Beta   |
| Gaussian |   .fch/.fchk   |          ✅/❌           |      |                |                  |  ✅   |  Beta   |
| Gaussian |      .wfx      |          ✅/❌           |      |                |                  |      |  Beta   |
|  MOPAC   |      .mop      |          ✅/❌           |      |                |                  |      |  Beta   |
|   PSI4   |      .inp      |          ✅/❌           |      |                |                  |      |  Beta   |
|   CP2K   | .inp/.restart  |          ✅/❌           | ✅    |                |                  |      |  Beta   |
|    QE    |      .in       |          ✅/❌           | ✅    |                |                  |      |  Beta   |
|   VASP   |     POSCAR     |          ✅/✅           | ✅    |                |                  |      |  Beta   |
|  ABACUS  |      STRU      |          ✅/❌           | ✅    |                |                  |      |  Beta   |
|          |                |                        |      |                |                  |      |         |





## 💡3. Supported keyboard and mouse interactions:



1. Left-click to rotate (does not affect molecular coordinates).
2. Right-click to move (does not affect molecular coordinates).
3. Ctrl + Left-click to rotate (**changes molecular coordinates**).
4. Ctrl + Right-click to move (**changes molecular coordinates**).
5. Double-clicking an atom selects the connected fragment.





## 🗓 4. To Do List:



1. 🍦
2. 🎃
3. 🐱
4. 🐶
