# Predicting-Tags-For-Stackoverflow

Suggest the tags based on the content that was there in the question posted on Stackoverflow.

![Screenshot (83)](https://user-images.githubusercontent.com/48092244/64816598-9bc28180-d5c5-11e9-945c-ed10d04fb339.png)

## Procedure :

1] We are modeling with less data points (0.5M data points) and more weight is given to the title.<br>
2] We are limiting our tags to 500 only.<br>
3] Due to the above steps we are reducing the time to train the model.<br>
4] If we want to train the whole data we need high computational resource.<br>
5] With  500 tags we are covering  90.956 % of questions.<br>
6] When we apply OneVsRest Logistic regression on BOW we get macro F1 score as 0.3338.<br>
7] Tfidf performs well than BOW on this dataset.
