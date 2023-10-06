# Amazon Product Recommendation System

## Overview
This recommendation system is built using TensorFlow Recommenders library to recommend the top 5 products for a given user based on their user ID. The system utilizes collaborative filtering techniques to suggest products that are likely to be of interest to the user based on the historical product reviews and interactions of other users.

Additionally, there is a user-friendly web-based UI created using Gradio, which allows users to interact with the recommendation system. The UI displays important information about the recommended products, including brand name, product reviews by other users, product name, and product images.

## Requirements
Before running the recommendation system and the UI, make sure you have the following dependencies installed:

Python 3.x
TensorFlow 2.x
TensorFlow Recommenders library
Gradio
You can install the required Python libraries using pip:

bash
Copy code
pip install tensorflow tensorflow_recommenders gradio
## Customization
You can customize the recommendation system by:

Fine-tuning the model parameters in recommendation_system.py to improve recommendation quality.
Modifying the UI layout and design in ui.py to match your preferences.
Adding more features and information to the product recommendations based on your dataset.
##Dataset
Make sure you have a suitable dataset of Amazon product reviews in the required format for training the recommendation system. You may need to preprocess and clean the dataset to fit the model's input requirements.

## Acknowledgments
This project was built using the TensorFlow Recommenders library and Gradio, which are powerful tools for building recommendation systems and user interfaces.

## Demo
Here a Code link [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15RQ17r-Pw9JD-Y36UiwBBRA6a8aHGaz1#scrollTo=JAh3RjZBM9N6)
