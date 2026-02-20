# Netflix Titles — Summary of Insights

## Dataset
- Rows: 8,807
- Columns (raw): 12
- Source file: `data/raw/netflix_titles.csv`
- Cleaned export: `data/processed/netflix_clean.csv`

## Data Quality Notes
- No duplicate rows detected.
- Missing values exist mainly in:
  - `director` (~29.9%)
  - `country` (~9.4%)
  - `cast` (~9.4%)
- `date_added` had a small number of missing values and was parsed to datetime.

## Key Findings
1. **Titles added peaked in 2019** (highest yearly additions).
2. **TV Show additions peaked in 2020** (highest number of TV shows added in a year).
3. **Top countries by titles**:
   - United States leads strongly (3,690 titles).
   - India (1,046) and United Kingdom (806) follow.
4. **Top genres/categories**:
   - International Movies (2,752) is the largest category.
   - Dramas (2,427) and Comedies (1,674) are also dominant.
5. **Duration patterns**:
   - Movies: median ~98 minutes (IQR 87–114), mean ~99.6.
   - TV shows: most titles have **1 season**, then 2 seasons, then 3.

## Notebook
- Main analysis: `notebooks/01_eda_netflix.ipynb`