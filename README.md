# Scones Unlimited Machine Learning Workflow

## Overview

Scones Unlimited, a leading baked goods delivery company, faces challenges in efficiently managing their delivery fleet. To streamline their operations, we are tasked with building an advanced image classification model that can classify the vehicles used by delivery drivers into two categories: bicycles and motorcycles.

The primary goal of this project is to:

Optimize Delivery Routing: By accurately determining whether a delivery professional is using a bicycle or a motorcycle, the model will help assign nearby orders to bicycle riders and more distant orders to motorcyclists. This optimization will reduce delivery times and enhance overall delivery efficiency.


## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Data Preparation](#data-preparation)
- [Model Training](#model-training)
- [Model Deployment](#model-deployment)
- [Model Monitoring](#model-monitoring)
- [License](#license)

## Features

- Image classification for vehicles for optimizing delivery routing.
- Utilizes AWS microservices for scalability and flexibility.
- Training jobs for fine-tuning the model to the specific needs of Scones Unlimited.
- Automated workflows using Step Functions for seamless execution.
- Model monitoring to ensure high performance and timely retraining.

### The Scones Unlimited Machine Learning Workflow consists of several key stages, each with its own set of functionalities. Below is an overview of the major steps involved:

## Data Preparation

I first prepared the image dataset for model training. Organized the images into appropriate folders and ensured proper labeling for each category.

## Model Training

Then Used SageMaker to train the image classification model with the prepared dataset. Fine-tuned the model as needed to achieve optimal results for Scones Unlimited's specific requirements.

## Model Deployment

Once the model is trained and tested, I did deploy it using AWS Lambda. This will allow real-time inference on new images and provide predictions for traffic management decisions.

## Model Monitoring

Then I implemented model monitoring to track the model's performance over time, Set up alerts to trigger retraining if the model's accuracy drops below a predefined threshold.

## License

The Scones Unlimited Machine Learning Workflow project is licensed under the MIT License.
