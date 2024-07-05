**Sentiment Analysis of Comments Using Machine Learning and NLP**


**Introduction**
This project aims to recognize comments as positive or negative using Machine Learning and Natural Language Processing (NLP). The project integrates the Kaggle API to directly interact with a dataset consisting of 16 million data rows.

**Prerequisites**
Python 3.x
Pandas
Numpy
Scikit-learn
TfidfVectorizer
Pickle
Kaggle API

**Installation**
Clone the repository:
git clone https://github.com/DISHA2004/Twitter-Sentiment-Analysis-.git



**Model Training and Testing**
The machine learning model is trained and tested on 16 million data rows by converting the comments to numeric form using TfidfVectorizer. The model employs Linear Regression Classification.


**Results**
This machine learning model has achieved an accuracy of 77.8%.It return 0 for negative comment and 1 for positive comment.

**Saving and Reusing the Model**
The use of the pickle library is demonstrated in the code file to show how the model can be saved and reused as needed.

python
Copy code

import pickle

# Save the model
with open('model.pkl', 'wb') as file:
    pickle.dump(model, file)

# Load the model
with open('model.pkl', 'rb') as file:
    loaded_model = pickle.load(file)


Contributors
Thanks to GFG for helping with this project.
