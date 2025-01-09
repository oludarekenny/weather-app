# 30 Days DevOps Challenge - Weather Display Application
## Day 1: Building a weather data collection system using AWS S3 and OpenWeather API

This project is a Weather information Collection application that fetches, stores, and manages real-time weather data.

## Features
Real-Time Weather Data Collection: Fetches up-to-date weather information for multiple cities worldwide.
Detailed Weather Insights: Displays temperature (°F), humidity levels, and current weather conditions.
Cloud Storage Integration: Automatically saves weather data to AWS S3 for secure and scalable storage.


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

