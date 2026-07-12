# Predicting NFL Draft Position from Combine Performance

CMSC 320 Final Project Tutorial — University of Maryland

**Authors:** Nakul Praveen, Samuel Antonielli, Pratyaksh Mishra, Toby Nwadiaro

**Live tutorial:** https://npraveen465.github.io/

## About

This project explores whether NFL Scouting Combine performance (40-yard dash, vertical jump,
bench press, shuttle run, broad jump, 3-cone drill) can predict where a player gets selected in
the NFL Draft, and how much of that relationship depends on position.

The tutorial covers the full data science pipeline:
- **Data curation** — merging and cleaning combine and draft data from the [NFL Play Statistics Dataset (2004–Present)](https://www.kaggle.com/datasets/toddsteussie/nfl-play-statistics-dataset-2004-to-present) (Kaggle)
- **Exploratory data analysis** — correlation analysis and hypothesis testing on combine metrics vs. draft outcomes
- **Machine learning** — Linear Regression and Random Forest models predicting draft pick number from combine stats and position
- **Visualization** — predicted vs. actual draft pick, feature importance, and error analysis by position
- **Insights and conclusions** — what the results say about how much combine testing actually matters for draft position

## Repository contents

```
CMSC320FinalProject/
├── index.html    # Rendered tutorial (this is what GitHub Pages serves)
└── *.ipynb        # Source Jupyter notebook
```

## Running it yourself

1. Clone this repository.
2. Download `combine.csv` and `draft.csv` from the [Kaggle dataset](https://www.kaggle.com/datasets/toddsteussie/nfl-play-statistics-dataset-2004-to-present) and place them in the `CMSC320FinalProject/` folder.
3. Install dependencies: `pip install pandas numpy matplotlib seaborn scipy scikit-learn`
4. Open and run `CMSC320_NFL_Final_Project.ipynb` in Jupyter.
