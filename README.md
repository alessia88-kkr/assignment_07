## Overview

This assignment demonstrates a complete cloud-based data analysis workflow using AWS. The answer of conceptual questions are in the pdf file attached.

1. **S3**: Store raw and processed data securely.
2. **EC2**: Launch a Ubuntu instance to run Jupyter Notebook.
3. **SSH Port Forwarding**: Securely access Jupyter from local machine.
4. **Python (Pandas, NumPy, Matplotlib, Seaborn packages)**: Generate synthetic data, perform EDA, and create visualizations.

## Dataset

- **File**: `salary_data.py` → generates `salary_job_data.csv`
- **Records**: 200 synthetic employees
- **Columns**:
  - `Employee_ID`
  - `Job_Title` (8 roles)
  - `Salary` (~N(85,000, 20,000) + experience bonus)
  - `Experience_Years` (0–25)
  - `Location` (6 major cities)
  - `Industry` (5 sectors)
  - `Employment_Type` (Full-Time: 70%, Part-Time/Contract: 15% each)
 
