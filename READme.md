# Hamster Ig TCR

## Cregions folder
Ig/TCR constant region consensus sequences described in Adams et al. (2025) stored as fasta file **Hamster_IgTCR_Cregions.fasta**.
IMGT's germline annotations of the C-regions from our Iso-Seq data on the hamster reference genome are provided as links in a table in the folder.

## IgBLAST folder 
The IgBLAST folder contains the IgBLAST database files used for the hamster constant region consensus sequence analysis.

### IMGT_reference_sequences subfolder
Combined IMGT Ig/TCR constant, variable, diversity, and joining germline sequences from mouse 
used to construct the IgBLAST database are stored as fasta files.

## IgDiscover folder 
Contains IgDiscover input yaml file and ouputs from the Iso-Seq data that passed filtering in the consensus sequence generation pipeline described by Adams et al.

## TRBC1_ProteinStructures folder
Contains the AlphaFold3 predicted hamster TRBC1 structures for the hamster reference (i.e. genomic sequence matches the reference genome) and alternate (i.e. SNV that led to non-synonmyous amino acid change) structures as well as the human crystal structure (7AMP) from Protein Data Bank.

# Hamster Ig/TCR Resources

This repository contains supporting data and resources related to the **Ig and TCR constant region analyses** described in *Adams et al. (2025)*, including consensus sequences, IgBLAST databases, IgDiscover outputs, and TRBC1 structural models.

---

## Cregions Folder

- Contains Ig/TCR constant region consensus sequences generated from hamster **Iso-Seq** data, stored in FASTA format:  
  - `Hamster_IgTCR_Cregions.fasta`
  
- **IMGT germline annotations** of the C-region consensus sequences, based on alignment to the hamster reference genome, are provided via external links in a summary table within this folder.

---

## IgBLAST Folder

- Contains **IgBLAST database files** used for hamster constant region consensus sequence analysis.

### IMGT_reference_sequences Subfolder

- Includes combined **IMGT germline sequences** (constant, variable, diversity, and joining regions) from **mouse**, used to construct the IgBLAST database. All sequences are provided in FASTA format.

---

## IgDiscover Folder

- Contains the **IgDiscover input YAML file** and **output results** from the Iso-Seq data used for consensus sequence generation and germline gene prediction, as described in *Adams et al. (2025)*.

---

## TRBC1_ProteinStructures Folder

- Contains **AlphaFold3-predicted hamster TRBC1 structures** for:
  - The **reference** sequence (genomic sequence matching the hamster reference genome):  
    - `fold_trbc1_213a_ref_hamster_model_0.cif`
  - The **alternate variant** containing a non-synonymous SNV (**213A>G**) that introduces the **S71G amino acid substitution**:  
    - `fold_trbc1_213g_alt_hamster_model_0.cif`

- Includes the **human TRBC1 crystal structure** (PDB ID: 7AMP), obtained from the Protein Data Bank:  
  - `7amp.pdb`

---

For more details on the methods and analyses, refer to *Adams et al. (2025)*.

