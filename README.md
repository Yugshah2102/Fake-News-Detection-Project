# Project Overview
Fake news has become a significant issue in today's digital age, where information spreads rapidly through various online platforms. This project leverages machine learning algorithms to automatically determine the authenticity of news articles, providing a valuable tool to combat misinformation.

# Dataset
We have used a labelled dataset containing news articles along with their corresponding labels (true or false). The dataset is divided into two classes:

True: Genuine news articles
False: Fake or fabricated news articles
System Requirements
Hardware :

4GB RAM
i3 Processor
500MB free space
Software :

Anaconda
Python
Dependencies
Before running the code, make sure you have the following libraries and packages installed:

Python 3
Scikit-learn
Pandas
Numpy
Seaborn
Matplotlib
Regular Expression
You can install these dependencies using pip:

pip install pandas 
pip install numpy
pip install matplotlib
pip install sklearn
pip install seaborn 
pip install re 
Usage
Clone this repository to your local machine:
git clone https://github.com/kapilsinghnegi/Fake-News-Detection.git
Navigate to the project directory:
cd fake-news-detection
Execute the Jupyter Notebook or Python scripts associated with each classifier to train and test the models. For example:
python random_forest_classifier.py
The code will produce evaluation metrics and provide a prediction for whether the given news is true or false based on the trained model.
Results
We evaluated each classifier's performance using metrics such as accuracy, precision, recall, and F1 score. The results are documented in the project files.

Model Deployment
Once you are satisfied with the performance of a particular classifier, you can deploy it in a real-world application or integrate it into a larger system for automatic fake news detection.
