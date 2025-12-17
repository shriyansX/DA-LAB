# Data Analytics Lab (DA) 🚀

[![Made with Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/) [![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/) [![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](#)

Hands-on notebooks for exploring Python-based data analytics: cleaning, visualization, and modeling in a Jupyter-first workflow.

## Highlights ✨
- Jupyter-native workflow for rapid iteration and explanation alongside code.
- Batteries-included stack: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.
- Lightweight setup; no exotic dependencies.
- Windows-friendly commands throughout.

## What’s Inside 📂
- `DA-LAB-1.ipynb` — Lab notebook (run top-to-bottom or cell-by-cell).
- `DA-LAB-2.ipynb` — Lab notebook.
- `DA-LAB-3.ipynb` — Lab notebook.

## Lab Exercise Overview
- **DA-LAB-1**: list indexing/slicing; nested list access; number sign check; even/odd; age check; `for` loops over ranges and collections; `while` loops for countdowns, accumulation, and a sentinel input loop.
- **DA-LAB-2**: input-driven mini-utilities—sum, swap, square/cube, ASCII code, Celsius→Fahrenheit, simple/compound interest, circle area, km→miles, remainder; conditionals (sign, max-of-three, even/odd, leap year, vowel/consonant); loops for tables, even numbers, sums, factorial; `while` for reversing digits and counting digits.
- **DA-LAB-3**: palindrome & Armstrong number checks; Fibonacci series; GCD & LCM; prime number detection (single range & count in range); sum of even/odd digits; perfect number check; pattern printing (stars & numbers); factors of a number; count digits divisible by 3; sum of squares 1..N.

## Quickstart (Windows-friendly) ⚡
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

## Recommended Workflow 🧭
- Run cells top-to-bottom the first time to populate outputs and checkpoints.
- Keep raw data outside the repo (or add paths to `.gitignore`) to avoid committing large files.
- Restart kernel and rerun all cells before sharing to ensure reproducibility.
- Consider duplicating notebooks for experiments (e.g., `DA-LAB-1-play.ipynb`).

## Troubleshooting 🛠️
- Kernel not finding packages: confirm the venv is activated (`.\.venv\Scripts\activate`).
- Slow plots in Jupyter: close heavy figures or use `%matplotlib inline` instead of interactive backends.
- Path issues: use forward slashes in notebook paths (`data/file.csv`) to stay cross-platform.

## Nice-to-Haves 🎯
- Add brief summaries in each notebook about the dataset and objective.
- Pin dependencies to a `requirements.txt` when the stack stabilizes (`pip freeze > requirements.txt`).
- If collaborating, consider enabling Jupyter autosave and Git clean filters for large outputs.
- Add a simple task runner (e.g., `Makefile` or `tasks.ps1`) with shortcuts like `make lab` → start Jupyter Lab.
