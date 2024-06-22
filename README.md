# Pandas_matlplotlib_ipl_analysis
This repository contains a basic example of how to perform data analysis and visualization on an IPL (Indian Premier League) matches dataset using Pandas and Matplotlib in a Jupyter Notebook.
# Import the library pandas and matplotlib '
import pandas as pd
import matplotlib.pyplot as mp

# creating variables 

df=pd.read_csv('ipl_24_del.csv')

# 1) Getting total number of matches played in IPL 
distinct_match_ids = df['match_id'].nunique()
print(distinct_match_ids)

# 2)  Getting total balls bowled in ipl valid or non valid 
total_bowls_bowled=len(df)
print(total_bowls_bowled)
