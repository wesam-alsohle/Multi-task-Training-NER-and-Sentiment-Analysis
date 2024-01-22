# Multi-task-Training-NER-and-Sentiment-Analysis

MULTI-TASK TRAINING ModeLs WITH  HUGGING FACE Arabic TRANSFORMERS:

1- we work on Real Arabic Hotel Reviews to :

- classify them into good, natural, and bad reviews 

- at the same time, we get the NER for each word.

2- Explore data then Clean it and Analysis the Result.

3- Using Huggingface Arabic Transformers such as Arabert, Marbert, and Qarib.

4- Build and Train a Multi-Task Model then we use it to Predict the test set for every single Task.

5- Evaluate each multitask model with both classification and NER tasks:

model  sentimenet_valid_acc  sentiment_test_acc  ner_test_acc

arabert      0.847211          0.849907              0.732296

marbert      0.845594          0.838789              0.735117

qarib        0.854487          0.843731              0.724035
