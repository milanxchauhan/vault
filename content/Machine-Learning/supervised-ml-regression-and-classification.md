---
title: Supervised Machine Learning - Regression and Classification
draft: false
tags:
  - notes
---

# Week 1 - Intro to Machine Learning  
Basic activities like google search, apps recommending you movies to watch, voice to text messages all involve machine learning.  

## Supervised vs Unsupervised ML  

**What is ML?**  
> "Field of study that gives computers the ability to learn without being explicitly programmed" - Arthur Samuel (1959)  

**Machine Learning Algorithms**  
- Supervised learning  
- Unsupervised learning  
- Recommender Systems  
- Reinforcement learning  

### Supervised Learning  
Algorithms that learn X --> Y i.e. input to output mappings. You do do this by giving your learning algorithm examples containing the right answers. Right answer here means correct label Y for input X.  

| Input(X)          | Output(Y)              | Application         |   |   |
|-------------------|------------------------|---------------------|---|---|
| email             | spam?(0/1)             | spam filtering      |   |   |
| audio             | text transcripts       | speech recognition  |   |   |
| English           | Spanish                | Machine Translation |   |   |
| ad, user info     | click? (0/1)           | online advertising  |   |   |
| image, radar info | position of other cars | self driving cars   |   |   |
| image of phone    | defect? (0/1)          | visual inspection   |   |   |  

Let us take an example. Say you want to predict the price of a 750 sq feet house.  

![Regression](https://i.imgur.com/DUPb5tm.png)  

The goal of the learning algorithm is to look at the plotted points depicting the correct prices for specific house sizes and produce more of those correct prices.  

![Regression-02](https://i.imgur.com/TD8jqMj.png)

The algorithm that can used here is **Regression**. We will predict a number from infinitely many possible outputs.  

Let us now take a look at **Classification** algorithm, another type of supervised learning algorithm.  

Say we are building a tool to detect breast cancer. The tool has to predict whether the tumor is malignant(danger) or benign(non cancerous lump).  

Let us denote malignant using 1 and benign using 0. There are only 2 possible outputs. This is different from what were solving using Regression.  

![Classification](https://i.imgur.com/9s4dACF.png)  

The same graph can be plotted on a line.  
Classification algorithms predict categories from a small number of possible outputs.  
