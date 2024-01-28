## Overview

The Health Management App is an innovative solution that leverages the power of AI to analyze food images and estimate their total calorie content. Utilizing the Google Gemini Pro Vision API, the app provides detailed information about each food item in an image, making it an essential tool for nutritionists, diet enthusiasts, and anyone interested in understanding their food intake better.

## Features

AI-Powered Image Analysis: Uses Google Gemini Pro Vision API to analyze food images.
Calorie Estimation: Provides an estimation of total calories in the uploaded food image.
Detailed Breakdown: Offers a detailed breakdown of each food item with its calorie content.
User-Friendly Interface: Easy-to-use interface, powered by Streamlit.

## How to Use

Enter a description or name of the food in the provided text input.
Upload an image of the food.
Click "Tell me the total calories" to get the analysis.

## Installation and Setup

To run the Health Management App locally, follow these steps:

## Prerequisites
Python 3.10 or later.
Google API key for Gemini Pro Vision API.

## Clone the Repository:
 ```
git clone https://github.com/shivakumar0002/Health-App.git

 ```
## Navigate to the Project Directory:
 ```
cd Health-App

 ```
## Install required packages::
 ```
pip install -r requirements.txt
 ```
## Set up environment variables:
Create a .env file in the project root.
Add your Google API key: GOOGLE_API_KEY=your_api_key_here.

## Run the Application:
 ```
streamlit run your_app_file.py

 ```
## Contributing

Contributions to improve the Health Management App are welcome. Feel free to fork the project, make changes, and submit a pull request.
