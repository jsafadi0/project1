# project1
project 1 By: Rupal, Jamal & Jaheim

## Datasource website 

https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data (used only Monthly dataset for project 1)

## Pharma Sales Monthly Dataset (sourcefile from : https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data)
## Out of all 4 datasets , we have only taken Pharma Monthly Dataset

## Summary of Dataset:
 This dataset contains selected group of drugs from the dataset (57 drugs) is classified to the following Anatomical Therapeutic Chemical (ATC) Classification System categories:

M01AB - Anti-inflammatory and antirheumatic products, non-steroids, Acetic acid derivatives and related substances
M01AE - Anti-inflammatory and antirheumatic products, non-steroids, Propionic acid derivatives
N02BA - Other analgesics and antipyretics, Salicylic acid and derivatives
N02BE/B - Other analgesics and antipyretics, Pyrazolones and Anilides
N05B - Psycholeptics drugs, Anxiolytic drugs
N05C - Psycholeptics drugs, Hypnotics and sedatives drugs
R03 - Drugs for obstructive airway diseases
R06 - Antihistamines for systemic use

## We are doing Comparison of Total Sale of Drugs from 2014- 2019 per Category 
We are looking at 8 different drug categories sold for the period of 2014- 2019 . 
Drug category like N02BE had variation in sale count but managed to have a high sale count of 7000-almost 14000 count for all 6 years .
As compared to other categories like M01AB, M01AE, N02BA had consitent sale count between 8000- 10000 counts, whereas the sum of R03 and R06 almost had 50 % of difference between the sale count(12000, 6000 respectively) 
as suppose to N05C it barely reached the sale to 1250 for all 6 years .

## We are looking at the ATC categories and sale count for each category through 2014-2019 
Looking at the bar charts for all the 8 drug types, we can see that trend for sales can be further categorized in 4 groups. 
    
    1. Drugs M01AB and M01AE seem to follow a similar sales trend from 2014 - 2019 and can be grouped together.

    2 Similarly, drugs N02BE, R03 and R06 can be put in another group as they have increasing sales trend from 2014 to 2016 followed by decreasing trend with a significant dip in 2017. 

    3. Drug types N05B and N05C have similar trends and can be group together as well. 

    4.Lastly, drug N02BA is in a group by itself with consistent sales from 2014 to 2016 and then constant decline in sales from 2017 onwards


## Highest selling Drug Category ( N02BE)
 We can see that the drug category N02BE is the highest selling drug with sales count of 10,000  in year 2014 to 13000+ in 2016 but then it had a dip in 2017 with sales of almost 7600, thenin 2018 and 2019 it maintained the sale of 11000- 8000 count . Even with all this rise and dip in sales , the drug N02BE was still able to maintain the highest selling drug 

 ## Lowest selling Drug Category ( N05C)
 We can see that the drug category N05C is the lowest selling drug  as over the period of 6 years barely the sale was about 1250 for all 6 years. 
 Even though this drug was not sold as much in terms of count to other ATC categories, it still had maintained a steady sale count for each year. 


## some of helpful links and websites used for help with code 

https://sparkbyexamples.com/pandas/pandas-extract-month-and-year-separately-from-datetime-column/
https://datatofish.com/sum-columns-rows-dataframe/
https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet


## Project Findings:

1- Questions that you found interesting and what motivated you to answer them

## Our questions are:
    1- Different categories for each drug group 
    2 Highest selling drug and its performance 
    3 Lowest selling drug and its performance 
    4 which drug group categories and its sales for all 6 years ( 2014- 2019)
    5- Yearly sales for each category
    6- Finding Mean, median, STd, deviation, Quartiles

What motivated us to answer them was the drive to become better data analysts and practice the concepts we learned in class to achieve that.

2- Where and how you found the data you used to answer these questions

We found the dataset on Kaggle.com. We were looking for a large dataset so we could come up with enough questions to answer. The "Salesmonthly" dataset has the sold monthly quantity for 8 drug groups over a 6-year period, which is a long time. And that's why we found it interesting . Also this web link has additional information about each drug category(https://www.whocc.no/atc/structure_and_principles/)

3- The data exploration and cleanup process (accompanied by your Jupyter notebook)

We started the data exploration process by reading the instructions for the project. The instructions suggested using data from certain fields, and healthcare was one of them. The cleanup process was done by downloading our dataset, importing packages, and deleting duplicate or null values in the dataset.

4- The analysis process (accompanied by your Jupyter notebook)

The analysis process was done by answering the propsal's questions we came up with as a group. We also added data visualization to these questions, which will make it easier for the audience to understand our analysis. We also calculated important things like the mean, median, variance, and standard deviation.

5- Your conclusions, including a numerical summary and visualizations of the summary

Our conclusions and analysis are shown in description and also through visualizations in presentation (Pharmasales_anlysis.ipynb
)





