# Analysis of *Prosper* Loan Data

## About the dataset
Prosper Loan Data contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This dataset was last updated 03/11/2014. This project is written within **Jupyter Notebooks**

## Installation

```ruby
$ git clone https://github.com/Eddavis92/Prosperanalysis
```

The following libaries are used within this project:
```ruby
import pandas as pd
import seaborn as sb
import matplotlib.pyplot as plt
import numpy as np
%matplotlib inline
```

The **raw data CSV file** from Prosper can be downloaded from the following link:

https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv

A CSV file containing a **variable descriptions** can be found in the repository.

## Analysis Files
This project contains four files (not including this READme):
- `Exploratory Analysis - Data Visualation.ipynb` Exploratory analysis Code
- `Explanatory_Analysis_Presentation.ipynb` Code to produce the slides
- `Explanatory_Analysis_Presentation.slides` Slide presentaion of analysis undertaken
- `Prosper Loan Data - Variable Definitions.csv` Information about the variables used
