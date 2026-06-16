# EGFR-Gefitinib-PyMOL-Analysis
Structural analysis of the EGFR-Gefitinib complex using PyMOL.


## Overview

This project presents a structural analysis of the Epidermal Growth Factor Receptor (EGFR) kinase domain in complex with the inhibitor Gefitinib using PyMOL.

The crystal structure analyzed was PDB ID: 4WKQ. The study focused on visualization of the protein-ligand complex and identification of residues surrounding the ligand-binding pocket.

## Objectives

* Visualize the EGFR-Gefitinib complex
* Examine the ATP-binding site
* Identify residues within 4 Å of Gefitinib
* Explore protein-ligand interactions using PyMOL

## Key Binding Site Residues

* LEU718
* LYS745
* THR790
* MET793
* ASP855

## Tools Used

* PyMOL
* Protein Data Bank (PDB)

## Files Included

* Structural analysis report (PDF)
* PyMOL session file (.pse) 
* Structural images 

## Structure Information

* Protein: Epidermal Growth Factor Receptor (EGFR)
* Ligand: Gefitinib
* PDB ID: 4WKQ

## PyMOL Commands Used

```pml
fetch 4WKQ

hide everything
show cartoon
color cyan

select ligand, organic
show sticks, ligand
color orange, ligand

select pocket, byres (ligand around 4)
show sticks, pocket
color green, pocket

zoom ligand
```

