# Sentiment-Classification
Sentiment Classification of IMDb Movie Reviews in Keras
## Getting Started:
- Use Google Colab for running the notebooks after uploading the dataset on colab session

## Description
- We used glove 200D data for word embeddings and WordCloud visualization to analyze the data
- The model architecture which gave the best results consists of an Embedding Layer, Bidirectional LSTM layer with two Dense layers and one Dropout Layer
- After Hyperparameter Tuning, the best accuracies achieved were **Training Accuracy - 87.45% & Validation Accuracy - 85.24%**

## Notebooks Descriptions:
- `Sentiment_Class_fication_of_IMDb_Movie_Reviews.ipynb`: Single Bi-LSTM layer with no Flatten Layer and Batch Normalization
- `Sentiment_Class_fication_of_IMDb_Movie_Reviews_v2.ipynb`: Double Bi-LSTM layers with Flatten Layer and Batch Normalization with momentum = 0.9
- `Sentiment_Class_fication_of_IMDb_Movie_Reviews_v3.ipynb`: Double Uni-LSTM layers with Flatten Layer and Batch Normalization with momentum = 0.9
- `Sentiment_Class_fication_of_IMDb_Movie_Reviews_v4.ipynb`: Double Bi-LSTM layers with Flatten Layer and Batch Normalization with momentum = 0.999
