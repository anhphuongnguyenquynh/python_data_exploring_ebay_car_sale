# Exploring Ebay Car Sales
Using Python for Data Analysis
This is a guided project from Dataquest using Python for data analysis. This project mainly focuses on using Numpy and Pandas.
Download dataset from: https://www.kaggle.com/orgesleka/used-cars-database/data

cool things I have learned
# convert camelCase to snake_case
def change_case(text):
    res = text(0).lower()
    for c in text[1:]:
        if c in ('ABCDEFGHIJKLMNOPQRSTUVWXYZ'):
            res.append('_')
            res.append(c.lower())
        else:
            res.append(c)
     return ''.join(res)
    
