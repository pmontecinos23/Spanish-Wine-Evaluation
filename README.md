# Spanish-Wine-Evaluation
### Author Paul Montecinos

## Business Problem:
Determine the best rated wine, so that we may choose the best way to use our resources to generate more sales.

### Data Source: 
https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset?resource=download

### Analytical Insights:

![Screenshot 2023-04-19 214557](https://user-images.githubusercontent.com/29460152/233245190-7feaaf4c-9d19-4662-b92f-6d45599b1fe4.png)
* The graph above shows the red wines have the largest amount of variance between the body of the wine.
* The sparkling types have a very low level of body to them. This means the weight held on the palate is lighter compared to those with a heavier body.

![Screenshot 2023-04-19 214544](https://user-images.githubusercontent.com/29460152/233245195-38fdd8f4-95e5-488f-8b22-10219d8708b4.png)
* The graph above details the body difference between the 3 wine types.
* Reds are the only wine to have an acidity level of 2 and the whites are the only one to have a level of 1.
* Acidity is basically the tartness of a wine. When the levels are lower, they tend to be more refreshing. You can compare it to drinking a glass of lemonade. The lower the level the more refreshing it is, making you want to take another sip. 

### Metrics for Random Forest Classification w/ GridSearchCV:
Received 0.79 accuracy on the training data.
Received 0.58 accuracy on the testing data.

### Model Justification:
With this data set I would not be able to help solve our business problem.

### Recommendations:
* Obtain more data. Out of 7500 rows 5500 were dropped as duplicate.
* Obtain more features. There are so many more features that describe wine. The more we have, I am sure we would be able to find more correlations.
