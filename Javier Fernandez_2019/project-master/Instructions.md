
# <p align="center"> INSTRUCTIONS</p>

## 1. Main tools and modules used

- pandas
- numpy 
- matplotlib.pyplot

## 2. Required inputs

- In section [2], in the first chunk of code the user will need to enter the working database. The example is based on a corn grain biomass data.
- In section [2], in the second chunk the user can input the name of the columns that refer to the variable and the dates for GDD calculation. Example:
    start_column = 'Flowering' 
    end_column = 'Sampling'
    variable = 'DW_mg'

- In section [3], the user will enter the name of the weather station that will be using for the calculations. When writing the name of the station, the user has to capitalize the first letter of every word and leave only one single space between words (e.g. Ashland Bottoms).

- In section [5], the user could change cardinal temperatures of the calculations, modifying GDD_D or GDD_H functions. 
    By default, values are: tbase=8, Tupp = 40, Topt = 30.


## 3. Project outputs

- The code will export a table with calculated daily and hourly thermal time as a new .csv file in the directory, named 'GDD_calculated.csv'. The file will be exactly as the main database with two new colums for the GDD results.
