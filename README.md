# Pandas Learning 🐼

A collection of Jupyter notebooks documenting my journey learning **Pandas** for data analysis in Python — covering everything from Series basics to grouping, merging, pivoting, and handling missing data, with two real-world datasets used for practice.

## 📓 Notebooks

| Notebook | Description |
|---|---|
| `series.ipynb` | Introduction to the Pandas `Series` object — creating series from lists, arrays, and dictionaries, and using custom index labels. |
| `dataframe.ipynb` | Core concepts of the `DataFrame` — creation, indexing, selection, and manipulation. |
| `basicOperations.ipynb` | Fundamental DataFrame operations: `.shape`, `.columns`, `.info()`, `.describe()`, column-wise math, and applying custom functions with `.apply()`. |
| `groupByAggregation.ipynb` | Using `.groupby()` for single and multi-column grouping, plus aggregation functions (`sum`, `mean`, `median`, `std`, `min`, `max`, `count`) via `.agg()`. |
| `mergingJoiningConcatenation.ipynb` | Combining datasets using `pd.merge()`, `.join()`, and `pd.concat()`. |
| `missingData.ipynb` | Detecting and handling missing values — `.isnull()`, `.dropna()`, `.fillna()`, and related strategies. |
| `pivotTable.ipynb` | Building pivot tables with `.pivot_table()` for summarizing and reshaping data. |
| `featureExtraction.ipynb` | Feature engineering and extraction techniques applied to a real dataset (uses `anime.csv`). |
| `countries.ipynb` | End-to-end data exploration and analysis practice using `Countries.csv`. |

## 📊 Datasets

| File | Description |
|---|---|
| `anime.csv` | Anime dataset used for practicing feature extraction and data cleaning. |
| `Countries.csv` | Countries dataset used for exploratory data analysis practice. |

## 🛠️ Tools

- Python 3.13
- pandas
- numpy
- Jupyter Notebook

## 🎯 Purpose

This repo is a personal learning log — each notebook builds on core Pandas skills through small, focused examples so I can reference them later and track my progress.
