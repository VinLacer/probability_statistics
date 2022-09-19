# probability_statistics
I make this code to simplify a final lesson of probability and statistics of my eletronics engineering course, using pandas and numpy libraries from python.

What it does:

This calculates the basic statistics of a .xlsx file in the same path of the .py and also plot some graphs. This code calculate the ANOVA test too.

So if you want to get the same informations of others .xlsx files of your choise, follow the next steps:

### Change the .xlsx name file

```
dados = pd.read_excel('Basededadostrabalhofinal.xlsx', sheet_name= 2)
```
Between the '' put the .xlsx file name and change the sheet_name to the number of the tab you want to take the data

### Collumns names
```
dados['MCUL03'].str.contains('Masculino').sum()
```

The ``` ['MCUL03'] ``` is the collumn that contains the information abbout public sex. So in this case you can change to search what you want and take the number of repetitions contains in the respective collumn.

### Exemple

To facilitate the understanding of that code i'll make avaible the .xlsx file that i use to take the data, so you can use as a exemple and build your own .xlsx file to use this code.
