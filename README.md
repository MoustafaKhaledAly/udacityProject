# Deployment Project

## Table of Contents

* [Project Description](#ProjectDescription)
* [Usage](#Usage)
* [URLs](#URLs)
* [Setup](#Setup)
* [CircleCI](#CircleCI)



## Project Description

This project is is based on configuring a deployment pipeline on CircleCi to deploy on AWS S3 and AWS EB

## Usage

All the features that are implemented in this project work across modern environments.



## URLs 

Front-end point :http://udacityprojectbuckett.s3-website-us-east-1.amazonaws.com/home
Back-end point  :http://projectfinal-env.eba-93qzt3mj.us-east-1.elasticbeanstalk.com/


## Setup
1- clone the project from 'https://github.com/MoustafaKhaledAly/udacityProject'
2-Instal python ,AWS CLI and AWS EB CLI locally
2-Build and run the project using the commands in the config file inside the circleci folder

## CircleCI
The pipeline installs ,build and deploy the backend on AWS EB using circleci
The pipeline installs ,build and deploy the front-end on AWS S3 using circleci