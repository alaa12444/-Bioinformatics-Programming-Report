
# 🧬 Bioinformatics Programming Assignment

This project implements a complete bioinformatics pipeline including:

- FASTA sequence parsing
- FASTQ quality control
- Read filtering and trimming
- Gene expression missing value imputation

---

## 📂 Dataset
- sample_sequences.fasta
- sample_reads.fastq
- expression_matrix.csv

---

## ⚙️ Tools Used
- Python
- Biopython
- Pandas
- NumPy
- Scikit-learn

---

## 🚀 Pipeline Steps

### 1. FASTA Parsing
- Sequence ID extraction
- Length calculation
- GC content computation
- First 20 bases extraction

### 2. FASTQ Analysis
- Read length statistics
- Phred quality score analysis

### 3. Quality Control
- Filtering low quality reads
- Trimming 3' end low quality bases

### 4. Expression Data Processing
- Missing value detection
- KNN imputation

---

## 📊 Outputs
- fasta_summary.csv
- expression_matrix_imputed.csv

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
