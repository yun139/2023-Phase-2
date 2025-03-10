# Part 3 - Microsoft Azure

Welcome to the third and final part of Phase 2 for the Data Science stream! This part will involve you doing (almost) everything you've done in the first two parts, except in the cloud! 

Microsoft's cloud computing platform is called Azure and this part will specifically focus on Azure Machine Learning, a service within Azure that allows you to do everything from running Jupyter notebooks and training machine learning models in the cloud to logging evaluation metrics across multiple iterations of model development and deploying models from within the Azure portal (i.e. the website you'll use to access Azure from your web browser) or from your own code.

We hope you find that doing data science in the cloud makes several things easier and faster to accomplish while unlocking some useful features that can help you as a data scientist deliver more value in less time!

## Getting Started

1. Complete [Getting Started with Azure Machine Learning](../0.%20Resources/docs/getting-started-with-azure-ml.md)

2. Read the comments and code in the [example.ipynb](./example.ipynb) notebook that we have provided for you to practice deploying a model onto Azure. Feel free to adapt the code within this notebook for your own work.

3. Choose one dataset from your two chosen datasets to use for this part and complete the tasks below. Make sure you have completed the first two parts and are using your processed dataset for this part.

## Tasks

If you have completed the first two parts, you are well on your way to completing the technical component of Phase 2! This third part is a smaller one since we recognise that you may have spent most of your time on the first two parts, and also Azure Machine Learning consists of a deep set of tools that could take weeks to cover in themselves.

The tasks below correspond to the tools visible in your workspace in Azure Machine Learning Studio, please complete the tasks with the help of the resources provided.

1. Use [Endpoints](https://ml.azure.com/endpoints/realtime) to create a real-time endpoint for your trained model from the previous part - resources:
    - [Deploy real-time machine learning services with Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/register-and-deploy-model-with-amls)
    - [Deploy a model to a managed online endpoint](https://learn.microsoft.com/en-us/training/modules/deploy-model-managed-online-endpoint)
    - [Deploy and score a machine learning model by using an online endpoint](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-deploy-online-endpoints)
    - [2021 Phase 2 - Model Deployment](https://github.com/NZMSA/2021-Phase-2-Data-Science/tree/master/4.%20Deploy%20Model%20onto%20Azure)
    - [deploy-local](https://github.com/Azure/azureml-examples/tree/main/v1/python-sdk/tutorials/deploy-local)

2. Complete at least ONE of the following tasks below to the best of your ability and time available:
    - Use [Models](https://ml.azure.com/model/list) and [Notebooks](https://ml.azure.com/fileexplorerAzNB) to run your Jupyter notebook/s for model training and evaluation, and register your trained model in Azure - resources:
        - [Train a machine learning model with Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/train-local-model-with-azure-mls)
        - [Run a training script as a command job in Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/run-training-script-command-job-azure-machine-learning)
    - Use [Jobs](https://ml.azure.com/experiments) to run a script for tuning hyperparameters - resources:
        - [Tune hyperparameters with Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/tune-hyperparameters-with-azure-machine-learning)
        - [Perform hyperparameter tuning with Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/perform-hyperparameter-tuning-azure-machine-learning-pipelines)
        - [Track model training with MLflow in jobs](https://learn.microsoft.com/en-us/training/modules/train-models-training-mlflow-jobs)
    - Use [Automated ML](https://ml.azure.com/automl/welcome) to automatically train and tune models to find the best one via experiments with different features, algorithms, and parameters - resources:
        - [Find the best classification model with Automated Machine Learning](https://learn.microsoft.com/en-us/training/modules/find-best-classification-model-automated-machine-learning)
        - [Automate machine learning model selection with Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/automate-model-selection-with-azure-automl)
        - [automl-with-azureml](https://github.com/Azure/azureml-examples/tree/main/v1/python-sdk/tutorials/automl-with-azureml)

## Submission

To complete this part, please include the following items in your repository:

- A Jupyter notebook (.ipynb) containing:
    - The API endpoint for your deployed model, with details on how to format the input data for your specific processed dataset and model (so that we can test your endpoint for marking purposes).
    - Any code, written explanations, results, screenshots of your Azure workspace (e.g. hyperparameter tuning results, precision and recall, ROC/AUC curves), and/or anything else to explain the steps you took and the outputs you generated.

Note: please do not delete or turn off any resources you have created until the team has completed marking. Once the team has completed marking we will inform you, after which you may clean up your resources as explained in [this section](https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-azure-ml-in-a-day?view=azureml-api-2#clean-up-resources) of the Azure Machine Learning documentation.

## Marking Criteria

1. Task Completion
    - Written an entry script that creates an endpoint for the student's processed dataset and model
    - The endpoint takes input data as specified by the student and produces a result (either a label (classification) or value (regression))
    - The student has completed at least one of the tasks in the list above (marking for this will be based on a comparative evaluation against other students)

2. Presentation
    - Your notebook/s and the code within them must be well-commented so that someone looking at your notebook/s for the first time can easily understand and follow along with what you did
        - Note that "well-commented" means that you have provided easily understandable explanations for what the results of your code mean or what you have inferred from them
        - We may penalise notebooks that only contain code and nothing else.

## Tips

- This part relies heavily on the Microsoft Learn modules from Week 5 of Phase 1! In particular, we recommend that you go through the following resources to support your work:
    - [Quickstart: Get started with Azure Machine Learning](https://learn.microsoft.com/en-gb/azure/machine-learning/tutorial-azure-ml-in-a-day)
    - Azure Machine Learning Hands-On Exercises from Phase 1 Microsoft Learn modules
        - https://microsoftlearning.github.io/mslearn-azure-ml
        - https://microsoftlearning.github.io/mslearn-dp100
    - Units 2 and 3 of [Introduction to Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-ml/2-what-is-azure-ml)
    - Unit 6 of [Explore Azure Machine Learning workspace resources and assets](https://learn.microsoft.com/en-us/training/modules/explore-azure-machine-learning-workspace-resources-assets/5-run-jobs)