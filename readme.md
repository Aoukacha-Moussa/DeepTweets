## Deep Tweets Classification
 This project is a text classification model that uses Natural Language Processing (NLP) techniques to classify tweets.

## Project Structure
 The project consists of the following files:

 1-model.ipynb: This Jupyter notebook contains the Python code for the project. It includes data preprocessing, feature 2.      extraction, model training, and prediction steps.

 2-train.csv: This CSV file contains the training data for the model. Each row represents a tweet with its corresponding label.

 3-test.csv: This CSV file contains the test data for the model. The model's performance is evaluated on this data.

 4-submission.csv: This CSV file contains the model's predictions on the test data.

## How to Run the Project
 Open the model.ipynb file in a Jupyter notebook environment.
 Run all the cells in the notebook from top to bottom.
 Dependencies
 This project requires the following Python libraries:
  pandas
  numpy
  matplotlib
  seaborn
  sklearn
  nltk
## Project Description
    The project starts by importing the necessary Python libraries and loading the training and test data from the train.csv and test.csv files respectively.

    The tweets in the training data are then preprocessed and cleaned. This includes removing special characters, converting text to lowercase, and stemming.

    Next, the TfidfVectorizer from the sklearn library is used to convert the cleaned tweets into a matrix of TF-IDF features.

    The data is then split into training and test sets, and a machine learning model (such as Logistic Regression or SVM) is trained on the training data.

    Finally, the trained model is used to make predictions on the test data, and the predictions are saved in the submission.csv file.


## License
This project is licensed under the MIT License.