## Example Folder

The `example` folder contains two subfolders:
- **Input**
- **Output**
  
---

## Input

Follow these steps as an example input for a test run:

### 1. Upload FASTA File
- Navigate to `Input Data → Option 1: Upload a FASTA file`
- Upload `ALK_mice.faa`
- This will store **3 protein sequences** in the list

### 2. Fetch from NCBI
- Navigate to `Input Data → Option 3: Fetch from NCBI by Organism`
- Set the following parameters:
  - **Organism:** Homo sapiens
  - **Max Proteins:** 100
  - **Filter Description:** NADH
- Click **Apply Filter**

### 3. Select Protein Sequences
- Select and confirm the following entries:
  - `3263820393 - NADH dehydrogenase subunit 6 (mitochondrion)`
  - `3263820392 - NADH dehydrogenase subunit 5 (mitochondrion)`
  - `3263820391 - NADH dehydrogenase subunit 4 (mitochondrion)`

### 4. Final Result
- You should now have a total of **6 protein sequences**:
  - 3 from the uploaded FASTA file
  - 3 from NCBI
- All sequences will be stored in the same list

---

## Output

After running the **Export and Download Results** cell, Google Colab will prompt you to download a `.zip` file containing all input and output files. These can be used as a report, including:

- `input_protein_sequences.fasta`
- `combined_dendrogram.png`
- `physicochemical_dendrogram.png`
- `physicochemical_properties.csv`
- `sequence_similarity_dendrogram.png`
- `sequence_similarity.csv`
