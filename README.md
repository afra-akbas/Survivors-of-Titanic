# Survivors of Titanic🛳

I make a survival prediction of Titanic. The dataset is from [a competition of Kaggle](https://www.kaggle.com/c/titanic).

First of all, there are different types of columns in the dataset. Therefore, I try to get some insight into the columns. Some columns have float type, some have integer type, and others have object type. 

These data types were really helpful for the next step because the next step is data preparation. I prepared data by cleaning the dataset from redundant elements. I determined the empty elements, and then, either I filled it or removed it completely out of the dataset. To decide which one I should choose, I consider various factors such as the number of null elements, or what kind of information that the column has.

With data transformation, I meant the transformation of object data to encoded data. We cannot use object elements to train our model, so I used the Label Encoder. There are also other encoder methods. One of the most popular is OneHotEncoder. You can also check out below.

I used two different classifier methods which are Random Forest Classifier, and Gradient Boosting Classifier. Random Forest algorithm is also not bad, but Gradient Boosting gave a better result than that.

### Procedure
1. Data Preparation
    1. Data cleaning
    2. Data transformation
2. Model & Evaluation
    1. Random Forest Classifier
    2. Gradient Boosting Classifier
3. Submission

#### To learn more about🔍🧩
* Encoding labels: [Label Encoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html) and [One Hot Encoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
* Classifier:  [Random Forest Classifier](https://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees) and [Gradient Boosting Classifier](https://scikit-learn.org/stable/modules/ensemble.html#gradient-tree-boosting)
