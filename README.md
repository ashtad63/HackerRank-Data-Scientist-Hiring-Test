# HackerRank Data Scientist Hiring Test: Predict Life Expectancy

Governments, research institutes, and organizations like the United Nations and the World Bank try to \
understand the relationship between the life expectancy of a country or a geographical area and \
socioeconomic factors. Such analysis is valuable in deciding economic and social policies. Can you \
construct a reliable model that predicts the life expectancy of an area (country, region, group of \
countries) using socioeconomic variables and identify how different features influence that?

Every row of the train_data or the test_data represents socioeconomic variables of a geographical \
area. That area could be a country, a group of countries, a region or a big country’s provision.

**Goal:**

For every row in the test data, you must predict the value of the life expectancy. The predictions must \
be saved in a .csv file with the name ‘submission.csv’.

The CSV file must have two columns.
* The first column must be the index of the test set
* The second column must have the predicted value of every corresponding index value.

**Evaluation Metric:**

The metric used for evaluating the performance of the predictive model will be the **mean absolute \
error** of the predictions from the ground truth (the real values of the life expectancy for every row in \
the test set).

***For more information please refer to the PDF file uploaded in this repo.***
