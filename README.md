# Londoncrimeanalysis
This project aims to identify the safest borough in London based on total crimes recorded between 2008 and 2016

## Background

London, the capital and largest city of England and the United Kingdom, is a global hub for arts, commerce, education, entertainment, fashion, finance, healthcare, media, professional services, research and development, tourism, and transportation. With its significant impact on various sectors, ensuring the security of London is paramount. As the most-visited city based on international arrivals and the busiest city airport system by passenger traffic, safety becomes a critical concern for both residents and visitors.

## Problem

Given London's significance on the global stage, maintaining a secure environment is essential. Certain parts of London experience higher crime rates, posing concerns for individuals relocating to the city for work and business. These individuals are often very conscious about selecting a safe area for residence. Additionally, local police can benefit from this analysis by focusing their efforts on controlling crime in areas that are major centers for criminal activities.

# Dataset 

This is the London LSOA 2008-2016 dataset available https://www.kaggle.com/datasets/jboysen/london-crime 

## Solution

This project aims to identify the safest borough in London based on total crimes recorded between 2008 and 2016. By analyzing crime statistics over this period, we provide valuable insights to help individuals make informed decisions about where to live. The analysis includes detailed exploration of major and minor crime categories, and identification of boroughs with the highest and lowest crime rates.

## Methodology

- Data Collection
Borough Data: Scraped from Wikipedia, containing information on London's boroughs.
Crime Data: Obtained from the London Datastore, containing detailed records of crimes from 2008 to 2016.
- Data Cleaning and Preparation
Irrelevant columns were removed from the borough dataset.
Columns were renamed for clarity.
The crime dataset was imported, and the 'value' column was renamed to 'num_of_crimes'.
Exploratory Data Analysis
- Major and Minor Crime Categories: We analyzed the count of crimes in major and minor categories, revealing that theft and handling are the most common crimes, followed by violence against the person.
Borough Analysis: Total crimes and crime rates were calculated for each borough. The top 5 boroughs with the highest and lowest crime totals were identified.
## Key Insights
* Total Crimes: Croydon, Bromley, Lambeth, Ealing, and Barnet are the top 5 boroughs with the highest total number of crimes.
* Crime Rates: Kensington and Chelsea, Hillingdon, and other boroughs show varying crime rates, providing a more accurate indicator of crime relative to population size.
* Yearly Trends: A line plot shows the total crimes per year, revealing trends and changes over time.
* Monthly Trends: Crime data by month shows variations in crime occurrence throughout the year.

## Visualizations
* Bar plots and pie charts were used to visualize the distribution of crimes across categories and boroughs.
* Line plots highlighted trends over the years and months.

# Conclusion

This analysis provides a comprehensive overview of crime in London from 2008 to 2016. It helps individuals and authorities understand crime distribution and trends, aiding in residence selection and crime control efforts. By focusing on the safest areas and understanding crime patterns, we can contribute to a safer London for everyone.


