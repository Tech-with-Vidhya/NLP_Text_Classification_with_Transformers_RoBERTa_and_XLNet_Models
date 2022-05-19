# NLP_Text_Classification_with_Transformers_RoBERTa_and_XLNet_Model

<h3><b><u>Introduction:</u></b></h3>

This project covers the end to end implementation of how to load, fine tune and evaluate various transformer models for NLP based text classification tasks.

In this project, 2 types of transformer models are explored to categorize human emotions using Hugging Face library dataset.

1. RoBERTa: A Robustly Optimized BERT Pretraining Approach
2. XLNet: Generalized Autoregressive Pretraining for Language Understanding

The architectures of these two models are analysed, studied about the training and optimization techniques and finally used them to classify Human Emotions into separate categories.

<h3><b><u>Dataset:</u></b></h3>

<h3><a href="https://huggingface.co/datasets/emotion" style="color: blue"><b><u>Hugging Face Emotion Dataset</u></b></a></h3>

Emotion is a dataset of English Twitter messages with six basic emotions: anger, fear, joy,love, sadness, and surprise. 

we will be using the Human Emotions datasets from the hugging face library.

The dataset comprises of three data categories namely,
1. Train - 16000 rows and 2 columns
2. Validation - 2000 rows and 2 columns
3. Test - 2000 rows and 2 columns

<h3><b><u>Project Implementation Steps:</u></b></h3>

The project aims at building two models namely RoBERTa and XLNet to perform classification on the human emotion dataset, by implementing the below steps for both the models.

1. Data Exploration and Analysis
2. Data Pre-processing
3. Creation of the RoBERTa/XLNet Model
4. Compiling the RoBERTa/XLNet Model
5. Model Training with Fine-Tuning
6. Model Evaluation and Validation
7. Model Performance Metrics Measures
8. Saving the Final Optimized Model
9. Verifying the Final Optimized on the Unseen Test Data

<h3><b><u>Tools & Technologies:</u></b></h3>

Python, numpy, pandas, ktrain, transformers, tensorflow, sklearn, amtplotlib

