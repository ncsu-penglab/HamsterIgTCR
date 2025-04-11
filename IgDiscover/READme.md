# IgDiscover

## igdiscover.yaml
This is the yaml file used for the IgDiscover analysis. 
The yaml files uses permissive parameters to handle single-end Iso-Seq reads for V, D, and J gene segment discovery in hamster.

## Snakefile
This is the modifed Snakefile used for the IgDiscover analysis.
It is tailored to bypass analysis using the J gene segments since no J genes were discovered.

## predicted_genes
This folder contains IgDiscover predicted V and D gene segments using IgDiscover. 
Inputs include the Mus musculus Ig/TCR V, D, and J gene segement germline sequences used in the IgBLAST used in the Adams et al. paper.
