<img width="800" height="524" alt="image" src="https://github.com/user-attachments/assets/6c5f6646-5a4c-4501-a075-0edfef08117e" />

# AWS Image Resizer

This project provides a CloudFormation template for an AWS Lambda function that automatically resizes images uploaded to an S3 source bucket.  
The resized images are saved to a destination bucket, and an SNS notification is sent to alert subscribers.

## Features
- Upload an image to the source S3 bucket.
- Lambda function resizes the image to max 800x800 pixels using Pillow.
- The resized image is stored in the destination S3 bucket.
- SNS notification is published after successful processing.

## Technologies
- AWS Lambda 
- Amazon S3  
- Amazon SNS  
- Pillow library for image processing  

