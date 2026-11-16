# DWBDA Assignments

**Student:** Somya Bharti  
**Registration Number:** 202400480  
**Subject:** DWBDA

## Contents

- `DWBDA_Assignments.ipynb` — all three assignments in separate notebook cells.
- `requirements.txt` — Python dependencies.
- `.gitignore` — files ignored by Git.
- `data/grocery_transactions.csv` — 350 eco-refill transactions, with 300+ rows.
- `data/previous_semester_results.csv` — 360 student records across six subjects.
- `data/sample_sales_data.csv` — 750 specialty craft and hobby sales records.

## Dataset themes

### Assignment 1 — Market Basket Analysis
Eco-friendly household and refill-store products. The file contains 350 transactions and 20 product types.

### Assignment 2 — MapReduce
360 student records with grades S, A, B, C, D, E, F across:
- Computer Networks
- Machine Learning
- DWBDA
- QALR
- Cyber Security
- IoT

### Assignment 3 — Spark
750 sales records across uncommon craft and hobby product lines. The Spark task groups by `PRODUCTLINE` and sums `QUANTITYORDERED`.

## How to run

```bash
python -m venv .venv
pip install -r requirements.txt
jupyter notebook
```

Open `DWBDA_Assignments.ipynb` and run the cells from top to bottom.

## Important dataset provenance note

The included CSV files are structured practice datasets generated for this assignment and are not claimed to be original Kaggle downloads. If your teacher requires strict Kaggle provenance, download the selected Kaggle datasets, replace the corresponding CSV files, and add the Kaggle URL, dataset author, access date, and license before submission.
