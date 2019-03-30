.h5 files are model check points. For each epoch, if the validation accuracy is higher, save the model of this epoch, after the traning complete, load this "best_model" and evaluate model with test set. Ensure avoid overfitting.

The result (based on test accuracy):
1. best_and_fast: 88.410%
2. no_dropout: 88.530%
3. No Z-score (mean-std) normalized:88.030%
4. baseline: 74.200%
