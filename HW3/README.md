# DSCI 552 Homework 3

Chen Zhu (GitHub: ChenZhu50)

## Contents

- `notebook/Zhu_Chen_HW3.ipynb` — the homework notebook (executed, with outputs saved).
- `data/AReM/` — the 88 AReM recordings from the course data folder (unchanged).
- `requirements.txt` — Python packages used.

## How to run

Tested with Python 3.12.3. From the course repository root:

```
cd HW3
pip install -r requirements.txt
jupyter notebook
```

Open `notebook/Zhu_Chen_HW3.ipynb` and run all cells. The notebook reads data from `../data/AReM` using a relative path.

The submitted notebook includes all six code cells executed in order, with saved outputs for the 88 recordings, the 69/19 train/test split, the feature table, the bootstrap confidence intervals, and the feature-selection plots.

## Data

Palumbo, F., Gallicchio, C., Pucci, R., & Micheli, A. (2016). Activity Recognition system based on Multisensor data fusion (AReM). UCI Machine Learning Repository. https://doi.org/10.24432/C5SS33 (CC BY 4.0).
