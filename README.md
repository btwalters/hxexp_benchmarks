# hxespmethod_structures

This repository contains structures used in the HXESP manuscript.
Currently available on BioRxiv: 

Walters, B. T., Patapoff, A. W., Wang, W., Wu, P. & Kiefer, J. A. Integrating Hydrogen Exchange with Molecular Dynamics for Improved Ligand Binding Predictions. bioRxiv, 2025, https://doi.org/10.1101/2025.01.13.632795

Structures used for inputs to modelling by flexible docking or HX-ESP are the same for each HPK1 and PAK1 folder.  

* represents a wildcard, any text may be found here.

In each folder:

# APO.cif 
corresponds to the structural coordinates used for the unbound X-ray structure used as an input for HX-ESP or flexible docking, ligand removed per manuscript. 
Note, the same structure is found in all HPK1 or PAK1 folders (PDBID: 9NBS for HPK1, 9N4U for PAK1).
# BOUND.cif 
corresponds to the structural coordinates used for the target X-ray structure of each benchmark
# cluster*.cif
corresponds to the structural coordinates produced by the best scoring HADDOCK model. There are four files in each folder.
# min*.cif
corresponds to converged HX-ESP structural coordinates. There are at least five files for any convered state. Additional text is added for forward and reverse states observed in PAK-1:GNE8350.
# us###ns*.cif
corresponds to relaxed X-ray models as described in the main text. There are three files in each folder.
