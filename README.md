Project: 

This analysis explores price and cost differences in different regions for drugs and procedures (inpatient and outpatient) 
covered under Medicare in 2014.

Specifically, I looked at price and cost differences for the top 10 most frequently completed procedures and prescribed drugs 
in the top 10 regions with the most overall procedures and drug prescriptions. 

The visualizations focus on a comparison of total cost between the most expensive and cheapest regions for each of the top 10 prescribed
and completed drugs/procedures by volume. 
 
I also included the total volume of prescription claims and number of discharges, which are depicted as line graphs, to include
volume, a potential determinant of price/cost.

The analysis was done by querying the public Medicare Dataset available on Google BigQuery. 

Prerequisites: 

pandas library (data structure and analysis tools):

install pandas library 

googlebigquery (data source): 

'from pandas.io import gbq' (to allow for query results to be stored as a dataframe)

plotly (visualizations library): 

install plotly

to view plotly charts: 

https://nbviewer.jupyter.org/github/daveyko/Medicare_Disparity_Analysis/blob/branch1/google_bigquery.ipynb


