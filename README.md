# Hate speech classification

## Problem statement

In this project, we have created an API which predicts a wheather the user has given hateful comment or not.

## Solution Proposed

The solution proposed for the above problem is that we have used NLP to solve the above problem.
We have used the Pytorch framework to solve the above problem also we used LSTM custom network with the help of PyTorch.
Then we created an API that takes in the text and classifies the type of feedback. Then we dockerized the application and deployed the model on the Google cloud.

## Dataset Used

There are two datasets one is imbalance data which consist of around 30000 rows and 2 column and the other dataset is the raw data which consist of 24000 rows and 7 columns.

## How to run?

```bash
conda create -n hate python=3.9 -y
```

```bash
conda activate hate
```

```bash
pip install -r requirements.txt
```

```bash
gcloud init
```
