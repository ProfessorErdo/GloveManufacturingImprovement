# Glove Manufacturing Improvement
The glove manufacturer experiences a disqualification rate around 3%. The disqualification is defined as the absolute weight difference (real weight - required weight) larger than 10% of the required weight.

The data set includes the manufacturing data from 2021.01 to 2022.03. I will try to analyze the data using decision tree method.

The data were processed through ETL and then analyzed with a decision tree classifier model.

In short summary, the take-home message are:

1. The **weight change** has a determinant impact on the disqualification.
2. A **negative weight change more than 0.2** leads to a dramastic increase in disqualification ratio.
