# Question-Answering-System-using-Contextualized-Generative-Models(BERT)

This repository contains code for a question answering system using BERT (Bidirectional Encoder Representations from Transformers). The system is designed to answer questions based on a given context passage. This study proposes a Question Answering System based on the BERT model, a modern natural language processing approach. Using the Stanford Question Answering Dataset (SQuAD) with exact match and F1 score measures, the model was fine-tuned to improve its understanding and answer to human questions. 

## Introduction

The question answering system utilizes the BERT model fine-tuned on the SQuAD (Stanford Question Answering Dataset) dataset. It consists of several components including data preprocessing, model training, evaluation, and a user interface for interaction.

## Setup and Dependencies

To run the code, you need to have the following dependencies installed:

- `transformers` library: Install it using pip with the command `pip install transformers`.
- `torch`: PyTorch library.
- Other necessary libraries such as `numpy`, `matplotlib`, and `google.colab`.

Ensure that you have the necessary permissions and access to Google Drive for loading and saving model checkpoints and data files.

The code in this project utilizes the `transformers` library for working with pre-trained transformer models. The library is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). For more details, please refer to the [transformers GitHub repository](https://github.com/huggingface/transformers).


## Usage

1. **Data Preparation**: Ensure that your training and validation data in SQuAD format are stored in your Google Drive. Modify the file paths in the code accordingly.

2. **Training the Model**: Run the provided code to load the base BERT model and fine-tune it on your SQuAD dataset.

3. **Evaluation**: Evaluate the performance of the trained model on the validation dataset to assess its accuracy and other metrics such as exact match and F1 score.

4. **User Interface**: Use the provided user interface to interact with the trained model. Input a context passage and a question, and the system will generate an answer based on the trained model's predictions.

## Structure of the Repository

- `README.md`: This file providing an overview of the repository.
- `code.ipynb`: Jupyter Notebook containing the main code for data processing, model training, evaluation, and user interface.

