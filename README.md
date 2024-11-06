# STEEL EC

## Project Overview
This is an assignment completed for the Advanced Machine Learning programe at Refactory (U) to create a "basic" Machine Learning and an "Advanced" Neural Networks prediction on a set of data. We chose this data from a steel mill in South Korea, and performed Exploratory Data Analysis (including visualizations), then created a logistic regression classification model, and a keras classification model.

### Participation
The participants are Emma Odeke and Jonathan Kateega

### Data Preprocessing
We used onehot encoder for categorical features and standard scalar for numerical features. I think we also used labelencoder somewhere, perhaps in the keras classifier.

### Model Tuning
The logistic regression model is tuned

### Classes
The data is imbalanced, one of the classes is over represented. We accounted for this in the tuned logistic regression model and in the keras model, but we could explore more ways to mitigate this; example, in the train-test split.

## Getting started
### Clone the repository

```
git clone https://github.com/eMoD256/steelEC.git
```

### Install dependencies

```
pip install -r requirements.txt
```

## Model performance

### Logistic regression model
![Confusion matrix for the logistic regression model (before tuning)](files/plots/LR_confusion%20matrix.png)

### Logistic regression model (tuned)
![Confusion matrix for the logistic regression model (after tuning)](files/plots/LR_tuned_confusion%20matrix.png)

### Keras model
![Confusion matrix for the keras model](files/plots/keras_confusion%20matrix.png)
