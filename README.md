# Pytorch serving practice
## TODO

1. What and Why MLflow?
2. MLflow Installation
3. MLflow vs. BentoML
4. MLflow Simple Usage
   1. MLflow tutorial
      1. https://www.mlflow.org/docs/latest/tutorials-and-examples/index.html

## What and Why MLflow?

1. Open-source tool to organize your entire ML lifecycle
2. Non-cloud service solution
3. MLflow provides solutions for ...
   1. Managing ML process and deployment
   2. experimentation
   3. reproducibility
   4. deployment
   5. central model registry
4. MLflow pros
   1. model tracking mechanism is easy to set up
   2. Offers very intuitive APIs for serving
   3. logging is practical and simplified, easy to run experiments
   4. Code-first approach
5. MLflow cons
   1. The addition of extra workings to the models is not automatic
   2. Not quite easy and ideal for deploying models to different platforms

## MLflow installation

```bash
pip install mlflow bentoml
```

## MLflow vs. BentoML

1. MLflow provices components that work great for **<u>experimentation management</u>**, **<u>ML project management</u>**
2. BentoML only focuses on serving and deploying trained models
   1. Can serve models **logged in MLFlow experimentation** with **BentoML**

