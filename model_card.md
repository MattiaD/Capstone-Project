# Model Card

## Model Description

**Input:** The model takes as input ten ten fetures 4 numerical and 6 categorical. 
these variables represent the characteristics of the customer at the time the loan was granted. 

**Output:** The output is the prediction of the quality/riskiness of the loan defined as positive or negative.

**Model Architecture:** The model uses a random forest optimised using Bayesian optimisation.

## Performance


## Limitations
the model performs very poorly despite grid search and bayesian optimisation. 
Its use is only illustrative for academic purposes and has no useful features for real-world implementation.


## Trade-offs
Given the limited number of data and the non-triviality of the problem presented, the model performs very poorly and is not applicable in reality. 
In particular, it performs poorly in predicting negative class, a limitation that makes it highly unsuitable for the banking context for which being able to define the riskiest loans is crucial. 
This underperformance can be justified by undersampling the high-risk class and can be corrected in the future through oversampling techniques.
