# Mycological Machine Learning

This repo is my completed Udacity Machine Learning Engineer capstone project. For my capstone I used the UCI Machine Learning Repository [mushroom dataset](https://archive.ics.uci.edu/ml/datasets/mushroom) to train a model to predict whether a mushroom is poisonous or not. The model was trained with AWS Sagemaker's built-in [Linear Learner](https://docs.aws.amazon.com/sagemaker/latest/dg/linear-learner.html) algorithm. 

The project notebook covers data visualization, data-preprocessing, training, refinement, and model deployment. It also covers how to use AWS Lambda and API Gateway to give web users access to the deployed model so that they can input data and receive the model's predictions. As part of the deployment process, I have also created a Django [web app](https://github.com/Pat878/mushroom-project).

In order to run the notebook, you will need to use a Sagemaker notebook instance. Here are [instructions](https://docs.aws.amazon.com/sagemaker/latest/dg/nbi-git-repo.html#nbi-git-resource) on how to set up a notebook instance from a GitHub repo.