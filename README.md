# python-api-challenge
Module 6 Challenge
# Python API Challenge: Weather Analysis & Vacation Planning

## Overview
This project analyzes global weather patterns and plans ideal vacations using:
- Python's `requests` library
- OpenWeatherMap & Geoapify APIs
- JSON data processing
- Jupyter Notebook visualizations

## Project Structure

python-api-challenge/
├── WeatherPy/                   # Weather analysis module
│   ├── api_keys.py              # API key configuration (ignored by Git)
│   ├── WeatherPy.ipynb          # Jupyter notebook for weather analysis
│   └── output_data/             # Folder for generated plots (optional)
├── VacationPy/                  # Vacation planning module
│   ├── VacationPy.ipynb         # Jupyter notebook for vacation planning
│   └── hotel_data/              # Folder for generated hotel data (optional)
├── .gitignore                   # Specifies files to ignore (includes api_keys.py)
└── README.md                    # This file

## Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required packages:
  ```bash
  pandas matplotlib scipy requests citipy geoviews hvplot
  
  
## Installation
  1. Clone repo:
bash
git clone https://github.com/your-username/python-api-challenge.git
cd python-api-challenge
pip install -r requirements.txt

2. Get API keys:
-OpenWeatherMap
-Geoapify

3. Add keys to api_keys.py:
weather_api_key = "your_key_here"
geoapify_key = "your_key_here"