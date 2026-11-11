# Machine Learning to Predict Digital Frustration from Clickstream Data

This repository contains the supplementary notebook code for my paper:

**Machine Learning to Predict Digital Frustration from Clickstream Data**
arXiv: https://arxiv.org/abs/2512.20438

## Repository Content

* `supplementary_material_notebook.ipynb`
  This notebook contains the main code used for preprocessing the clickstream data, creating frustration labels, feature engineering, training machine learning models, and evaluating the results.
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jibin10/clickstream-frustration-prediction/blob/main/supplementary_material_notebook.ipynb)

## About the Work

In this work, I use the public Coveo e-commerce clickstream dataset to predict digital frustration in user sessions.

Frustration is defined using rule-based behavioural signals such as:

* Rage bursts
* U-turns
* Cart churn
* Search struggle
* Long wandering sessions

The notebook includes the steps for:

* Sessionization of raw clickstream data
* Symbolization of user actions
* Rule-based frustration labelling
* Feature engineering using n-grams, HVG motifs, entropy, and cyclical time features
* Training standard machine learning models
* Training an LSTM classifier
* Early-window frustration prediction

## Dataset

This work uses the public Coveo e-commerce clickstream dataset.

Dataset source: https://www.coveo.com/blog/dataset-release-intent-prediction-ecommerce/

The dataset is not included in this repository. Anyone using this code should download the dataset from the original Coveo source and follow their dataset terms and conditions.

## Code Access and Use

This project is open source under the MIT License. Anyone is welcome to use, modify, and share the code for research, education, or other purposes.

If this work is useful for academic research, citation of the original paper is appreciated:

https://arxiv.org/abs/2512.20438

## Contact

For any questions related to this work, please contact:

**Jibin Joseph**
Email: [jibinjoseph@utexas.edu](mailto:jibinjoseph@utexas.edu)
