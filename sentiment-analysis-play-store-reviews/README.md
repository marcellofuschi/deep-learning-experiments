
# Sentiment analysis of a dataset of reviews from Google Play Store

Naive Bayes classification is used as baseline. Then, we fine-tune a pre-trained BERT model on the training set, achieving a not-so-great test accuracy of ~73%

More samples are probably needed, as regularization attempts with higher drop-out rates don't seem to improve the generalization results.

Dataset source: https://www.kaggle.com/datasets/prakharrathi25/google-play-store-reviews