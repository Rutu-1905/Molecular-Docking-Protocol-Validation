# Molecular-Docking-Protocol-Validation



\# Structure-Based Validation of a Molecular Docking Protocol



\## Project Overview



This project focuses on the structure-based validation of a molecular docking protocol using redocking of a native ligand.



The workflow includes protein preparation, ligand preparation, docking setup, redocking, RMSD-based validation, and protein–ligand interaction analysis.



\## Workflow



1\. PDB structure preparation

2\. Protein preparation

3\. Ligand preparation

4\. Molecular docking using AutoDock Vina

5\. Native ligand redocking

6\. RMSD-based docking pose validation

7\. Protein–ligand interaction analysis



\## Docking Parameters



Grid center:



\- X = 0.725

\- Y = 26.962

\- Z = 26.969



\## Validation Results



| Parameter | Result |

|---|---:|

| Native ligand atoms analyzed | 30 |

| Redocked ligand atoms analyzed | 40 |

| RMSD | 2.303 Å |

| Interacting residues identified | 141 |



\## Tools



\- AutoDock Vina

\- AutoDock Tools

\- PyMOL

\- Protein Data Bank (PDB)



\## Repository Structure



```text

Molecular-Docking-Protocol-Validation/

├── 01\_PDB/

├── 02\_protein/

├── 03\_ligand/

├── 04\_Docking/

├── 05\_RMSD/

├── 06\_interaction/

├── README.md

├── .gitignore

└── .gitattributes

