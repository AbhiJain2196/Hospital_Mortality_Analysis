
# Hospital_Mortality_Analysis
The aim of the project is to predict the outcome of the person based on the data viz. heart rate, age, BMI ,etc. 


## Screenshots

People above age 60 are more likely to get atrialfibrillation than their younger counterparts

![App Screenshot](/newplot.png)

More number of renal failure has occurred when BMI is in the range of 25-30, also the person is more likely to have diabetes if he / she is falling in this range

![App Screenshot](/newplot1.png)

## Results
<br>
1. LogisticRegression

|           |precision|recall|f1-score|support|
|-----------|---------|------|--------|-------|
|    0.0    |   0.85  | 0.99 |  0.91  |   198 |
|    1.0    |   0.67  | 0.05 |  0.10  |   38  | 
|accuracy   |         |      |  0.84  |   236 |
|   macro avg|  0.76  | 0.52 |  0.51  |   236 |
|weighted avg|  0.82  | 0.84 |  0.78  |   236 |

<br>
2. KNearestNeighbor Algorithm

|           |precision|recall|f1-score|support|
|-----------|---------|------|--------|-------|
|    0.0    |   0.84  | 0.97 |  0.90  |   198 |
|    1.0    |   0.14  | 0.03 |  0.04  |   38  | 
|accuracy   |         |      |  0.82  |   236 |
|   macro avg|  0.49  | 0.50 |  0.47  |   236 |
|weighted avg|  0.73  | 0.82 |  0.76  |   236 |  