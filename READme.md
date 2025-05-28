# Hamster Ig/TCR

This repository contains supporting data and resources related to the **Ig and TCR constant region analyses** described in *Adams et al. (2025)*, including consensus sequences, IgBLAST databases, IgDiscover outputs, and AlphaFold3 TRBC1 protein structure predictions.

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
  - The **alternate variant** containing a non-synonymous SNV (**213A>G**) that introduces the **S71G non-synonymous amino acid change**:  
    - `fold_trbc1_213g_alt_hamster_model_0.cif`

- Includes the **human TRBC1 crystal structure** (PDB ID: 7AMP), obtained from the Protein Data Bank:  
  - `7amp.pdb`

---

For more details on the methods and analyses, refer to *Adams et al. (2025)*.

