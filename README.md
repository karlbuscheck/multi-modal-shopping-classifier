# Building a Multi-Modal Classifier for Shopping Recommendations

Multi-modal classification is a type of classification problem where the input is composed of different types of data. In this project, we'll explore a case where the input is composed of both text and tabular data. Specifically, we will be looking at a dataset of clothing reviews and build a model to generate predictions (0's and 1's), indicating the likelihood that a given shopper would recommend a given item. You can read all about our model that we will be using for this task -- Google's bert-base-uncased -- [right here](https://huggingface.co/google-bert/bert-base-uncased) on Hugging Face.

## View the full notebook right here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17SPfMHY63F5r3SOx01w0foKuHGOkoZpu?usp=sharing)

## The Pipeline

Before we dive in, here's the pipeline that we will be following:

 - Set up the environment
- Load the dataset
-Import the tokenizer
-Split the training, validation and test sets
-Create the encodings
-Build the PyTorch dataset
-Design a neural network
-Train the model
-Generate predictions from the test set
-The big picture: Multi-modal classification at the frontier of ML

## Tools & Libraries Used

- **Google Colab** — for interactive coding and exploration  
- **Python 3.11.12** — base language for all modeling and data wrangling  
- **pandas** — for reading and managing the dataset of 31K news articles
- **numpy** - for numerical operations and array manipulation
- **gdown:** - for programmatically downloading files from Google Drive within the Colab environment
- **transformers** — Hugging Face's library for working with the BERT base model (uncased) 
- **torch** — for building and training the neural network components of the multi-modal classifier
- **scikit-learn** - for test-train split, classification metrics, and model evaluation   


## Acknowledgements

This project builds on work I started in my NLP class at Santa Clara University with Professor Michele Samorani. A big thanks to him and the Leavey School of Business for creating the kind of classes where real-world, data-driven projects like this can take shape.
