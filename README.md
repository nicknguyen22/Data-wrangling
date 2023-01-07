# Data-wrangling
Data wrangling with R and Julia 

This small project use both R and Julia for Data Wrangling. Therefore, the code have been separated into two Jupyter notebooks, one using Julia and the other using R.
DW_Julia.ipynb
DR_R.ipynb

1. Copy those two files into the same folder, then first run the Julia notebook. This notebook will create a temporary file named:
CAS.csv

2. Afterthat,let run the R notebook, which will download a temporary population file: population.xlsx
• It then creates an SQLite database named: CAS.db
• and removes two temporary files: CAS.csv, population.xlsx

The CAS.db is the data that we have produced.
