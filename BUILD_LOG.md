# Building Log 

## 2026/10/08 -- Project Set up
- Exported Trading 212 history (two CSVs) and put them in data/raw/
- Created the virtual environment and installed pandas, numpy, matplotlib, yfinance, jupyter
- Saved the libraries to requirements.txt
- Created notebooks/, README.md, BUILD_LOG.md, .gitignore
- Wrote .gitignore so the raw data and .venv never go to GitHub
- Created the first notebook and ran the imports test (pandas 2.3.3)

## 2026/10/09 -- README
- I Wrote the README document: Context, tools used, data, status
- Fixed any spelling and phrasing over several drafts  
- Pushed the project to Github (first commit)


## Git routine
- git status
- git add .
- git commit -m "Describe what you did"
- git push.

## 2026/10/15 -- Loaded and checked the data 
- Loaded both CSVs and combined them, giving 2959 rows
- Checked missing values with isna().sum() 
- .isna() = changes the values in the table to boolean values, it gives true if NULL and false if has value. It's basically asking "Is it empty"
- .sum() is to add up each column 

