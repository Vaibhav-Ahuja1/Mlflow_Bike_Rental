# Mlflow_Bike_Rental

*Whole code is comprised in ipynb file*

* This is an ML Model predictig the No. of bikes that will be rented per hour depending on various conditions.

* Dateset: Bike Sharing Dataset: http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

* MLflow is an easy to install tool, only a single command is enough `pip install mlflow` .

We have used **`Mlflow`** for **Metrics collection, Model packaging and to get UI at port 5000**

Every metrics is logged in MLflow. Mlflow also stores charts , artifacts , models, these stored files can be used later while reproducing.

# MLFlow
<img width="400" alt="MLflow-logo" src="https://user-images.githubusercontent.com/123439845/230708796-1c4562ed-ade0-4459-b2d3-c72f971c5834.png">

MLflow is an open source platform to manage the ML lifecycle, including experimentation, reproducibility, deployment, and a central model registry. MLflow currently offers four components

![ML Flow components](https://user-images.githubusercontent.com/123439845/230709253-60eab72c-99ae-436b-ac1f-4a490d33e5d3.png)

These components have different use cases and these can be used with any other component of MLFlow as well as can be done alone.

* ###  **MLflow Tracking** 


* ###  **MLflow Project**


### * **MLflow Model Packaging**


### **MLflow model Registry**



In this project we have taken `learning rate:[0.1, 0.05, 0.01]`, and `max depth: [4,5,6]` as **Hyper-Parameters** , these *3 x 3 hyper-parameter* set will generate *9 runs which are a sort of equal to 9 iterations of the model*.

These iteration will provide 9 different models with different accuracy and you can choose the best one among them and apply it into the ml workflow.

To get MLFlow Ui :  `mlflow ui --host 0.0.0.0 --port 5000`
















