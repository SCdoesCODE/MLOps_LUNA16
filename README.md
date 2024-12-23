# Medical_Imaging

Detection of lung nodules in CT scans using the LUNA16 dataset. 

LUNA16: https://luna16.grand-challenge.org/

This project is done using the AWS Free Tier. Preprocessing is done on an EC2 instance (maximum free storage 30GB) and preprocessed data will be stored in S3 (maximum free storage 5GB).

## Notebooks with instructions on how recreate project and use AWS

- Setup_Instructions.ipynb
- Reconnecting_Instructions.ipynb
- Create_S3_Bucket_Instructions.ipynb

## Notebooks for downloading and preprocessing data

- Download_LUNA16.ipynb
- Subsetting_Data.ipynb

## TODO

- use SageMaker to train model
- use cloudwatch to monitor logs 