# Text Classification 

## Dataset

There are many datasets available freely on the web to perform text classification. The dataset that was used is the Cornell sentiment analysis dataset.

Link: [http://www.cs.cornell.edu/people/pabo/movie-review-data/ ]

In this page you will be able to find a lot of datasets and the one that was used is "polarity_dataset_v2.0" which was introduced in Pang/Lee ACL 2004.

This dataset contains 1000 positive and 1000 negative reviews.

## Implementation

The corpus was created by using regular expression formatting and was converted into Bag-Of-Words(BOW) model. This was converted into a TF-IDF model.
The corpus was split into train and test data and several models were trained and were tested.

## Results

Accuracy - 

**SVM** - 0.84
*Logistic Regression* - **0.87**
**Random Forest** - 0.84