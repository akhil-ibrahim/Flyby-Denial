# 🧬 Protein Analysis Pipeline (Google Colab)

This project is a simple bioinformatics pipeline built in Google Colab for analyzing and comparing protein sequences. It’s designed to be easy to run and modify, especially for students or anyone getting started with protein analysis.

---

## What this does

Given a set of protein sequences, the pipeline will:

- Read in your data (from a FASTA file or by fetching sequences)
- Calculate basic physicochemical properties
- Compare sequences to each other
- Show how the proteins are related using clustering

---

## 1. Input data

There are two ways to get your protein sequences into the notebook:

### Upload a FASTA file
Upload multiple `.fasta` files directly in Colab.

### Fetch sequences
Copy and paste multiple sequences 

---

## 2. Physicochemical properties

For each protein, the pipeline calculates:

- sequence length  
- molecular weight  
- amino acid composition  
- isoelectric point (pI)  
- net charge 

This gives a quick overview of the biochemical characteristics of each sequence.

---

## 3. Sequence similarity

Each protein is compared with every other protein in the dataset:

- pairwise alignments are computed  
- similarity scores are generated  
- results are stored in a table 

This helps identify which proteins are more closely related.

---

## 4. Relationships between proteins

The pipeline groups proteins and visualizes their relationships.

### Outputs:

- **Physicochemical-based relationship**  
  Clustering using features like pI and molecular weight  

- **Sequence similarity-based relationship**  
  Clustering based on alignment-derived distances  

- **Combined relationship**  
  Clustering using both physicochemical properties and sequence similarity  

These are typically shown as dendrograms.

---

## Outputs

The notebook generates:

- tables of physicochemical properties  
- a sequence similarity table  
- clustering visualizations (dendrograms)  

All results are displayed in Colab and can be saved.

---

## How to run

1. Open the notebook in Google Colab  
2. Run the setup cells  
3. Upload your FASTA file or fetch sequences  
4. Run the remaining cells in order  

---

## Notes

- Make sure your input is valid protein FASTA format  
- Larger datasets may take longer to process  
- Results depend on alignment and clustering methods used  

---

## Contributing

Feel free to modify or extend the pipeline.

