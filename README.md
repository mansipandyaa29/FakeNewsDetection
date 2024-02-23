<h1 align="center">Fake News Detection Using ML.</h1>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)]()
  ![GitHub repo size](https://img.shields.io/github/repo-size/vipul-shinde/customer-churn-prediction)

</div>

---

<p align="center"> In this project, we are trying to predict the possibility a News Article being fake or real thus helping combat misinformation and address social challenges among other things.
    <br>
</p>

## 📝 Table of Contents

- [🧐 About](#about)
- [📊 Dataset Overview](#data-overview)
- [🧠 Model Building](#neural-network-model)
- [🏅 Model Evaluation](#model-evaluation)
- [🌟 Support](#support)

## 🧐 About <a name = "about"></a>

Fake news refers to false or misleading information presented as factual news. It can take various forms, including fabricated stories, deceptive headlines, manipulated images or videos, and misleading or biased reporting.

In this project, I built a machine learning model that'll help people predict is a news article is fake or real.

## 📊 Dataset Overview <a name="data-overview"></a>

The dataset was downloaded from the <a href="https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection">Kaggle Fake News Detection Dataset</a>. 

This dataset contains news title, text assocaited with the news title and type of news and the date of news.

<details>
<summary>Click to check Dataset Attributes:</summary>
<br>

1. ```Title```: Title of News

2. ```Text```: Description of the News

3. ```Subject```: Type of News

4. ```Date```: Date of News
</details>

### Click to view 👇:

[![forthebadge](figures/badges/solution-exploratory-data-analysis.svg)](https://github.com/mansipandyaa29/FakeNewsDetection/blob/main/notebooks/FakeNewsDetection.ipynb)

```P.S: The notebook is still in works```

## 🧠 Model Building <a name="neural-network-model">

We implemented the following machine learning models for predicting the chances that a given customer will churn. 

1. Logistic Regression
2. Random Forest Classifier
3. K Nearest Neigbors Classifier
4. Neural Networks

### Click to view 👇:

[![forthebadge](figures/badges/solution-model-building.svg)](https://github.com/mansipandyaa29/FakeNewsDetection/blob/main/notebooks/FakeNewsDetection.ipynb)

```Scroll all the way down```

## 🏅 Model Evaluation <a name="model-evaluation">

Here are the model's performance on the unseen test dataset:

| **Model**                            | **Accuracy** | **Precision** | **Recall** | **f1-Score** |
|--------------------------------------|--------------|---------------|------------|--------------|
| Logistic Regression                  | 0.621        | 0.62          | 0.62       | 0.62         |
| Random Forest Classifier             | 0.36         | 0.22          | 0.36       | 0.27         | 
| K Nearest Neighbors Classifier       | 0.91         | 0.91          | 0.91       | 0.91         |
| Extreme Gradient Boosting Classifier | 0.984        | 0.98          | 0.98       | 0.98         | 

## 🌟 Support <a name="support">

Hit the ⭐ button if you like this project. 😄

# Thank you!