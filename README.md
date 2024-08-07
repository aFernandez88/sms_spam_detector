# sms_spam_detector
SMS Text Classification with Linear Support Vector Classification (SVC)
This project aims to refactor an existing SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, a Gradio app will be developed to host the application, allowing users to test text messages. The application will classify the messages as spam or not based on the model's performance.
## Introduction:
This project involves creating a machine learning model to classify SMS text messages as spam or not spam using a linear Support Vector Classification (SVC) algorithm. The model will be integrated into a user-friendly interface built with Gradio, allowing users to input text messages and receive immediate feedback on whether the message is likely to be spam.

## Features:
Refactored code to construct and train a linear SVC model
User-friendly Gradio app for testing text messages
Real-time feedback on message classification
Clear indication of whether a message is spam or not

## Requirements:
Python 3.x

pandas

scikit-learn

Gradio

## Installation:
Clone the repository:

bash or terminal 
Copy code
'git clone https://github.com/aFernandez88/sms_spam_detector.git'

'cd sms-text-classification'

## Model training:
Create a pipeline to:

Load and preprocess the SMS dataset

Split the data into training and testing sets

Train a linear SVC model and TfidfVectorizer

Fit the model

Make prediction whether text is 'spam' or 'ham'

Save the trained model for later use in the Gradio app


## Import the required dependencies

import pandas as pd

import gradio as gr

from sklearn.model_selection import train_test_split

from sklearn.pipeline import Pipeline

from sklearn.feature_extraction.text import TfidfVectorizer

from sklearn.svm import LinearSVC

## Contributing
Contributions are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

Gradio for the user-friendly interface

scikit-learn for the machine learning tools and algorithms
