# Datasheet Template

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

## Motivation

- For what purpose was the dataset created? 

- This dataset classifies people described by a set of attributes as good or bad credit risks. Comes in two formats (one all numeric). Also comes with a cost matrix

- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?

- The original dataset was created by Prof. Hofmann and contains categorical/symbolic attributes.
- No information are available on who founded the dataset.

 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 

-The instances represent persons granted a loan in Germany with their respective characteristics summarised by the 20 categories provided plus a target feature representing the quality of the loan.

- How many instances of each type are there? 

1000 instances with 20 features representing individuals who have been granted a loan in germany.

- Is there any missing data?
- 
- Yes, distributed as following:

-Checking account features 394 missing values

-Saving accounts feature 183 missing value
- 
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?

- the data, although containing sensitive information such as credit amount, age and employment, have been appropriately anonymised so as to prevent association with the persons to whom they correspond.

## Collection process

- How was the data acquired? 
- If the data is a sample of a larger subset, what was the sampling strategy? 
- Over what time frame was the data collected?

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 

-From the initial dataset, a new dataset was created containing only 10 features considered to be the most relevant. 
-Subsequently, the categorical variables were transformed into numerical variables in order to be able to use them in the algorithm as well as the missing values were filled in. 
-In addition, in order to be able to analyse more in depth during the exploration phase, feature age bins were created to facilitate the reading of certain analyses

- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 

- The rawdata is available as the following link:

- https://archive-beta.ics.uci.edu/dataset/144/statlog+german+credit+data
 
## Uses

- What other tasks could the dataset be used for? 
- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
- Are there tasks for which the dataset should not be used? If so, please provide a description.

## Distribution

- How has the dataset already been distributed? 
- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?  

## Maintenance

- Who maintains the dataset?

