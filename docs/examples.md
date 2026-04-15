---
layout: default
title: Examples
nav_order: 3
---

# Pipeline Examples 📊

This section demonstrates the input and output capabilities of the Flyby-Denial pipeline, specifically focused on protein sequence analysis.

## 1. Input Data
The pipeline is designed to handle protein sequences from three different sources:
* **FASTA Upload:** Users can upload standard `.fasta` or `.faa` files.
* **Manual Input:** Raw amino acid sequences can be pasted directly into the notebook.
* **NCBI Integration:** Direct fetching of protein sequences from the NCBI database using `Biopython.Entrez`.

**Example Input Sequence:**
> `>User_Input_Protein_1`
> `MVLSPADKTNVKAAWGKVGAHAGEYGAEALERMFLSFPTTKTYFPHFDLSHGSAQVKGHG...`

## 2. Physicochemical Analysis
Using the `ProtParam` module, the pipeline automatically calculates a profile for each protein, including:
* **Molecular Weight:** Measured in Daltons.
* **Isoelectric Point (pI):** Calculating the pH at which the protein carries no net charge.
* **Amino Acid Composition:** A percentage-based breakdown of the primary sequence.

## 3. Comparative Clustering (Output)
The primary output of the Flyby-Denial pipeline is a series of **Hierarchical Clustering Dendrograms**. These provide a visual representation of how different proteins relate to one another based on:
1. **Physicochemical Distances:** Clustering based on the similarity of physical properties.
2. **Sequence Similarity:** Clustering based on global alignment scores using the **BLOSUM62** substitution matrix.

---
*Please refer to the `/examples` folder in the GitHub repository to find sample FASTA and CSV files for testing.*
