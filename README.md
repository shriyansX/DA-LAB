# Data Analytics Lab (DA)

Hands-on notebooks for exploring Python-based data analytics: cleaning, visualization, and modeling in a Jupyter-first workflow.

## Highlights
- Jupyter-native workflow for rapid iteration and explanation alongside code.
- Batteries-included stack: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.
- Lightweight setup; no exotic dependencies.

## What’s Inside
- `DA-LAB-1.ipynb` — Lab notebook (run top-to-bottom or cell-by-cell).
- `DA-LAB-2.ipynb` — Lab notebook.
- `DA-LAB-3.ipynb` — Lab notebook.

## Quickstart (Windows-friendly)
1) **Requirements**: Python 3.11+, Git.

2) **Create a virtual environment** (recommended):
```powershell
cd "c:\Users\shriy\Desktop\DA LAB"
python -m venv .venv
.\.venv\Scripts\activate
```

3) **Install the usual data stack**:
```powershell
pip install --upgrade pip
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

4) **Launch notebooks**:
```powershell
jupyter lab
# or
jupyter notebook
```

## Recommended Workflow
- Run cells top-to-bottom the first time to populate outputs and checkpoints.
- Keep raw data outside the repo (or add paths to `.gitignore`) to avoid committing large files.
- Restart kernel and rerun all cells before sharing to ensure reproducibility.
- Consider duplicating notebooks for experiments (e.g., `DA-LAB-1-play.ipynb`).

## Troubleshooting
- Kernel not finding packages: confirm the venv is activated (`.\.venv\Scripts\activate`).
- Slow plots in Jupyter: close heavy figures or use `%matplotlib inline` instead of interactive backends.
- Path issues: use forward slashes in notebook paths (`data/file.csv`) to stay cross-platform.

## Next Steps
- Add brief summaries in each notebook about the dataset and objective.
- Pin dependencies to a `requirements.txt` when the stack stabilizes.
- If collaborating, consider enabling Jupyter autosave and Git clean filters for large outputs.
