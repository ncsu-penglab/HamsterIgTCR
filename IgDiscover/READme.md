# IgDiscover Analysis for Hamster V Gene Discovery

This folder contains configuration files and outputs related to **IgDiscover** analysis, specifically optimized for **single-end Iso-Seq reads** used in **V gene segment discovery** in hamster, as described in *Adams et al. (2025)*.

---

## Files and Folders

### `igdiscover.yaml`

- This is the **configuration YAML file** used for running IgDiscover.  
- It includes **permissive parameters** tailored to handle **single-end Iso-Seq reads**, which differ from standard short-read paired-end sequencing, allowing for more effective V gene discovery in hamster.

---

## `predicted_genes` Folder

- Contains the **predicted V gene segments** output from IgDiscover.  
- Inputs to this analysis included **Mus musculus Ig/TCR V, D, and J germline sequences** (the same reference sequences used for IgBLAST in *Adams et al. 2025*).  
- The hamster V gene predictions generated in this folder are based on aligning hamster Iso-Seq transcripts against this mouse reference.

---

For more details on the methodology and findings, please refer to *Adams et al. (2025)*.

