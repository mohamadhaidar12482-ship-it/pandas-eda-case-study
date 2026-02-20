# Pandas EDA Case Study

Goal: Perform a clean, reproducible Exploratory Data Analysis (EDA) using Pandas:
- Load data
- Inspect & validate
- Clean missing values / types
- Answer business-style questions with groupby/aggregation
- Produce a short report of insights

## Key Findings (Highlights)
- Peak year for titles added: **2019**
- Peak year for TV shows added: **2020**
- Top country: **United States (3,690 titles)**
- Top category: **International Movies (2,752 titles)**
- Typical movie duration: **median ~98 minutes**

## Project Structure
- data/raw: original dataset (do not edit)
- data/processed: cleaned dataset outputs
- notebooks: analysis notebooks
- src: helper functions (optional-we may use it)
- reports: final charts/screenshots/summary

## Data
- Run the notebook in order from top to bottom. Cleaned output will be saved to data/processed/.
- Source: Kaggle — “Netflix Movies and TV Shows” (shivamb/netflix-shows)
- File: `data/raw/netflix_titles.csv`
- License: CC0 (Public Domain) (per Kaggle dataset page)

## How to Run
1. Install requirements:
   - `pip install -r requirements.txt`
2. Open the notebook:
   - `jupyter notebook`
3. Run: `notebooks/01_eda_netflix.ipynb`