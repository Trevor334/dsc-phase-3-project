## Overview
This project focuses on SyriaTel, a telco looking to investigate the reasons as to why their customers are churning. 
The project uses classification models to come up with an algorithm that can be used by SyriaTel to predict whether a customer is likely to churn in order to allocate resources and remedy the issues making the customer consider leaving the firm.

## Data Understanding
The data used for this project is from SyriaTel and contains information about the state, plans, talk minutes and the charges levied on the calls.

## Conclusion
The grid search cross validation produces the model with the highest recall which is the metric chosen for this project since SyriaTel will prefer to have many false positives rather than false negatives which would indicate that a customer is not likely to churn when in reality they are likely to. 

It is more expensive to acquire new customers than to retain the current ones and so SyriaTel would want to reduce the false negatives to as low as possible. The model produced 25 false negatives which was the best of the rest. Therefore this model is recommended in predicting whether a customer is going to churn or not. This would assist Syria in making things right to prevent the customer from churning.


