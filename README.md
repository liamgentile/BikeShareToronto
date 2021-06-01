# BikeShareToronto
A look into Bike Share Toronto Data between 2017 and 2020. 

I downloaded the data from Toronto Open Data. You can find it here: https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/

My process was as follows:

1. Collect the data. 
2. Aggregate quarterly and monthly data into year based DataFrames in Python. 
3. Clean the data. 
4. Format the yearly dataframes in order to aggregate the yearly DataFrames into a single long DataFrame including data from 2017-2020. 
5. Save the data to csv and import to Tableau. 
6. Analyze the data through creating a series of visuals in Tableau. 
7. Bring together some of the most insightful charts to make an interactive public Tableau dashboard.  

### See the interactive Tableau Dashboard here: https://public.tableau.com/app/profile/liam.gentile/viz/toronto_bikeshare_2017-2020/BikeShareDashboard

---------

### Files

Summary of Data Findings
- a brief written summary of some of the findings and recommendations after exploring the bike share data. 

toronto_bikeshare_data_aggregation.ipynb
- notebook in which I aggregated the quarterly and monthly bike share data into 4 yearly DataFrames. 

toronto_bikeshare_data_cleaning.ipynb
- notebook in which I cleaned the data in preparation for data analysis. 

toronto_bikeshare_final_data_aggregation.ipynb
- notebook in which I prepared the yearly DataFrames for aggregation into a single DataFrame and ultimately csv file for visual based analysis in Tableau. 
