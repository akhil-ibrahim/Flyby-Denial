---
layout: default
title: Examples
nav_order: 3
---

# Pipeline Examples 📊

This section demonstrates the input and output capabilities of the Flyby-Denial pipeline, specifically focused on protein sequence analysis using sample data from the Luque Lab.

## 1. Sample Datasets
To test the pipeline, you can use the sample files already provided in our repository. These include short peptide sequences and metabolic hormones used for verification:

* 📄 [Browse Example FASTA Files](https://github.com/luquelab/Flyby-Denial/tree/main/examples)
* 📄 [Browse Example Metadata/CSV](https://github.com/luquelab/Flyby-Denial/tree/main/examples)

## 2. Input Data Sources
The pipeline is designed to handle protein sequences from three primary sources:
* **FASTA Upload:** Users can upload standard `.fasta` or `.faa` files.
* **Manual Input:** Raw amino acid sequences can be pasted directly into the notebook.
* **NCBI Integration:** Direct fetching of protein sequences from the NCBI database using `Biopython.Entrez`.

**Example Input Format:**
> `>NP_000468.1 albumin [Homo sapiens]`
> `MKWVTFISLLFLFSSAYSRGVFRRDAHKSEVAHRFKDLGEENFKALVLIAFAQYLQQCPFEDHVKLVNEV...`

## 3. Physicochemical Analysis
Using the `ProtParam` module, the pipeline automatically calculates a profile for each protein, including:
* **Molecular Weight:** Measured in Daltons.
* **Isoelectric Point (pI):** Calculating the pH at which the protein carries no net charge.
* **Amino Acid Composition:** A percentage-based breakdown of the primary sequence.

## 4. Comparative Clustering (Output)
The primary output of the Flyby-Denial pipeline is a series of **Hierarchical Clustering Dendrograms**. These visualize how different proteins relate based on:

1. **Physicochemical Distances:** Clustering based on the similarity of physical properties (e.g., comparing Albumin vs. Myoglobin).
2. **Sequence Similarity:** Clustering based on global alignment scores using the **BLOSUM62** substitution matrix.



---
*Please ensure that any uploaded files are placed in the `/examples` folder to maintain repository structure.*
