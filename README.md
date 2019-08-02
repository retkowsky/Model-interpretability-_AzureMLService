# Model-interpretability-_AzureMLService
Model interpretability with Azure Machine Learning service

In machine learning, features are the data fields used to predict a target data point. For example, to predict credit risk, data fields for age, account size, and account age might be used. In this case, age, account size, and account age are features. Feature importance tells you how each data field affected the model's predictions. For example, age may be heavily used in the prediction while account size and age don't affect the prediction accuracy significantly. This process allows data scientists to explain resulting predictions, so that stakeholders have visibility into what data points are most important in the model.

Using these tools, you can explain machine learning models globally on all data, or locally on a specific data point using the state-of-art technologies in an easy-to-use and scalable fashion.

The interpretability classes are made available through multiple SDK packages. Learn how to install SDK packages for Azure Machine Learning.

azureml.explain.model, the main package, containing functionalities supported by Microsoft.

azureml.contrib.explain.model, preview, and experimental functionalities that you can try.

azureml.train.automl.automlexplainer package for interpreting automated machine learning models.


https://docs.microsoft.com/en-us/azure/machine-learning/service/machine-learning-interpretability-explainability
