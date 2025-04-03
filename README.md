**Large Language Models (LLM) - Group Assignment**

Overview

This repository contains code developed as part of a group assignment for the course Large Language Models. The project focuses on analyzing and classifying fake news using large language models.

Datasets Used

The following datasets are utilized in this project:

1. LIAR Dataset
Description: The LIAR dataset consists of 12.8K labeled statements with various degrees of truthfulness.
Download:https://sites.cs.ucsb.edu/~william/data/liar_dataset.zip
Labels:
Pants-fire
False
Barely-true
Half-true
Mostly-true
True

2. FakeNewsNet Dataset
Description: The FakeNewsNet dataset contains real and fake news articles.
Download:https://github.com/KaiDMML/FakeNewsNet
Labels:
Real
Fake

**Code Files**

1. Group3_GPT.ipynb
**This file requires an OpenAI API Key to be updated before execution.**
It leverages GPT-based models for processing and classification tasks.

2. Group3_RoBERTa.ipynb
Contains code for training and evaluating a RoBERTa model using the above datasets.
Implements preprocessing, model fine-tuning, and evaluation metrics.


Setup Instructions

--> Clone the repository:

    git clone https://github.com/smruthijv/LLM

--> Install required dependencies:

    pip install -r requirements.txt

--> Update the OpenAI API Key in Group3_GPT.ipynb before running the script.
--> Update the dataset path in both Group3_GPT.ipynb and Group3_RoBERTa.ipynb


