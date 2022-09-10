# Sentiment Analysis
# Problem Statement
Use the transformer model on the movie reviews dataset. To use explainability tool to analyze the sensitivity such as LIME. Confusion arises due to overlapping words, especially between adjacent classes, try to solve this problem.
# Architecture
* We have used the DistilBert-base-uncased model from the Huggingface to train our model.
* DistilBERT is a transformers model, smaller and faster than BERT, which was pretrained on the same corpus in a self-supervised fashion, using the BERT base model as a teacher.
* This model contains 6 encoder unlike the BERT model which consists of 12 encoders.
* The uncased word means it is case-insensitive
# Result
![image](https://user-images.githubusercontent.com/96630179/189303724-0711d3e4-d11c-4389-afc7-ea85b97d5342.png)
![image](https://user-images.githubusercontent.com/96630179/189495835-eab91e60-4ffc-477d-bd2a-2198fb13b565.png)

