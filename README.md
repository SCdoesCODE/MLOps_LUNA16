# Medical Imaging on AWS

## Introduction

This repository documents my journey in using ML Ops tools and AWS services to preprocess medical imaging datasets and fine-tune a machine learning model for cancer research. The project utilises the LUNA16 dataset, a collection of annotated CT scans for lung cancer detection. The primary goal is to learn ML Ops workflows, including cloud infrastructure setup, data preprocessing, model training, and deployment, while staying within the AWS Free Tier limits as it is a project I am doing on my free time and simply for learning purposes.

## Cloud infrastructure and AWS services used

- S3: Store preprocessed datasets. (maximum free storage 5GB)
- EC2: Handle preprocessing and smaller tasks. (maximum free storage 30GB)
- SageMaker: Data handling and train the ML model in jupyterlab notebooks. (250 hours of free training on selected CPU instances)
- CloudWatch: Monitor and debug logs.

## Dataset

LUNA16: https://luna16.grand-challenge.org/

## Instructions for how to reproduce the process

My notes and remarks while setting up and learning during this project can be found in the Instructions.ipynb notebook. 

## TODO

- use SageMaker to finetune 3D U net model on LUNA16 data (didn´t know I had to stop my notebook instance, 250 hour limit per month on sagemaker - so will have to wait for february to finish the work for this repo)
- use cloudwatch to monitor logs 