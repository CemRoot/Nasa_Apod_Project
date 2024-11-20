## Project Name: NASA APOD Data Retrieval and Iris Dataset Analysis

### Project Description
This project retrieves data from NASA's Astronomy Picture of the Day (APOD) API, stores the data in JSON format, and performs data processing and analysis on the Iris dataset. It combines API integration and fundamental data analysis with Python, including visualization and regression modeling.

### Table of Contents
1. [Project Overview](#project-overview)
2. [Installation Requirements](#installation-requirements)
3. [Setup and Configuration](#setup-and-configuration)
4. [Running the Project](#running-the-project)
5. [Project Structure](#project-structure)
6. [Key Notes](#key-notes)

### Project Overview
This project has two primary components:
- **NASA APOD API Data Retrieval**: Calls NASA's APOD API, retrieves data, and saves it in JSON format.
- **Iris Dataset Analysis**: Analyzes and visualizes the classic Iris dataset, including data processing and regression modeling.

### Installation Requirements
Make sure Python 3.x is installed. Install the necessary Python packages with:


pip install -r requirements.txt

Required Libraries:

	•	pandas
	•	numpy
	•	matplotlib
	•	seaborn
	•	requests
	•	os
	•	json
	•	dotenv(for loading environment variables)

Setup and Configuration

	1.	Clone or Download the Repository:
Clone the repository or download and extract the ZIP file:

git clone https://github.com/CemRoot/Nasa_Apod_Project


	2.	Set Up the API Key:
Obtain an API key from NASA’s API portal and configure it:
	•	Using Environment Variables:
	•	Windows:

set API_KEY="YOUR_API_KEY"


	•	macOS/Linux:

export API_KEY="YOUR_API_KEY"


	•	Using a .env File:
Create a .env file in the root directory and add:

API_KEY=YOUR_API_KEY



Running the Project

	1.	Execute the Jupyter Notebook to run the project:

jupyter notebook nasa_apod_analysis.ipynb


	2.	Follow the notebook instructions to:
	•	Retrieve APOD data.
	•	Analyze and visualize the Iris dataset.

Project Structure
```
project_folder/
├── data/
│   ├── iris.csv
│   ├── apod_data.json
│   ├── iris_corrected.csv
│   └── iris_scatter_with_regression.pdf
├── nasa_apod_analysis.ipynb
├── report.pdf
├── requirements.txt
└── README.md
```
Key Notes

	•	Ensure the API key is correctly set up before running API-related scripts.
	•	report.pdf contains a detailed analysis of the project, including visual outputs.
	•	The project includes robust error handling for API interactions to ensure user-friendly feedback if data retrieval issues arise.
	•	The Iris dataset analysis demonstrates regression modeling and data visualization techniques.
