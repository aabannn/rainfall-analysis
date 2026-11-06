# rainfall-project-(1901-2015)

Exploratory analysis and a prediction experiment on 115 years of IMD rainfall data for Kerala, using Python, Pandas, SQL (SQLite) and scikit-learn.

## Questions
1. How has Kerala's rainfall changed over 115 years?
2. How much of it falls in the monsoon?
3. Can early-year rainfall and last year's monsoon predict this year's monsoon?

## Data
IMD subdivision rainfall data (Kaggle: "Rainfall in India"), filtered to Kerala: 115 yearly records.

## Cleaning
- No missing values or duplicate years.
- Monthly totals matched ANNUAL within 0.3 mm for every year.

## Key findings
- Wettest decade: 1920s (3188.8 mm/yr). Driest: 1980s (2456.3 mm/yr).
- No steady long-term decline: a dry stretch in the 1970s-80s, then recovery to about 3000 mm in the 1990s.
- 69.1% of annual

## Graphs
<img width="1275" height="701" alt="monthly_rainfall" src="https://github.com/user-attachments/assets/91b16d08-d92a-43d2-ab3c-1f479515d3ff" />
<img width="990" height="749" alt="annual_rainfall" src="https://github.com/user-attachments/assets/424386c0-8a2b-4390-9c12-12bb6aacee13" />
