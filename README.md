# AG News Classification Dataset solution using Bidirectional-LSTM and fine-tuned Bert transformer

Link to the dataset - https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset

## Bidirectional-LSTM-based model results
1. train_loss = 0.2119
2. train_accuracy - 0.9337
3. test_loss - 0.88
4. test_accuracy - 0.70

### Classification report
                  precision    recall  f1-score   support

               0       0.78      0.88      0.83      1900
               1       0.87      0.83      0.85      1900
               2       0.95      0.20      0.33      1900
               3       0.52      0.90      0.66      1900

        accuracy                           0.70      7600
       macro avg       0.78      0.70      0.67      7600
    weighted avg       0.78      0.70      0.67      7600

### Confusion matrix
![image](https://github.com/chit38/ag_news_classification/assets/47925131/ba142b21-6c3d-4a42-beae-893148b139da)

## fine-tuned Bert transformer results
1. train_loss = 0.40
2. train_accuracy - 0.86
3. test_loss - 0.36
4. test_accuracy - 0.87

### Classification report
                  precision    recall  f1-score   support

               0       0.93      0.83      0.88      1900
               1       0.95      0.96      0.96      1900
               2       0.78      0.88      0.83      1900
               3       0.85      0.83      0.84      1900

        accuracy                           0.87      7600
       macro avg       0.88      0.87      0.87      7600
    weighted avg       0.88      0.87      0.87      7600

### Confusion matrix
![image](https://github.com/chit38/ag_news_classification/assets/47925131/181f25b1-1893-4bd8-9404-c950a4485f13)


    
