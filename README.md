# probability_statistics
I made this code to simplify a final lesson on probability and statistics in my electronics engineering course, using pandas and NumPy libraries from python.

What it does:
This calculates the basic statistics of a .xlsx file in the same path as the .py and also plots some graphs. This code calculates the ANOVA test too.
So if you want to get the same information of other .xlsx files of your choice, follow the next steps:

### Change the .xlsx name file
```
dados = pd.read_excel('Basededadostrabalhofinal.xlsx', sheet_name= 2)
```
Between the '    ' put the .xlsx file name and change the sheet_name to the number of the tab you want to take the data

### Collumns names
```
dados['MCUL03'].str.contains('Masculino').sum()
```

The ``` ['MCUL03'] ``` is the column that contains information about public sex. So in this case you can change to search what you want and take the number of repetitions contains in the respective column.

### Example:

To facilitate the understanding of that code I'll make available the .xlsx file that I use to take the data, so you can use it as an example and build your .xlsx file to use this code.

You can also open the .ipynb to see the code preview. Maybe it will help you. 

## Examples of statistics that the code gives you:

<img src = "https://user-images.githubusercontent.com/71742380/192061426-e33dd464-2dfb-4962-af6a-43d36d633f6a.png">
