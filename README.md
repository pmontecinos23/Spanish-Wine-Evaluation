# Spanish-Wine-Evaluation
### Author Paul Montecinos

## Business Problem:
Determine the best rated wine, so that we may choose the best way to use our resources to generate more sales.

### Data Source: 
https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset?resource=download

### Analytical Insights:
* Higer ratings in body tend to reslut in higer ratings overall.
  ![Screenshot 2023-04-13 184518](https://user-images.githubusercontent.com/29460152/231906161-2ccd07ce-f1e2-4cbf-9b73-f8a59d956440.png)


* Most common types of wine in the data set are Reds or a version of Reds.
  ![Screenshot 2023-04-13 184620](https://user-images.githubusercontent.com/29460152/231906169-36a889f7-7fee-402d-a3c2-717563052b4d.png)
 
* With the graphs below you can see that the acidity of the wines tends to correlate to higher prices, as well as higher ratings. Knowing this we can market wines with higer acidity and higer bodies to our premium customers.
  ![Screenshot 2023-04-18 225124](https://user-images.githubusercontent.com/29460152/232962604-454a300b-a74b-40c0-aed8-9b8504430655.png)
  
### Metrics for Random Forest Classification w/ GridSearchCV:
Received 0.79 accuracy on the training data.
Received 0.58 accuracy on the testing data.

### Model Justification:
With this data set I would not be able to help solve our business problem.

### Recommendations:
* Obtain more data. Out of 7500 rows 5500 were dropped as duplicate.
* Obtain more features. There are so many more features that describe wine. The more we have, I am sure we would be able to find more correlations.
