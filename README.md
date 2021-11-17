## Context
Data was created as a part of real-world Data Science Project in effort to predict what investment program to offer to investment bank customer . The bank found very useful to predict the investing program type beforehand and not to try and offer both products to specific customer. The project was held about 12 year ago and most of modern techniques and algorithms weren't available.

## Tasks
### Investment Bank Type Program Prediction

Given data about investment back prgram transactions, let's try to predict the type of a given program.<br>
We will use logistic regression model to make our predictions.

DataSource - __[KAGGLE](https://www.kaggle.com/snassimr/data-for-investing-type-prediction)__

![Investment Banking](/images/Investment-Banking.jpg)

## Content
Data contains of one dataset and provided in csv format. In order to anonymize data we provided the description for group of columns and specific columns that their meaning can be guessed easily.
Input features group description :

- SE1 (Age) , SE2 (Geographic location) - Customer data
- BA1 – BA7 – Banking activity , money equivalent for general activities on customer’s bank account in last year , i.e. sum of payments for loan return
- PE1 – PE15 – Investing history , flag if customer had one of 15 popular investment products/programs in last year
- IA1 – IA3 – Investing activity , counts for different types of operations on investment accounts in last year