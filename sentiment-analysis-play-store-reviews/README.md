# Sentiment analysis of reviews from Google Play Store

Naive Bayes classification is used as baseline. Then, a pre-trained BERT model is fine-tuned on the training set, achieving a test accuracy of ~73%, which is only slightly higher than the basline. More samples are probably needed, as regularization attempts with higher drop-out rates don't seem to improve the generalization results.

Dataset source: https://www.kaggle.com/datasets/prakharrathi25/google-play-store-reviews
