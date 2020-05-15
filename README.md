# Udagram Image Filtering Microservice

A node express microservice to filter images using the Jimp package. The image_url is sourced from user input and a valid input requires a publicly accesible image.

## Steps to run the code locally

After cloning the repository, run `npm install`

After the node_modules folder has been created, type the command `npm run dev`

## Getting Started

The application runs by default on the port 8082 and you can send a GET request to the following url
http://localhost:8082/filteredimage?image_url=https://udagram-amitesh-dev.s3.ap-south-1.amazonaws.com/amitesh.jpg

## EBS Endpoint

For Udacity review, the Elastic Beanstalk endpoint - http://image-filter-amitesh-dev.ap-south-1.elasticbeanstalk.com/filteredimage?image_url=https://udagram-amitesh-dev.s3.ap-south-1.amazonaws.com/amitesh.jpg

## EBS Screenshot

The elastic beanstalk screenshot can be found in the deployment_screenshots directory
