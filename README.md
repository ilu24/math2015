# Math 2015 Final Project

#### by: Kaan Erdem, Isabella Lu, Austin Senna, Will Wang

Run through the cells sequentially to see project workflow.

#### Abstract
This project investigates Principal Component Analysis (PCA) as a mathematical method
for dimensionality reduction. We implement PCA from first principles using eigendecompo-
sition of covariance and correlation matrices, and evaluate its performance on distinct data
modalities: the California Housing dataset (tabular numeric) and two image datasets (CIFAR-
10 and LFW Faces). Our analysis demonstrates how PCA identifies orthogonal directions of
maximum variance, enabling significant dimensionality reduction. For the image datasets, we
achieve substantial compression: CIFAR-10 retains 90% variance with 98 components (3.2%
of dimensions), while LFW requires 268 components (2.2% of dimensions). We compare Co-
variance versus Correlation PCA on the numeric dataset to demonstrate the impact of feature
scaling. We find that unscaled Covariance PCA fails to capture multivariate structure, falsely
concentrating 100% of variance in a single high-magnitude feature (“Population”), whereas Cor-
relation PCA successfully recovers latent relationships between income, age, and location. We
conclude with a theoretical analysis connecting eigenvalue magnitudes to information retention
via the Eckart-Young theorem and visual demonstrations of reconstruction quality.
