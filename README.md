# KPI-s-Comparator-
Python script for comparing KPIs pre-post a given date.
- It can remove outlier peaks (temporary peaks) using peak detection by sorting and averaging method.
- It can detect whether the KPI colums provided in the csv file is a Success rate (SR) or Drop rate (DR) KPI for adaptive comparison.
- Input is CSV file with following sequence: 

![image](https://user-images.githubusercontent.com/103688787/208787916-aa42ab52-d2ee-45e2-a7a2-c720f74b2eab.png)

- Output is the percentages of improvment or degradation and final decision whether KPIs are acceptable or not:

![image](https://user-images.githubusercontent.com/103688787/208787873-88346b84-3403-4541-acbc-d0d78fc07215.png)

