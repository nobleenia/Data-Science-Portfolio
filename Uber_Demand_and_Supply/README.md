# Uber Taxi Demand and Supply Gap Analysis

## Overview
This project aims to analyze the demand and supply gap for Uber taxi services based on a provided dataset. We explore various aspects, including time-based demand, pickup locations, ride availability, and cancellations. The analysis is conducted to gain insights into the challenges faced by Uber in meeting customer demand and optimizing service provision.

## Getting Started
### Prerequisites
To run the code and analysis in this project, you need to have the following software installed:  

Python (3.7 or higher)  
Jupyter Notebook  
Required Python packages (see requirements.txt)  
Installation  
Clone the repository:  
```git clone https://github.com/nobleenia/uber-demand-analysis.git```  

Navigate to the project directory:
```cd uber-demand-analysis```  

Install the required Python packages:
Open and run the Jupyter Notebook to execute the analysis and generate visualizations.

## Data Cleaning and Preparation
Before conducting the analysis, the dataset is cleaned and prepared. This includes converting date and time columns to datetime format, categorizing pickup times, and creating columns for demand, supply, and the demand-supply gap.

## Analysis of Dataset
### Problem Identification
The first step in the analysis involves identifying the frequency of different request statuses, including "Trip Completed," "No Cars Available," and "Cancelled."

### Analysis Based on Availability
This section examines the availability of Uber rides based on pickup locations (Airport or City).

### Analysis Based on Cancelled Requests
The analysis further investigates cancelled ride requests based on their pickup locations (Airport or City).

### Analysis Based on Pickup Time
The time of day is categorized, and the analysis is performed to understand the distribution of ride requests, unavailability, and cancellations.

### Demand and Supply Analysis
This section calculates the demand, supply, and the demand-supply gap for different time categories, providing insights into service optimization.

## Conclusion
In the conclusion section, the key findings and insights from the analysis are summarized, helping to understand the challenges and opportunities in the Uber taxi service.

## Contributing
If you want to contribute to this project, feel free to open issues or submit pull requests. Your contributions are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.