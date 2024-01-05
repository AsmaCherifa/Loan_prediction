# Loan Prediction Machine Learning Project

## Overview

This repository contains the code and resources for a machine learning project that predicts loan approval based on various features.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Fine-Tuning](#fine-tuning)
- [Deployment](#deployment)
- [Monitoring and Maintenance](#monitoring-and-maintenance)
- [Contributing](#contributing)
- [License](#license)

## Dataset

- The dataset used for this project is located in "https://github.com/AsmaCherifa/Loan_prediction/blob/main/dataset/loan.xlsx". 
- It includes features like applicant income, loan amount, credit history, etc.
- The target variable is 'Loan_Status' (1: Approved, 0: Denied).

## Project Structure

- [model_training/](model_training/): Contains code for training the machine learning model.
- [notebooks/](notebooks/): Jupyter notebooks for data exploration, preprocessing, and model evaluation.
- [app/](app/): Deployment-related files if applicable.
- [dataset/](dataset/): The dataset used for training and testing.

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/AsmaCherifa/Loan_prediction.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Loan_prediction
    ```

3. Create a virtual environment and install dependencies:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
    pip install -r requirements.txt
    ```

## Usage

- Follow the steps in the [Setup](#setup) section.
- Run the Jupyter notebooks in the [notebooks/](notebooks/) directory for data exploration and model training.

## Model Evaluation

- Evaluate the model's performance using metrics like accuracy, precision, recall, and F1 score.
  
    ```bash
    python model_evaluation.py
    ```


## Deployment using Streamlit Sharing
Streamlit, as a powerful Python library for creating interactive web applications, allows developers to design a user interface effortlessly
Streamlit Sharing is a platform provided by Streamlit for deploying and sharing Streamlit apps online

![Capture3](https://github.com/AsmaCherifa/Loan_prediction/assets/66530514/3118c672-8be9-4968-b0cf-2128e76978ca)
