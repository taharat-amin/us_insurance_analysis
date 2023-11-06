# **U.S Medical Insurance Cost**

## <u>Part 1: Data Reading and Preparation</u>

The `csv` module is imported to read raw data from the `insurance.csv` file using `csv.DictReader()` method. Initially all data are in string format. Therefore, the processed data is added to the `dataset` list by typecasting the variables in the following manner:

<center>

|<center>Variable</center> | <center>Data Type</center> | <center>Variable Type</center> |
|-|-|-|
| `age` | int | Scale |
| `sex` | bool (0 for 'male' and 1 for 'female') | Nominal |
| `bmi` | float | Ratio |
| `children` | int | Ordinal |
| `smoker` | bool (0 for 'no' and 1 for 'yes') | Nominal |
| `region` | int (1 for 'northeast', 2 for 'northwest' , <br>3 for 'southeast', 4 for 'southwest') | Nominal |
| `charges` | float | Ratio |

</center>

Identified the regions uniquely by first separating the `region` column in the `insurance.csv` to `regions.txt` file. Then the following command was executed in terminal to get the unique names of the regions:
```
sort regions.txt | uniq
```
This command gave the unique names of the regions based on which the numeric codes were provided.
