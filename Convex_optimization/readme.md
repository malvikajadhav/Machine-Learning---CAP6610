## Problem Statement 1 
We test the performance of three regression methods on the wine data set http://archive.
ics.uci.edu/ml/datasets/Wine+Quality. We will only consider the red wine data set, with 1599
samples. We use the first 1400 samples for training, and the last 199 samples for testing. The goal is
to build a linear model of the first 11 features (together with a constant term) to predict the quality
of the wine. All models are trained by solving the following optimization problem
![image](https://user-images.githubusercontent.com/20522169/154814775-872dff9f-43cc-46df-88bc-24a39e81b1cb.png)
The least squares loss can be directly solved by the command Phi\y for some properly defined Phi. For
the latter two, you will use the cvx package found on Prof. Boyd’s website https://web.stanford.
edu/~boyd/software.html. Report their prediction performance on the test set using a different
metric, mean absolution error (MAE), defined as (1/n)
Pn
i=1 |yi − yˆi|.

## Problem Statement 2
We test the performance of three classification methods on the ionosphere data set https:
//archive.ics.uci.edu/ml/datasets/ionosphere. There are 351 samples. We use the first 300
samples for training, and the last 51 samples for testing. The goal is to build a linear model of the 34
features (together with a constant term) to predict the binary (±1) outcome. All models are trained
by solving the following optimization problem
![image](https://user-images.githubusercontent.com/20522169/154814802-969a7c29-44ae-4b91-af55-5c5f06d7c2d1.png)
![image](https://user-images.githubusercontent.com/20522169/154814812-a8fa1a9d-8d64-4833-a84b-8d4b88d3f181.png)
