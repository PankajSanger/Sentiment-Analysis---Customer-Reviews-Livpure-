Sentiment Analysis - Customer Reviews (Livpure)
This project aims to perform sentiment analysis on customer reviews of Livpure products. The goal is to classify the sentiment of the reviews as positive or negative using deep learning techniques.

Getting Started
To get started with the project, follow the steps below:

Prerequisites
Ensure you have the following dependencies installed:

Python 3.x
pandas
numpy
nltk
textblob
spacy
tensorflow
matplotlib
Install the required Python packages using the following command:

bash
Copy code
pip install pandas numpy nltk textblob spacy tensorflow matplotlib
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/livpure-reviews-sentiment-analysis.git
Change directory to the project folder:
bash
Copy code
cd livpure-reviews-sentiment-analysis
Run the Jupyter notebook or Python script to execute the sentiment analysis.
Data Import and Preprocessing
Import the reviews data from the provided CSV file using pandas.
Handle missing values in the dataset.
Perform text preprocessing tasks including converting text to lowercase, removing punctuation, normalizing text, treating chat words, spelling correction, removing stop words, lemmatization, and tokenization.
Model Building
Utilize LSTM (Long Short-Term Memory) neural network architecture for sentiment classification.
Tokenize the preprocessed text data and pad sequences to ensure uniform input length.
Split the data into training and testing sets.
Build the LSTM model using TensorFlow's Keras API.
Compile the model with appropriate loss function and optimizer.
Train the model on the training data and validate it on a subset of the training data.
Visualize the training and validation accuracy and loss curves using matplotlib.
Results
The trained LSTM model achieves a certain accuracy and loss on the validation set, which indicates its performance in sentiment classification.

Contributors
Pankaj Sanger

Acknowledgments
This project utilizes various natural language processing (NLP) techniques.
Special thanks to the developers of the libraries and frameworks used in this project.
