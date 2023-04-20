# Parameter Optimization of SVM

Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/HTRU2](https://archive.ics.uci.edu/ml/datasets/HTRU2)

This dataset is used for estimating the precise number of Pulsar candidates collected during the HTRU survey. Pulsars are a type of star, of considerable scientific interest. Candidates must be classified in to pulsar and non-pulsar classes to aid discovery.
It is a multi-variate classification Dataset.

Number of Instances: 17898

Number of Attributes: 9

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.92 | Sigmoid | 9.64 | 4.62 |
| 2 | 0.95 | Linear | 6.40 | 2.01 |
| 3 | 0.91 | Sigmoid | 2.34 | 1.93 |
| 4 | 0.91 | Sigmoid | 1.24 | 3.41 |
| 5 | 0.91 | Sigmoid | 6.07 | 2.99 |
| 6 | 0.91 | Sigmoid | 4.45 | 2.89 |
| 7 | 0.91 | Sigmoid | 6.86 | 8.89 |
| 8 | 0.55 | Linear | 2.48 | 1.33 |
| 9 | 0.91 | Sigmoid | 9.70 | 5.52 |
| 10 | 0.69 | Linear | 4.22 | 6.23 |

## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 2 has the best accuracy of 0.95 having kernel = Linear, Nu = 6.40 and Epsilon = 2.01.

## Written By
Name : Kunal Madan
  
Roll No. : 102053007

Sub-Group: 3CO10
