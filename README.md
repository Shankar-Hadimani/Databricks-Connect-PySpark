# Developing with Databricks-Connect & Azure DevOps

## About
This is a sample Databricks-Connect PySpark application that is designed as a template for best practice and useability.

The project is designed for:
* Python local development in an IDE (VSCode) using Databricks-Connect
* Well structured PySpark application 
* Simple data pipelines with reusable code
* Unit Testing with Pytest
* Build into a Python Wheel
* CI Build with Test results published
* Automated deployments/promotions

## Setup

Create a Conda Environment (open Conda prompt):
```
conda create --name dbconnectappdemo python=3.5
```

Activate the environment:
```
conda activate dbconnectappdemo
```

IMPORTANT: Open the requirements.txt in the root folder and ensure the version of databrick-connect matches your cluster runtime.

Install the requirements into your environments:
```
pip install -r requirements.txt
```

If you need to setup databricks-connect then run:
```
databricks-connect configure
```

## Setup Deployment
If you would like to deploy from your local PC to Databricks create a file in the root called MyBearerToken.txt and paste in a bearer token from the Databricks UI.

