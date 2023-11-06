# **U.S Medical Insurance Cost**

This repository contains analysis of a survey report conducted to gather data regarding the cost of medical insurance in the United States. The data analysis file can be viewed by cloming this repo with the following command:

```git
git clone https://github.com/taharat-amin/us_insurance_analysis.git
```

## Data Description

The dataset contained **1,338** samples which had the following data types

<div align="center">

|<center>Variable</center> | <center>Data Type</center> | <center>Variable Type</center> |
|-|-|-|
| `age` | int | Scale |
| `sex` | bool (0 for 'male' and 1 for 'female') | Nominal |
| `bmi` | float | Ratio |
| `children` | int | Ordinal |
| `smoker` | bool (0 for 'no' and 1 for 'yes') | Nominal |
| `region` | int (1 for 'northeast', 2 for 'northwest' , <br>3 for 'southeast', 4 for 'southwest') | Nominal |
| `charges` | float | Ratio |

</div>

## Frequency Distribution
Frequency distribution shows the distribution of the samples among different groups or ungrouped data.

### 1. Grouped frequency distribution

<div align="center">

<b>Frequency Distribution of Age</b>

<table style="width:100%; text-align:center;">
  <tr>
    <th>Age</th>
    <th>Frequency</th>
    <th>% of Respondents</th>
  </tr>
  <tr>
    <td>18-23</td>
    <td>250</td>
    <td>18.68%</td>
  </tr>
  <tr>
    <td>24-29</td>
    <td>167</td>
    <td>12.48%</td>
  </tr>
  <tr>
    <td>30-35</td>
    <td>157</td>
    <td>11.73%</td>
  </tr>
  <tr>
    <td>36-41</td>
    <td>154</td>
    <td>11.51%</td>
  </tr>
  <tr>
    <td>42-47</td>
    <td>168</td>
    <td>12.56%</td>
  </tr>
  <tr>
    <td>48-53</td>
    <td>172</td>
    <td>12.86%</td>
  </tr>
  <tr>
    <td>54-59</td>
    <td>156</td>
    <td>11.66%</td>
  </tr>
  <tr>
    <td>60-65</td>
    <td>114</td>
    <td>8.52%</td>
  </tr>
</table>

<b>Frequency Distribution of Children</b>

<table style="width:100%; text-align:center;">
  <tr>
    <th>Children</th>
    <th>Frequency</th>
    <th>% of Respondents</th>
  </tr>
  <tr>
    <td>0-1</td>
    <td>898</td>
    <td>67.12%</td>
  </tr>
  <tr>
    <td>2-3</td>
    <td>397</td>
    <td>29.67%</td>
  </tr>
  <tr>
    <td>4-5</td>
    <td>43</td>
    <td>3.21%</td>
  </tr>
</table>


</div>

### 2. Ungrouped frequency distribution

<div align="center">

<b> Distribution of Sex </b>
<table style="width:100%; text-align:center;">
<tr>
<th>Sex</th>
<th>Number</th>
<th>% of Respondents</th>
</tr>
<tr>
<td>Male</td>
<td>676</td>
<td>50.52%</td>
</tr>
<tr>
<td>Female</td>
<td>662</td>
<td>49.48%</td>
</tr>
</table>

<b> Distribution of Smoker </b>
<table style="width:100%; text-align:center;">
<tr>
<th>Smoker?</th>
<th>Number</th>
<th>% of Respondents</th>
</tr>
<tr>
<td>Yes</td>
<td>274</td>
<td>20.48%</td>
</tr>
<tr>
<td>No</td>
<td>1,064</td>
<td>79.52%</td>
</tr>
</table>

<b> Regional Distribution </b>
<table style="width:100%; text-align:center;">
<tr>
<th>Region</th>
<th>Number</th>
<th>% of Respondents</th>
</tr>
<tr>
<td>Northeast</td>
<td>324</td>
<td>24.22%</td>
</tr>
<tr>
<td>Northwest</td>
<td>325</td>
<td>24.29%</td>
</tr>
<tr>
<td>Southeast</td>
<td>364</td>
<td>27.20%</td>
</tr>
<tr>
<td>Southwest</td>
<td>325</td>
<td>24.29%</td>
</tr>
</table></div>

## Summary Statistics
<div align="center">

<b> Central Tendency </b>
<table style="width: 70%;">
  <tr>
    <th style="width: 20%;">Statistic</th>
    <th style="width: 20%;">Age</th>
    <th style="width: 20%;">BMI</th>
    <th style="width: 20%;">Children</th>
    <th style="width: 20%;">Charges</th>
  </tr>
  <tr>
    <td>Mean</td>
    <td>39.21</td>
    <td>30.66</td>
    <td>1.09</td>
    <td>13270.42</td>
  </tr>
  <tr>
    <td>Median</td>
    <td>39.0s</td>
    <td>30.4</td>
    <td>1.0</td>
    <td>9388.75</td>
  </tr>
</table>

<b>Quartiles</b>
<table style="width: 40%;">
  <tr>
    <th>Variable</th>
    <th>Q1</th>
    <th>Q2</th>
    <th>Q3</th>
  </tr>
  <tr>
    <td>Age</td>
    <td>27.0</td>
    <td>39.0</td>
    <td>51.0</td>
  </tr>
  <tr>
    <td>BMI</td>
    <td>26.3</td>
    <td>30.4</td>
    <td>34.7</td>
  </tr>
  <tr>
    <td>Children</td>
    <td>0.0</td>
    <td>1.0</td>
    <td>2.0</td>
  </tr>
  <tr>
    <td>Charges</td>
    <td>4742.31</td>
    <td>9388.75</td>
    <td>16717.01</td>
  </tr>
