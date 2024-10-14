# CovidNLP - Multi-Label Text Classification

This notebook was created to solve a text classification problem during a Kaggle competition hosted at my school.

## Overview

This project addresses a **multi-label text classification** problem, leveraging **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques. The dataset comes from a survey conducted during the first COVID-19 lockdown in France in 2020. The survey targeted individuals aged 75 and older, gathering their perceptions and concerns about the Coronavirus crisis.

### Dataset Context

The dataset is derived from a questionnaire designed to assess perceptions of the COVID-19 pandemic. Below are examples of the questions asked:

1. **Do you consider the Coronavirus as:**
   - No danger or low danger
   - Moderate danger
   - Serious danger
2. **On a scale of 0 to 10, how intense has your anxiety been in the last few days?**
3. **What are your main concerns?**

The first two questions are **closed-ended** and not part of this project. However, the third question is **open-ended**, allowing respondents to freely express their thoughts. The goal of this challenge is to analyze these free-text responses.

### Objective

The main objective is to classify each open-ended response into one or more of four predefined categories (multi-label classification). This involves identifying the concerns expressed by each respondent in their free-text answers.

## Dependencies

You can install the necessary dependencies via:
```bash
pip install nltk scikit-learn pandas numpy matplotlib
