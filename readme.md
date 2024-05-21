# COVID-19 Countrywise Data Analysis

This project fetches COVID-19 data for selected countries from the [disease.sh API](https://disease.sh/docs/#/COVID-19%3A%20Worldometers/get_v3_covid_19_countries) and performs data analysis using PySpark DataFrame. Additionally, it exposes an API using Flask to display the analyzed data.

## Overview

The project consists of the following main components:

1. **Data Fetching**: Utilizes the disease.sh API to fetch COVID-19 data for 20 countries.

2. **Data Processing**: Processes the fetched data using PySpark DataFrame to perform required operations such as filtering, aggregation, and transformation.

3. **API Development**: Develops a Flask application to create a development server and expose APIs to display the analyzed data.

4. **Data Visualization**: Presents the analyzed data through API endpoints in JSON format for visualization or further consumption.

Absolutely, here's the updated content for your GitHub README file in Markdown format:



## API Endpoints

This Flask application exposes several API endpoints that return COVID-19 data in JSON format. To access these endpoints, make HTTP GET requests to the following URLs after running the application:

**COVID-19 Data**

http://localhost:5000/covid-data

**Most Affected Country**

http://localhost:5000/most-affected-country

**Least Affected Country**

http://localhost:5000/least-affected-country

**Country with Highest Cases**

http://localhost:5000/country-with-highest-cases

**Country with Minimum Cases**

http://localhost:5000/country-with-minimum-cases

**Total Cases**

http://localhost:5000/total-cases

**Most Efficient Country** 

http://localhost:5000/most-efficient-country

**Least Efficient Country**

http://localhost:5000/least-efficient-country

**Least Suffering Country**

http://localhost:5000/least-suffering-country

**Still Suffering Country** 

http://localhost:5000/still-suffering-country

**Important Note:**

Replace localhost:5000 with the actual IP address or hostname of your server if it's different.



## How to Use

To run the project locally, follow these steps:

```bash
# Clone the repository:
git clone <repository-url>

# Navigate to the project directory:
cd <project-directory>

# Install the required packages using pip:
pip install -r requirements.txt

# Run the Flask application:
python src/covid_api.py

# Run the Main application:
python main.py
```

