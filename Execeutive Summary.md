# Executive Summary
### Apr, 13, 2022

The major key point of data analysis from the PowerCo, Inc and its Churn forecast project.

## The Churn rate
- Churn people represents 10% of data. (n = 14606)
- ~79.42% were consuming between 0 & 50K over 12 months and ~9.72% were between 50K and 100K.
- ~72.16% renewal their contract in the right day, and just ~3.87% pass over one day to renewal.
- ~80.9% of churn people consumed beyond the forecast.
- The highest peak started from whose had ~4 years of contract. The second one was among ~7 years of contract.
- The majority were paying between 0 and 75 suming up net margin and impost.

## The Price
- The average of Price Off Peak Var is $ ~0.1418, the differences between the client's average is 0.42%.
- The average of Price Off Peak Var is $ ~43.16, the differences represents 0.39%.
1. Price Off Peak:
    - The mean churn price was ~49% below the mean price per client ($0.1423), and ~52% of churn people were paying for this Peak Fix.
    - The mean churn price was ~60% above the mean price per client ($42.92), and ~56% of churn people were paying for this Peak Var.
2. Price Peak:
    - The mean churn price was ~79% above the mean price per client ($0.05), and ~55.5% of churn people were paying for this Peak Fix.
    - The mean churn price was ~55% above the mean price per client ($9.46), and ~45.3% of churn people were paying for this Peak Var.

## The Dilleme
- Churn and Non-churns have presented similar pattern over the data.
- Both segmens had an increasing of 1% of consume beyond the expected.
- The churn people came from the average of data.
- The company has ~8% of people with ~4 years of contract and ~10,8 with 7 years. Together they are more than churn rate.
- Even though the difference of prices, the average is the same for both segments.
- ~43% for Price Peak Var and ~60% of current clients are paying $0.00 for Price Peak Fix. Similar rate presented in churn people.


## The Model
Due the similarity of pattern between the segments the best choice was to build a statistical model to detect the slightly trends.
the result was:
- 103 likely churn people from current clients.

## The Recommendation
The data showed that churn people were paying above the mean per client. Even though the churning reason was pointed to price, the machine considered consumption an important feature and as it was not computed, the main factor to build a pattern is non-understandable, however their little trends were statistically applied and 103 current clients showed the same behaviour as churn people.
The solution of applying a discount is a good aproach but as we saw early the price is highly above the estimated value so there are some things to consider before applying a discount:
- More Quality of Service
- Build a relationship with customers
- Priorize customers in specific geo areas - segmentation
- Record consumption behaviour
