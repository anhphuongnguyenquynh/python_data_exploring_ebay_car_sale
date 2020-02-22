# python_data_exploring_ebay_car_sale
This is a guided project from Dataquest using Python for data analysis. This project mainly focuses on using Numpy and Pandas.

# cool things I have learned
# convert camelCase to snake_case
def change_case(text):
    res = [text[0].lower()]
    for c in text[1:]:
        if c in ('ABCDEFGHIJKLMNOPQRSTUVWXYZ'):
            res.append('_')
            res.append(c.lower())
        else:
            res.append(c)
    return ''.join(res)
    
