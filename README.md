# Bangla Product Review Sentiment Analysis
This project, "Bangla Product Review Sentiment Analysis," aims to analyze the sentiment of Bangla product reviews using various machine learning and deep learning techniques. The goal is to provide insights into customer sentiments towards Bangla products, enabling businesses and consumers to make informed decisions.

## Summary
The project begins with an abstract that provides an overview of the project's methodology and results. The introduction section provides a brief background, explains the motivation behind the project, states the objective, and highlights the significance of the problem statement.

The data collection and preprocessing stage involves combining the initial dataset, which consists of Bangla product reviews and sentiment labels provided by three different individuals, using majority voting. The data is then balanced using SMOTE, and word embedding is performed using BERT's multilingual base model to convert the review comments into numerical vectors.

Exploratory data analysis employs PCA (Principal Component Analysis) to visualize the data and identify separations in the dataset. It is discovered that the dataset is not properly separable based on the PCA output.

The model development and evaluation section cover several algorithms, including Decision Tree, Dense Neural Network, Random Forest Classifier, LSTM Model, Bidirectional LSTM, 1D Convolutional Neural Network (CNN), Transformer model, and KNN. Each algorithm is described, along with its working principles, hyperparameter optimization techniques, architecture, training process, and test results.

The experimental results section provides an overview of the results obtained from the different models, including their accuracies. It presents a summary of the outcomes and offers a general overview of the project's experimental findings.

Finally, the conclusion section summarizes the key findings and insights from the project. It highlights the strengths and limitations of the developed models and provides recommendations for future work and improvements.

Overall, the "Bangla Product Review Sentiment Analysis" project offers a comprehensive analysis of sentiment in Bangla product reviews and provides valuable insights for businesses and consumers in understanding customer sentiments towards Bangla products.

## Dependecies
- python
- pandas
- numpy
- scikit-learn
- tensorflow
