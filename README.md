# ENS491-492-MAML

## Table of contents
* [Repository info](#repository-info)
* [Project info](#project-info)
* [Technologies](#technologies)
* [Setup](#setup)

## Repository info
maml_nn_5_rsrq.ipynb includes RSRQ forecasting with training data set of size 5 data points.
maml_nn_20_rsrq.ipynb includes RSRQ forecasting with training data set of size 20 data points.
maml_nn_40_rsrq.ipynb includes RSRQ forecasting with training data set of size 40 data points.
maml_nn_40_rsrp.ipynb includes RSRP forecasting with training data set of size 40 data points.
maml_nn_40_rs_snr.ipynb includes SINR forecasting with training data set of size 40 data points.
maml_nn_log_mean_var.ipynb includes logarithm of mean and variance for each size of training data set. 

## Project info
The aim of this Graduation Project is to use machine learning models to analyze and improve
the Quality of Experience (QoE) of fixed wireless services. In modern communication networks, user
Quality of Experience has been the most significant performance requirement. Unlike Quality of Service which describes network performance, user Quality of Experience is determined by the content,
user preferences, and how the content is delivered. Despite the fact that Quality of Experience is a
subjective metric, ITU P.1203 gives a quantitative approach to assess it. The purpose of this research
is to provide a mapping of network side parameters to user Quality of Experience using real-world
network traces, to learn the patterns and comprehend the core issues that need to be addressed in
order to improve the system’s performance, deep learning approaches will be employed. Our aim was
to give a mapping of network side parameters to user Quality of Experience. Deep learning algorithms
are used to understand the patterns, analyze and improve the Quality of Experience of fixed wireless
services and identify the core issues that need to be addressed in order to improve the performance
of the system. As a first step, literature research was carried out in the fields of Meta-Learning and
especially Model Agnostic Meta-Learning (MAML). Instead of developing a single model for all tasks,
MAML discovers a common initialization vector that allows quick training on any other task. By using
MAML few steps of Gradient Descent make a huge impact on finding converges.
	
## Technologies
Project is created with:
* Python
	
## Setup
All you need to do is to run the .ipynb files.
