# Crop Production Analysis in India

### Problem Statement

The Agriculture business domain, as a vital part of the overall supply chain, is expected to highly evolve in the upcoming years via the developments, which are taking place on the side of the Future Internet. This paper presents a novel Business-to-Business collaboration platform from the agri-food sector perspective, which aims to facilitate the collaboration of numerous stakeholders belonging to associated business domains, in an effective and flexible manner. This dataset provides a huge amount of information on crop production in India ranging from several years. Based on the Information the ultimate goal would be to predict crop production and find important insights highlighting key indicators and metrics that influence crop production.


### About Dataset
Description:
This dataset encompasses agricultural data for multiple crops cultivated across various states in India from the year 1997 till 2015. The dataset provides crucial features related to crop yield prediction, including crop types, crop years, cropping seasons, states, district name, areas under cultivation, and production quantities.
The dataset is presented in tabular form, with each row representing data for a specific crop and its corresponding features. It has 246091 rows and 7 columns.

### Key Features:

* State_Name: The Indian state where the crop was cultivated.
* District_Name : Name of the District.
* Crop_Year: The year in which the crop was grown.
* Season: The specific cropping season (e.g., Kharif, Rabi, Whole Year).
* Crop: The name of the crop cultivated.
* Area: The total land area (in hectares) under cultivation for the specific crop.
* Production: The quantity of crop production (in metric tons).

### Approach
The main goal of the project is to find key metrics and factors and then show meaningful relationships between them based on different features available in the dataset.

Data Collection : Imported data from various datasets available in the project using Pandas library.

Data Cleaning : Removed missing values and created new features as per insights.

Data Preprocessing : Modified the structure of data in order to make it more understandable and suitable and convenient for statistical analysis.

Data Analysis : I started analyzing dataset using Pandas,Numpy,Matplotlib and Seaborn.

Data Visualization : Plotted graphs to get insights about dependent and independent variables.


To solve the problem, the dataframe was divided based on zones such as 
    'Union Terr', 'South Zone', 'North East Zone', 'East Zone', 'Central Zone', 'West Zone', 'North Zone'
Again this zone is divided based on 'State' and 'District'
