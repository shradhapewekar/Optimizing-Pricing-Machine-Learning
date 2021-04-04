# Optimizing Pricing with Machine Learning using LightGBM

In this machine learning project, I will build a model that automatically suggests the right product prices. 
 
Dataset: [Mercari](https://www.kaggle.com/saitosean/mercari/code) 

LightGBM is a relatively new algorithm 

Working:
Light GBM grows tree vertically.It will choose the leaf with max delta loss to grow. When growing the same leaf, Leaf-wise algorithm can reduce more loss than a level-wise algorithm.

Light GBM can handle the **large size** of data and takes **lower memory** to run. Another reason of why Light GBM is popular is because it **focuses on accuracy** of results.
LGBM also supports GPU learning
Light GBM is **sensitive to overfitting and can easily overfit small data.**
