🏥 SDOH Predictor & Community Resource Mapper
This project was developed for the 2024 Community Companion Challenge and aims to identify Social Determinants of Health (SDOH) deficiencies based on minimal input (like ZIP code), and recommend local support services such as food, transport, and healthcare facilities.

🚀 Project Overview
The system performs:

SDOH Flagging: Converts census and demographic data into quantile-based SDOH risk flags.

Classification: Trains a Random Forest classifier to predict community-level SDOH deficiencies based on regional indicators like business ratios, residence ratios, and demographics.

Resource Mapping: Uses Selenium web scraping to collect support resource data (e.g., hospitals, food centers, pharmacies), enabling action-driven recommendations.

📊 Key Features
Achieved 76% accuracy in SDOH deficiency prediction using tabular classification.

Supports early insight generation using zipcode-based inputs only.

Provides sample web-scraping implementation for community support databases (currently includes 3 ZIP codes).

Sample resource data stored in sample_data/resources.csv.
