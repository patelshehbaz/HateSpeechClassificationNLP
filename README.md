# Hate speech classification
#### Language and Libraries

<p>
<a><img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen" alt="python"/></a>
<a><img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas"/></a>
<a><img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="numpy"/></a>
<a><img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="pytorch"/></a>
<a><img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)" alt="docker"/></a>
<a><img src="https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white" alt="gcp"/></a>
</p>


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
