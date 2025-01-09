# 30 Days DevOps Challenge - Weather Display Application
## Day 1: Building a weather data collection system using AWS S3 and OpenWeather API

This project is a Weather Data Collection System designed to fetch, store, and manage real-time weather data.

## Features
-Real-Time Weather Data Collection: Fetches up-to-date weather information for multiple cities worldwide.
-Detailed Weather Insights: Displays temperature (°F), humidity levels, and current weather conditions.
-Cloud Storage Integration: Automatically saves weather data to AWS S3 for secure and scalable storage.


## Technical Architecture
-Language: Python 3.x 

-Cloud Provider: AWS (S3) 

-External API: OpenWeather API 

Core Dependencies:
-boto3 – AWS SDK for Python

-python-dotenv – Secure environment variable management

-requests – Simplified HTTP requests for API integration

##Project Structure
weather-dashboard/
  src/
    __init__.py
    weather_dashboard.py
  tests/
  data/
  .env
  .gitignore
  requirements.txt


# Setup Instructions
## Clone the repository

Initially i could have cloned the repository but i wanted to recreate and do it all myself. Create all the files that are within the Project Structure. Then insert the required infomation in each file

### Create a Virtual Environment

Before you install it's important you create a virtual environment for python. This wont install as the package is being handled externally. This could simply be Apt. So make sure to isolate the environment and install it within there. To do this:

To create a virtual environment python3 -m venv (your virtual environment name)

Then you have to activate the virtual environment source envname/bin/activate 

### Install dependencies

pip install -r requirements.txt

Configure environment variables (.env)

CopyOPENWEATHER_API_KEY=your_api_key
AWS_BUCKET_NAME=your_bucket_name
Configure AWS credentials

Use aws configure to connect to the CLI

### Run the application:

 python src/weather_dashboard.py

image