</table>

<b>Measures of Dispersion</b>
<table style="width: 40%;">
  <tr>
    <th>Variable</th>
    <th>Standard Deviation (SD)</th>
    <th>Interquartile Range (QD)</th>
  </tr>
  <tr>
    <td>Age</td>
    <td>14.04</td>
    <td>39.0</td>
  </tr>
  <tr>
    <td>BMI</td>
    <td>6.1</td>
    <td>30.5</td>
  </tr>
  <tr>
    <td>Children</td>
    <td>1.21</td>
    <td>1.0</td>
  </tr>
  <tr>
    <td>Charges</td>
    <td>12105.48</td>
    <td>10729.66</td>
  </tr>
</table>

<b>Measure of Relative Variation</b>
<table style="width: 50%;">
  <tr>
    <th>Variable</th>
    <th>CV (Coefficient of Variation)</th>
    <th>CQD (Coefficient of Quartile Deviation)</th>
  </tr>
  <tr>
    <td>Age</td>
    <td>35.81</td>
    <td>30.77</td>
  </tr>
  <tr>
    <td>BMI</td>
    <td>19.9</td>
    <td>13.77</td>
  </tr>
  <tr>
    <td>Number of Children</td>
    <td>111.01</td>
    <td>100.0</td>
  </tr>
  <tr>
    <td>Insurance Charges (in dollars)</td>
    <td>91.22</td>
    <td>55.8</td>
  </tr>
</table>

<b>Skewness</b>
<table style="width: 50%;">
  <tr>
    <th>Variable</th>
    <th>Skewness</th>
  </tr>
  <tr>
    <td>Age</td>
    <td>0.0</td>
  </tr>
  <tr>
    <td>BMI</td>
    <td>0.02</td>
  </tr>
  <tr>
    <td>Number of Children</td>
    <td>0.0</td>
  </tr>
  <tr>
    <td>Insurance Charges (in dollars)</td>
    <td>0.22</td>
  </tr>
</table>

</div>

## Covariance and Correlation

The most significant part of any analysis, correlation shows the relationship between the independent variables and dependent variable. Since this analysis is not much rigorous, no regression model was developed. Only the individual relationship of independent variables and dependent variable is shown.

As the subject matter of this analysis is regarding the medical insurance cost of in the US, the <u>dependent variable</u> is undoubtedly `charges` and the rest are independent.

Correlation coefficients signify two aspects of the relationship between two variables, which are:

- **Strength of relation**: Correlation coefficients range from -1 to 1. The closer the coefficient to 1 is (considering the absolute value), stronger the relation is.
- **Direction of movement**: As mentioned earlier that the coefficient ranges from -1 to 1, positive value indicates that changes in independent variable will bring changes in similar direction for dependent variable and vice versa.

It is clear that when coefficient is 0 there exists no correlation.

</div align="center">

<b>Covariance</b>
<table style="width: 50%;">
  <tr>
    <th>Independent Variable</th>
    <th>Covariance with Charges</th>
  </tr>
  <tr>
    <td>Age</td>
    <td>50836.78</td>
  </tr>
  <tr>
    <td>Sex</td>
    <td>-346.76</td>
  </tr>
  <tr>
    <td>BMI</td>
    <td>14636.36</td>
  </tr>
  <tr>
    <td>Children</td>
    <td>991.93</td>
  </tr>
  <tr>
    <td>Smoker</td>
    <td>3845.79</td>
  </tr>
  <tr>
    <td>Region</td>
    <td>-83.01</td>
  </tr>
</table>

<b>Pearson Correlation Coefficients</b>

<table style="width: 50%;">
  <tr>
    <th>Variable 1</th>
    <th>Variable 2</th>
    <th>Pearson Coefficient</th>
  </tr>
  <tr>
    <td>Age</td>
    <td>Charges</td>
    <td>0.3</td>
  </tr>
  <tr>
    <td>Sex</td>
    <td>Charges</td>
    <td>-0.06</td>
  </tr>
  <tr>
    <td>BMI</td>
    <td>Charges</td>
    <td>0.2</td>
  </tr>
  <tr>
    <td>Children</td>
    <td>Charges</td>
    <td>0.07</td>
  </tr>
  <tr>
    <td>Smoker</td>
    <td>Charges</td>
    <td>0.79</td>
  </tr>
  <tr>
    <td>Region</td>
    <td>Charges</td>
    <td>-0.01</td>
  </tr>
</table>

</div>

## Analysis and Conclusion

Based on the summary statistics, the variable `children` is most widely dispersed although it is normally distributed as its skewness is 0. `bmi` has the least dispersion and an insignificant skewness, making it the most common factor among all participants who have medical insurance. 

When it comes to correlation with `charges`, the strongest correlation (0.79) goes to `smoker` implying that a smoker is charged higher for medical insurance. This also complies with our basic understanding that a smoker has higher risk of health problems and therefore need to pay higher premium. An insignificant correlation was observed among `sex`, `children`, and `region` with less than 0.1 correlation with dependent variable. This signifies that these three variables does not matter that much when determining insurance charges.

Therefore, the conclusion of this analysis is that the medical insurance charges primarily depend on three factors, a person's `age`, their `bmi`, and whether they are `smoker` or not.