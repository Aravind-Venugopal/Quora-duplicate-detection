# Quora-duplicate-detection
<!-- ![architecture](https://storage.googleapis.com/cloud-samples-data/ai-platform/census/keras-tensorflow-cmle.png){width:200px;} -->
<img src="https://storage.googleapis.com/cloud-samples-data/ai-platform/census/keras-tensorflow-cmle.png" height="60" />

### Detecting duplicate questions using keras and xgboost

Using keras and xgboost to create models which can identify duplicate questions or sentences. The model was trained on a dataset from Quora, using google colab GPU.
Once trained the model was uploaded to GCP cloud storage and deployed on GCP AI platform. 
GCP cloud APIs were used to generate predictions from the deployed model.

<img src="architecture.png" />

A simple interface(shown below) was developed using Jupyter to visualize the model results.

![preview](Quora_project.gif)