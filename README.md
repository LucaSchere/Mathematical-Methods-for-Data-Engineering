# MMDE Course - Bern University of Applied Sciences

A compact collection of data analysis notebooks, raw datasets, and supporting files for exercises and projects.

Short summary:

- `task2` – The notebook cleans the data, performs descriptive statistics and visualizations.

- `task3` – Focus on data preprocessing, and inferential statistical analyses; `openpyxl` is required to read the Excel files.

- `task4` – The notebook demonstrates parameter setup (including seed), vectorized computation with NumPy, and outputs in the form of plots and summary statistics for Monte Carlo simulations.

- `task5` – Covers data preprocessing, feature engineering, and basic classification experiments (e.g., with scikit-learn), including evaluation metrics.

- `Z_project` – Combination of text analysis and tabular data evaluation; `taskC.rmd` is R Markdown for reproducible results, while the notebooks complement it with exploratory scripts.

Quick setup (minimal)
- Python 3.9+ recommended.
- Create virtual env and install commonly used packages:

```bash
python -m venv .venv
.venv\Scripts\activate
pip install pandas numpy matplotlib seaborn scipy statsmodels openpyxl jupyter
```

Usage
- Open notebooks in DataSpell, JupyterLab, or VS Code and run cells sequentially.
- Check relative paths in notebooks (some load files from `data/` or their folder).
