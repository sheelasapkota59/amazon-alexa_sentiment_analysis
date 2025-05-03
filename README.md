# amazon-alexa_sentiment_analysis
Amazon Alexa Sentiment Analysis using LSTM

📖 Introduction
This project performs sentiment analysis on Amazon Alexa reviews using a Long Short-Term Memory (LSTM) neural network. The goal is to classify customer reviews as positive or negative based on their ratings, leveraging natural language processing (NLP) techniques to understand user feedback.

🛠️ Installation
To run this project locally, you need Python 3.7+ and the following libraries installed:

bash
pip install pandas numpy tensorflow scikit-learn matplotlib

Alternatively, you can run the notebook on platforms like Google Colab or Kaggle without local setup.
👨🏫 Getting Started

  Load the Dataset:
    The dataset is a TSV file containing Amazon Alexa reviews with ratings and feedback.

  Preprocessing:
        Dropped irrelevant columns (date, variation, feedback).
        Converted ratings into binary sentiment labels (ratings 4-5 as positive, 1-3 as negative).
        Tokenized and padded review texts for LSTM input.

  Model:
        Built a Bidirectional LSTM model with an embedding layer.
        Trained the model on 80% of the data and tested on 20%.

  Evaluation:
        Evaluated model accuracy and loss.
        Visualized training history.

📘 Code Structure
    notebooks/ : Contains Jupyter notebooks for data exploration, preprocessing, and model training.
    data/ : Contains the Amazon Alexa reviews dataset (amazon_alexa.tsv).
    src/ : (Optional) Python scripts for preprocessing and model code.
    README.md : This file.

📊 Results and Evaluation
    Achieved accuracy of approximately 90% on the test set.
    The model effectively distinguishes positive and negative reviews based on textual data.
    Training and validation loss and accuracy plots are included in the notebook.

🔮 Future Work
    Experiment with advanced NLP models like Transformers (BERT, RoBERTa).
    Perform hyperparameter tuning to improve model performance.
    Add more data preprocessing steps such as stopword removal, lemmatization.
    Deploy the model as a web app or API for real-time sentiment analysis.

🙌 Contributing

Contributions and suggestions are welcome! Feel free to open issues or submit pull requests.
📄 License

This project is licensed under the MIT License. The Amazon Alexa dataset is used under its respective terms.
📚 References
    Amazon Alexa Reviews Dataset on Kaggle
    TensorFlow and Keras documentation
    NLP and sentiment analysis tutorials


