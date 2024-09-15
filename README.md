## COMPLETED

# ASSIGNMENT DETAILS


Assignment 1a
In this assignment you will be working on setting up your system and refreshing basic probability theory or basic linear algebra concepts such as Singular Value Decomposition (SVD). You are mandated to use the Pytorch namespace libraries such as pytorch.linalg, pytorch.rand and in general libraries in the pytorch.xyz namespace but not any derived or any other libraries. The idea is to implement from scratch the following without implementing every minute component such as random number generators etc.

Points:

Dev Environnment : 5 points
Simulation of gaussian random variables : 5 points
KMeans : 20 points
PCA : 20 points
Development Environment Setup
Following the instructions of the course site with respect to the course docker container

Install docker on your machine.
Clone the repo (For windows users ensure that you clone it on the WSL2 filesystem.) Show this by a screenshot below of the terminal where you have cloned the repo.
Build and launch the docker container inside your desired IDE (if you havent used an IDE before you can start with VSCode).
Launch the virtual environment with rye sync inside the container and then show a screenshot of your IDE and the terminal with the (your virtual env) prefix.
Select the kernel of your virtual environment (.venv folder) and execute the following code. Save the output of all cells of this notebook before submitting.
Source: Development Environment Setup
Simulation of Multivariate Normal Distribution
Generate 
 samples from each of the two Bivariate Normal distributions.

A: mean 
 and covariance matrix  
 
.

B: mean 
 and covariance matrix  
 
.

Plot them in the same plot and stack them into a single tensor X as if it is generated from a single distribution.

Source: Simulation of Multivariate Normal Distribution
K-Means Clustering
Using the steps outlined in this video, implement K-means clustering using Pytorch pytorch.xyz libraries, for the unsupervised dataset created from the stacked 
 data points of the two bivariate Gaussian distributions below:

A: mean 
 and covariance matrix  
 
.

B: mean 
 and covariance matrix  
 
.


Source: K-Means Clustering
Projection with Principal Components Analysis (PCA)
Using the synthetic dataset outlined in the video, replicate the steps using pytorch.xyz namespaced libraries to perform PCA on the dataset.
