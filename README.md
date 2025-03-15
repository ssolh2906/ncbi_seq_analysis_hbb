# NCBI Sequence Analysis 🧬

This project is a **beginner-friendly practice exercise** for learning how to retrieve and analyze gene sequences using **NCBI Entrez API** and **Biopython**. It provides a hands-on experience in handling biological sequence data, making it ideal for those new to bioinformatics.

By following the included Jupyter Notebook, users can **fetch genetic sequences, analyze nucleotide composition, and visualize results.**

## 📌 What This Project Covers

- ✅ **Retrieving a gene sequence** from NCBI Entrez API
- ✅ **Computing GC content** of the sequence
- ✅ **Counting nucleotide frequency** (A, T, G, C)
- ✅ **Saving results in FASTA and CSV formats**
- ✅ **Generating a nucleotide frequency bar chart**

## 📂 Project Structure

```
📁 ncbi-seq-analysis  
 ├── 📝 `ncbi_sequence_analysis.ipynb`  *(Jupyter Notebook for interactive execution)*  
 ├── 🐍 `ncbi_sequence_analysis.py`  *(Python script for running in the terminal)*  
 ├── 📄 `base_counts.csv`  *(CSV file with nucleotide frequency data)*  
 ├── 🎨 `nucleotide_frequency.png`  *(Bar chart visualization of nucleotide composition)*  
 ├── 🧬 `hbb_gene.fasta`  *(FASTA file of the retrieved gene sequence)*  
 ├── 📄 `README.md`  *(Project documentation)*  
```

## ⏳ Estimated Time to Complete
This project should take **1 to 3 hours**, depending on familiarity with Python and Jupyter Notebook.

## 🚀 How to Use
Instead of cloning the repository, it is recommended to **manually follow the steps and write the code yourself** to reinforce learning.

### 1️⃣ Set Up the Environment

```bash
conda create -n ncbi_seq_analysis python=3.10 -y
conda activate ncbi_seq_analysis
conda install -c conda-forge biopython pandas requests matplotlib -y
```

### 2️⃣ Open Jupyter Notebook
```bash
jupyter lab
```
Create a new notebook and refer to this README while writing and executing each block of code step by step.

### 3️⃣ Running the Python Script (Once Written)
```bash
python ncbi_sequence_analysis.py
```

## 📊 Example Output

```
Gene ID: NM_000518.5
Sequence length: 626 bp
GC Content: 53.66%
Nucleotide frequency:
A: 150 occurrences
T: 130 occurrences
G: 170 occurrences
C: 176 occurrences
Graph saved: nucleotide_frequency.png
```

✅ The **nucleotide composition graph** is also generated:

📌 **Important:** Before running the script, make sure to **replace the email placeholder with your own** in the Entrez API setup.
```python
Entrez.email = "your_email@example.com"  # Replace with your actual email
```

This project is a great hands-on way to practice **bioinformatics and sequence analysis!** 🧬✨

