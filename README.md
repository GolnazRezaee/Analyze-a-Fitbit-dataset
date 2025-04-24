# Healthcare Information Systems - Fitbit Dataset Analysis

## Overview
This project involves analyzing a Fitbit dataset to provide insights into healthcare information systems. The dataset includes various participant data such as exercise, sleep patterns, heart rate, calories, steps, and distance. The goal of this project is to design and implement an Entity-Relationship (ER) schema, perform ETL (Extract, Transform, Load) operations, and create a dashboard with useful visualizations and insights.

## Project Requirements
The project consists of the following tasks:

1. **ER Schema Design**  
   Design an ER schema for storing the Fitbit data, including:
   - **Partecipant**: Data from `participant-overview.xlsx`
   - **Exercise**: Data from `fitbit/exercise.json`
   - **Sleep**: Data from `fitbit/sleep.json`
   - **Sleep Scores**: Data from `fitbit/sleep_score.csv`

   Additionally, two more datasets from the following options:
   - **BPM**: Heart rate data from `fitbit/heart_rate.json`
   - **Calories**: Calorie consumption data from `fitbit/calories.json`
   - **Steps**: Step count data from `fitbit/steps.json`
   - **Distance**: Distance data from `fitbit/distance.json`

2. **ORM Implementation**  
   Implement the ER schema using Object-Relational Mapping (ORM) to interact with the database.

3. **ETL Functions**  
   Create functions to load the data for each participant on a daily basis, ensuring that the data is imported if it hasn’t already been loaded.

4. **Data Loading**  
   Load data for at least 5 participants into the database using the functions developed.

5. **DFM Design**  
   Design a Data Fact Model (DFM) based on the ER schema, incorporating facts and dimensions.

6. **Fact Table Creation**  
   Implement the fact table for the DFM using ORM.

7. **ETL for Fact Table**  
   Implement ETL functions to populate the fact table with relevant data.

8. **Pivot Table Generation**  
   Create a pivot table based on the fact table for data analysis.

9. **Dashboard Implementation**  
   Design and implement a dashboard that provides insights into the Fitbit data.

## Data Sources
The dataset is provided by [Simula Research Laboratory](https://datasets.simula.no/pmdata/), and it contains multiple JSON, CSV, and XLSX files related to Fitbit data for various participants.

## Tools and Technologies
- **Python**: Programming language used for data analysis and processing.
- **ORM**: Object-Relational Mapping for database interaction.
- **ETL**: Extract, Transform, Load processes for data ingestion.
- **Pandas**: Library for data manipulation and analysis.
- **Matplotlib/Seaborn**: Libraries for data visualization and dashboard creation.
- **SQLAlchemy**: ORM library for Python to interact with relational databases.

## Setup
1. Clone this repository:
   ```bash
   git clone <repository_url>

# install the required dependencies
2. pip install -r requirements.txt

# 3.Download the dataset from Simula Research Laboratory and place the files in the appropriate directory.

# 4.Run the data loading and analysis scripts:
python load_data.py

# 5.Access the dashboard at http://localhost:5000.

# This project is licensed under the MIT License - see the LICENSE file for details.
This template covers the key points of your project, including the ER schema design, ORM implementation, ETL functions, and dashboard creation. You can adjust the details and code instructions based on the specific steps you follow in your project. Let me know if you need any modifications!


