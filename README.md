# Predicting Crime Rate in Chicago Using Facebook Prophet

## Project Overview

This project aims to predict the crime rate in the City of Chicago from 2001 to 2017 using Facebook's Prophet forecasting tool. By analyzing historical crime data, we seek to model and forecast future crime rates, providing valuable insights for law enforcement and public safety efforts.

### Dataset Summary

The dataset, obtained from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system, summarizes reported crimes in Chicago within the mentioned period. It includes details like incident identifiers, dates, locations, types of crimes, arrests made, and geographic coordinates, among others.

#### Columns in the Dataset:
- ID: Unique identifier for each record.
- Case Number: Unique incident number.
- Date: Date of the incident.
- Block: Incident location address.
- IUCR: Illinois Uniform Crime Reporting code.
- Primary Type: Main description of the crime.
- Description: Detailed crime description.
- Location Description: Incident location type.
- Arrest: Arrest made (Yes/No).
- Domestic: Domestic-related incident (Yes/No).
- Beat, District, Ward, Community Area: Law enforcement and municipal zoning details.
- FBI Code: FBI's crime classification.
- Coordinates (X, Y, Latitude, Longitude) and Location: Geographic details.
- Year: Year of the incident.
- Updated On: Record last updated date.

Data Source: [Crimes in Chicago Dataset on Kaggle](https://www.kaggle.com/currie32/crimes-in-chicago)

## Technologies Used

- Python 3.x
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Matplotlib & Seaborn: For data visualization.
- Facebook Prophet: For time series forecasting.
