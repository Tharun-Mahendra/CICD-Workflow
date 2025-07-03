**This repository demonstrates a continuous integration and continuous deployment (CI/CD) workflow for a simple machine learning project using the Iris dataset.**

## Project Overview

The main components of this project are:

1. **ModelTraining.py**: The Python script that trains a machine learning model on the Iris dataset.
2. **iris.csv**: The dataset file containing the Iris flower measurements.
3. **requirements.txt**: The file listing the Python dependencies required to run the project.
4. **.github/workflows/main.yaml**: The GitHub Actions workflow file that automates the CI/CD pipeline.

## CI/CD Workflow

The CI/CD workflow in this project is set up using GitHub Actions. Whenever a new commit is pushed to the repository, the following steps are automatically executed:

1. **Code Linting and Testing**: The Python code is linted and unit tests are run to ensure code quality and functionality.
2. **Model Training**: The `ModelTraining.py` script is executed to train a machine learning model on the Iris dataset.
3. **Artifact Deployment**: The trained model and associated files are packaged and deployed as a GitHub release, making them available for download and use.

This automated workflow helps to ensure that the project is always up-to-date, tested, and ready for deployment.
