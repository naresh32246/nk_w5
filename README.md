# Will the Customer Accept the Coupon?
In this application, python libraries are imported as numpy as np, pandas as pd, matplotlib.pyplot as plt, seaborn as sns, and plotly.express as px
# Steps to load and validate data
Import the data from in-vehicle-coupon-recommendation.csv
To understand the data frame, data type, statistics, and missing data, I used head(), info(), and describe().
Converting data frame datatypes,Age is a mostly numeric and displayed as a string, so the following logic is applied to convert to int64
Look for null or NaN valuesLook for special characters
Drop column(s) and 'NaN' values
