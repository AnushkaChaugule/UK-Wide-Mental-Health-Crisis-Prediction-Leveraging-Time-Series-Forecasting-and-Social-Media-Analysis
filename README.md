# UK-Wide-Mental-Health-Crisis-Prediction-Leveraging-Time-Series-Forecasting-and-Social-Media-Analysis

Project Description - 
This project presents a comprehensive predictive model designed to forecast nationwide mental health crises in the UK. It employs a dual-stream approach, integrating traditional time-series forecasting of historical suicide data with real-time sentiment analysis of social media discourse. The goal is to provide a valuable tool for policymakers and healthcare professionals to help implement proactive and timely interventions by providing early indications of potential increases in mental health issues.
Methodology - 
The project's methodology is a dual-stream framework that combines structured official suicide data with unstructured social media insights. Key steps include:
Data Collection: Historical suicide statistics were gathered from the Office for National Statistics (ONS), National Records of Scotland (NRS), and the Northern Ireland Statistics and Research Agency (NISRA). Unstructured text data was collected from the Reddit API.
Time-Series Modeling: Time-series models such as ARIMA, Prophet, and Long Short-Term Memory (LSTM) networks were used to analyze historical trends in the suicide data.
Natural Language Processing (NLP): NLP techniques were applied to social media data, specifically using RoBERTa for sentiment analysis and Latent Dirichlet Allocation (LDA) for topic modeling.
Model Integration: The processed social media data was integrated with the historical suicide data to create a unified dataset for a final predictive model.
Project Author
Anushka Balkrishna Chaugule, University of Birmingham.
How to Run the Project
Dependencies: Ensure you have all the necessary libraries installed. You can install them by running the following command in your terminal: pip install -r requirements.txt.
Data: The notebook requires several external data files, which are listed in the Data Sources section below. The original data was consolidated into a single file named UK_Suicide_cleaned.csv.
Execution: Open the Project.ipynb notebook in a Jupyter environment (JupyterLab, Jupyter Notebook, VS Code with the Jupyter extension, etc.) and run all the cells in sequence.
Data Sources - 
The project utilizes several datasets. The original data was sourced from:
The project utilizes several datasets. The original data was sourced from:
Office for National Statistics (ONS): Suicides in the United Kingdom: Reference Tables. Available at: https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/datasets/suicidesintheunitedkingdomreferencetables
National Records of Scotland (NRS): Probable Suicides: 2023 Edition. Available at: https://www.nrscotland.gov.uk/publications/probable-suicides-2023
Northern Ireland Statistics and Research Agency (NISRA):
VS1130 – Suicide and accidental deaths, 2005 to 2023. Available at: https://www.nisra.gov.uk/publications/vital-statistics-user-requested-data-tables
All areas – Population by sex and age bands (Mid-Year Population Estimates 2023). Available at: https://www.nisra.gov.uk/publications/2023-mid-year-population-estimates-northern-ireland-and-estimates-population-aged-85
Reddit API (for social media data)
