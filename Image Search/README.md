# Dataset Description

## Source
The dataset is obtained from the Kaggle competition titled "Image Search". You can find the dataset [here](https://www.kaggle.com/competitions/image-search/data).

## Files
- **train/**: This directory contains the training set.
- **test/**: This directory contains the test set.
- **queries/**: Data used for class reference.
- **sample_submission.csv**: A sample submission file in the correct format.
- **zeroshot_clip.py**: Baseline code used to generate `dot_product.csv` and `cosine_similarity.csv` files. Some adjustment on the threshold can be done to improve the score.

## Result
The model achieved an F1 Macro score of 0.95714 on the evaluation metrics.
