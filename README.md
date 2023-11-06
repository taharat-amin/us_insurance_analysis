# **U.S Medical Insurance Cost**

This repository contains analysis of a survey report conducted to gather data regarding the cost of medical insurance in the United States. The data analysis file can be viewed by cloming this repo with the following command:

```git
git clone https://github.com/taharat-amin/us_insurance_analysis.git
```

## Data Description

The dataset contained **1,338** samples which had the following data types

<div align="center">
<table>
  <tr>
    <th>Variable</th>
    <th>Data Type</th>
    <th>Variable Type</th>
  </tr>
  <tr>
    <td>`age`</td>
    <td>int</td>
    <td>Scale</td>
  </tr>
  <tr>
    <td>`sex`</td>
    <td>bool (0 for 'male' and 1 for 'female')</td>
    <td>Nominal</td>
  </tr>
  <tr>
    <td>`bmi`</td>
    <td>float</td>
    <td>Ratio</td>
  </tr>
  <tr>
    <td>`children`</td>
    <td>int</td>
    <td>Ordinal</td>
  </tr>
  <tr>
    <td>`smoker`</td>
    <td>bool (0 for 'no' and 1 for 'yes')</td>
    <td>Nominal</td>
  </tr>
  <tr>
    <td>`region`</td>
    <td>int (1 for 'northeast', 2 for 'northwest',<br>3 for 'southeast', 4 for 'southwest')</td>
    <td>Nominal</td>
  </tr>
  <tr>
    <td>`charges`</td>
    <td>float</td>
    <td>Ratio</td>
  </tr>
</table>
</div>

## Frequency Distributio18ns
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

### 2. Ungrouped Frequency Distribution

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
</table>