# hxespmethod_structures

This repository contains structures used in the HXESP manuscript.

Structures used for inputs to modelling by flexible docking or HX-ESP are located in "apo_input". 

Files for each target protein and ligand pair are housed in separate folders and follow the following convention where an asterisk represents a wildcard where variable text may be used. E.g. Ben*Walters would include BenjaminThomasWalters.

In each folder:


Xtal_ref.pdb corresponds to the structural coordinates used for the target X-ray structure. Only one file exists in each folder.

cluster*.pdb corresponds to the structural coordinates produced by the best scorring HADDOCK model. There are four files in each folder.

min*.pdb corresponds to converged HX-ESP structural coordinates. There are at least five files for any convered state. Additional text is added for forward and reverse states observed in PAK-1:GNE8350.

relaxed*.pdb corresponds to relaxed X-ray models as described in the main text. There are three files in each folder.
