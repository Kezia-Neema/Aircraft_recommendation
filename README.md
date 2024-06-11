# Tableau Dashboard
    - [Click Here](https://public.tableau.com/app/profile/kezia.neema/viz/Aircraft_accidents_analysis/Aircraftaccidentdash?publish=yes)

# Overview
To address the business problem of identifying the lowest risk aircraft for the company's new aviation division, we will perform a comprehensive analysis of the aviation accident data provided by the National Transportation Safety Board (NTSB). Here's a detailed outline of our approach, including the deliverables and the insights we aim to derive.

Project Outline
1. **Data Exploration and Preparation**
    - Data Loading: Load the dataset and explore its structure, including the range of years, types of aircraft, and nature of incidents.
    - Data Cleaning: Handle missing values appropriately (e.g., imputation, removal) and ensure data consistency.
    - Data Transformation: Aggregate data by aircraft model, manufacturer, and other relevant attributes to facilitate analysis.

2. **Risk Assessment Analysis**
    - Accident Frequency: Calculate the number of accidents per aircraft model and manufacturer.
    - Severity of Accidents: Evaluate the severity of accidents (fatalities, injuries, damages) and categorize them.
    - Incident Types: Analyze common causes of incidents and accidents to identify patterns or frequent issues.

3. **Data Visualization and Insights**
    - Interactive Dashboard: Create an interactive dashboard using a tool like Plotly Dash or Power BI, allowing users to explore accident data by aircraft model, year, manufacturer, and other filters.
    - Visualizations:
        - Bar charts showing accident frequency by aircraft model and manufacturer.
        - Line graphs depicting trends in accident rates over time.
        - Heatmaps or bubble charts illustrating the severity and types of incidents.
4. Business Recommendations
    - Based on the analysis, we will formulate three concrete business recommendations for the head of the new aviation division




## Business Understanding
In an effort to diversify its holdings, the business is entering the aviation sector with the goal of buying and managing aircraft for both public and private companies. Entering this strictly regulated and safety-sensitive sector, however, carries a considerable chance of mishaps and mishaps.

The business must carefully evaluate and reduce these risks by choosing aircraft models that have been shown to be dependable and safe in order to guarantee a successful entry. In order to find trends, comprehend recurring causes of mishaps, and ascertain which aircraft type and manufacturers have the best safety records, this entails studying historical data on aviation accidents.

The business may reduce possible risks, guarantee passenger safety, and establish a respectable and prosperous aviation segment by making data-driven decisions. 

By giving the head of the new aviation business practical advice and insights on which aircraft to buy, the company hopes to establish itself as a leader in the aviation industry for the long run.

## Data Understanding
We are working with data from [Kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) which contains information from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters.

The data is contained in a csv file:
- AviationData.csv: Each record represents an accident with details about the accident