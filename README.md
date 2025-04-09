# BERT Sentiment Classifier (IMDB Reviews)

This project uses a fine-tuned bert model to classify imdb movie reviews into positive or negative sentiments.

## About  
- implemented using huggingface transformers and pytorch  
- trained on a small subset of the imdb dataset due to hardware limitations  
- includes custom dataset class, data loading, training, evaluation, and prediction  
- accuracy is not the main focus, the goal was to learn the full nlp pipeline  

## What i learned  
- how to tokenize text using pretrained bert tokenizer  
- building custom pytorch datasets and dataloaders  
- training a transformer model with optimizer and loss  
- making predictions from raw text input  
- using git and github to manage and upload the project  

## How to use  
example to run prediction:

```python
prediction(model, "The movie was awesome!", tokenizer)
# returns: "Positive"
NOTE
This model was trained on a small sample size and is not meant for real-world usage.
The purpose of this project is only to practice and understand the nlp workflow.
