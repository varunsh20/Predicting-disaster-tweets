# Predicting-disaster-tweets

This repository is about predicting which Tweets are about real disasters and which ones are not.

It is a kaggle project. The link to the kaggle competition is https://www.kaggle.com/c/nlp-getting-started.

Different models like 'Logistic regression', 'mutlinomial naive bayes','gaussian naive bayes' and 'random forest classifier' is used to predict whether a given tweet is about a disaster or not.

Out of all the models logistic regression performs best on both training and validation data.

## Performance of different models:

### Logistic regression:

Results on training data:

- Accuracy = 0.9919309438919122
- Precision = 0.9919489523469399
- Recall = 0.9919309438919122

Results on validation data:

- Accuracy = 0.8209281961471103
- Precision = 0.8230780206003571
- Recall = 0.8209281961471103

Confusion matrix:

![lr1](https://user-images.githubusercontent.com/62187533/121905809-2494c100-cd48-11eb-95d1-be132ef3b2a9.png)

### Multinomial naive bayes

Results on training data:

Accuracy = 0.9742916119346969
Precision = 0.9743125441815697
Recall = 0.9742916119346969

Results on validation data:

Accuracy = 0.7985989492119089
Precision = 0.7986622274084477
Recall = 0.7985989492119089

Confusion matrix:

![mnb](https://user-images.githubusercontent.com/62187533/121906163-763d4b80-cd48-11eb-8e70-3d9700e0b3ed.png)

### Gaussian naive bayes

Results on training data:

Accuracy = 0.9742916119346969
Precision = 0.9743125441815697
Recall = 0.9742916119346969

Results on validation data:

Accuracy = 0.7985989492119089
Precision = 0.7986622274084477
Recall = 0.7985989492119089

Confusion matrix:

![gnb](https://user-images.githubusercontent.com/62187533/121906137-71789780-cd48-11eb-8d6e-09daf9b8dae3.png)

### Random forest classifier

Results on training data:

Accuracy = 0.9968099080502909
Precision = 0.9968098241072487
Recall = 0.9968099080502909

Results on validation data:

Accuracy = 0.7889667250437828
Precision = 0.8144449683416408
Recall = 0.7889667250437828

Confusion matrix

![rfc](https://user-images.githubusercontent.com/62187533/121906179-7b01ff80-cd48-11eb-9044-7162fca9c24e.png)

