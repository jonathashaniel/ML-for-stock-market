# Machine Learn for Stock Markets
This code make some indicators and prices in Brazil stock market to test classifiers (from sklearn and tensor flow) predicting short-term price movement.

### Prediction:
**Will the price will rise more than 3% in the next 4 days?**

### Indicators:
- High Low activator
- Up or down compared to a arithmetic moving average
- stocastic moment
- Trix
- Directional Movement Index
- Last day variation
- 60 days accumulated variation
- Variation in volume of negociations 
- Relative Strength Index

### Classifiers:
- Suport Vector Machine: 
    - SVC kernels:
        - linear (sklearn an tensorflow)
        - gaussian (sklearn an tensorflow)
        - rbf (sklearn)
        - sigmoid (sklearn)
- Neighbors:
    - KNeighborsClassifier (sklearn)
- Naive Bayes:
    - GaussianNB (sklearn)
- Linear model:
    - Stochastic Gradient Descent [SGDClassifier] (sklearn)

 ### Date:03/2019
- Python 3 
- sklearn
- tensorflow
- pandas
- numpy
