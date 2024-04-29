# Pregnancy Drug Safety Prediction

## Overview
This project focuses on developing an explainable multimodal machine learning model for classifying the safety of drugs during pregnancy. The model aims to predict the safety of drugs based on various modalities, including textual descriptors and hierarchical clustering of drug features.

## Table of Contents
1. [Introduction](#introduction)
2. [Data](#data)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Usage](#usage)
6. [References](#references)

## Introduction
Pregnancy drug safety prediction is crucial for ensuring the well-being of both pregnant women and their unborn children. This project addresses the challenge by leveraging machine learning techniques to classify the safety of drugs during pregnancy.

## Data
The dataset used in this project consists of drug descriptions and safety labels collected from reputable sources such as DrugBank. Each drug is annotated with safety labels indicating its suitability for use during pregnancy.

## Methodology
### Text Mining
We employed FastText to generate word embeddings from drug descriptions, capturing semantic representations. Hierarchical clustering was then applied to group similar features together, reducing dimensionality while preserving essential information.

### Multimodal Machine Learning
We utilized a multimodal approach, combining textual descriptors with hierarchical clustering features. Various machine learning models, including MLP Classifier, Extra Trees Classifier, XGBoost Classifier, and Voting Orthogonal Large, were trained on the integrated features to predict drug safety during pregnancy.

## Results
The results section outlines the performance of different models evaluated through 10-fold cross-validation and cross-expert validation. Key metrics such as AUC, AUPR, and F1-score are reported for each model, highlighting the effectiveness of the proposed approach.

## Usage
To replicate the experiments conducted in this project, follow these steps:
1. Clone the repository to your local machine.
2. Install the necessary dependencies listed in the `requirements.txt` file.
3. Run the provided scripts to preprocess the data, train the models, and evaluate their performance.
4. Explore the results and analyze the predictive accuracy of each model.

## References
Shtar, G., Rokach, L., Shapira, B., Kohn, E., Berkovitch, M., & Berlin, M. (Year). Explainable multimodal machine learning model for classifying pregnancy drug safety. Journal Name, Volume(Number), Page range. DOI: [DOI number]
