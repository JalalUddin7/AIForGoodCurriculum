

# Content for AI for good session - 26th Feb 2020

This provides some good material to support various starting points in your machine learning journey.  While it assumes very little knowledge as a pre-requisite, there is also some content for the more advanced.

## Some Foundation material

**Some of the fundamentals content using Azure Machine Learning Studio (your initial homework):**

[Explore AI solution development with data science services in Azure](https://docs.microsoft.com/en-gb/learn/paths/explore-data-science-tools-in-azure/)

* 	Introduction to Data Science in Azure
* 	Choose the Data Science service in Azure you need


Next, learn how to use the Azure Machine Learning designer to train and deploy a machine learning model that predicts the price of any car. The designer is a drag-and-drop tool that lets you create machine learning models without a single line of code.  **NOTE**: You will need to upgrade to Enterprise to complete this tutorial.

- In this [first part](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-designer-automobile-price-train-score
) you learn how to use the Azure Machine Learning designer to train the model.
- In [this](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-designer-automobile-price-deploy) second part, you deploy the model to give others a chance to use it. You generate new predictions based on user input.


To support this further, we've provided some broader reference material, which may be of interest:

**Some Machine learing Cheat Sheets:**

Machine Learning typically uses many algorithms from the classification, recommender systems, clustering, anomaly detection, regression, and text analytics families. Azure Machine learning is no exception.  Each algorith addresses a different type of machine learning problem. These cheat sheets help you consider which approach might be appropriate for your analytics model.

- [Machine learning algorithm cheat sheet for Azure Machine Learning Designer](https://docs.microsoft.com/en-us/azure/machine-learning/algorithm-cheat-sheet)
- [28 cheat sheets for Machine Learning, Data Science, Probability, SQL & Big Data](https://www.analyticsvidhya.com/blog/2017/02/top-28-cheat-sheets-for-machine-learning-data-science-probability-sql-big-data/)

It's often not clear which machine learning algorithm would be more appropriate. [This](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-select-algorithms) may help clarify some core questions to ask yourself and types of success criteria.  

## Tutorials and Labs

### Studio and Designer

Here are some more Azure Machine Learning Studio examples to help reflect on how to solve different sorts of problems using an interface, which you are starting to become familiar with:

- In [this](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-first-experiment-automated-ml) tutorial, you'll create an automated machine learning experiment through Azure Machine Learning studio without writing a single line of code. This uses classification to predict if a client will subscribe to a fixed term deposit with a financial institution.  Automated machine learning rapidly iterates over many combinations of algorithms and hyperparameters to help you find the best model based on a success metric of your choosing 
- In [this](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-automated-ml-forecast) tutorial, you use automated machine learning, or automated ML, in the Azure Machine Learning studio to create a time series forecasting model to predict rental demand for a bike sharing service.

### Using Python:

- **Foundations**
	- In this [first part](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-1st-experiment-sdk-setup) of a two-part tutorial, you complete the end-to-end steps to get started with the Azure Machine Learning Python SDK running in Jupyter notebooks. This part covers Python environment setup and configuration, as well as creating a workspace to manage your experiments and machine learning models.
	- In this [second part](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-1st-experiment-sdk-train), you learn some foundational design patterns in Azure Machine Learning, and train a simple scikit-learn model based on the diabetes data set. After completing this tutorial, you will have the practical knowledge of the SDK to scale up to developing more-complex experiments and workflows.
- **Image Recognition**
	- In this [first part](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-train-models-with-aml) of a two-part tutorial, you train a machine learning model on remote compute resources (in Azure). Your training and deployment workflow will be in a Python Jupyter notebook. You could use this notebook as a template to train your own machine learning model with your own data.
	- In this [second part](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-deploy-models-with-aml) you'll deploy the model as a web service in Azure Container Instances (a Docker image). It encapsulates the scoring logic and the model itself.

### Using the Command Line Interface (CLI)

- Not *code* but *process*: In [this](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-train-deploy-model-cli) tutorial, you'll use the machine learning extension for the Azure CLI to train, register, and deploy a model.  You'll use Python with scikit-learn to train a basic model, but the focus here is not on the scripts or the model, but the process of using the CLI to work with Azure Machine Learning.  You might then consider a similar approach with some parts of your own scenarios. 

### DP-100 - Designing and Implementing a Data Science Solution on Azure

[This](https://github.com/MicrosoftLearning/DP100/blob/master/labdocs/README.md) repository provides a number of exercises that will help in your preparation for your [DP-100](https://docs.microsoft.com/en-us/learn/certifications/courses/dp-100t01) certification.




	