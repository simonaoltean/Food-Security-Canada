# Food Security Canada Dashboard

## Overview
In this dashboard, I've used the CSV raw data from the [Canadian Open Government website](https://open.canada.ca/data/en/dataset/9bcb8daa-a528-47d1-a54e-b2b16d78119f) on food security among the canadian population by demographic characteristics such as age, gender, and ethnicity. The dashboard includes histograms based on the sum of number of people in the different levels of food securiy between 2018 and 2021.
The different food security levels include:
- Food secure
- Food insecure, severe
- Food insecure, moderate or severe
- Food insecure moderate
- Food insecure, marginal
- Food insecure

Two types of histograms are features for each category of demographic characteristics, the first one being a stacked sum of the number of people for each demographic characteristic, differentiated by food security status with different colors. The second type of bar plot is instead a 100% stacked bar chart with the total number of people in each demographic equated to 100% with different colours still representing the various food security levels. For the first type of chart, the demographic characteristics (the x axis labels) are ranked by the total number of people in that category. In the 100% stacked bar charts, the demographic characteristics are ranked by the percentage of food secure people from highest to lowest. All the charts are created within the [Jupyter notebook](https://github.com/simonaoltean/Food-Security-Canada-Dashboard/blob/main/food_security_canada.ipynb) and written into [JSON](https://www.json.org/json-en.html) files.

## Deployment
To access this dashboard, simply click on this [link](https://simonaoltean.github.io/Food-Security-Canada-Dashboard/) which will lead you to the deployment page of this Github repository. The charts are made using [Plotly](https://plotly.com/) which makes them interactive and the viewer can hover over the data and get the number of people (or the percentage) for each level of food security.

Technologies used: 
- Pandas
- Plotly
- Matplotlib
- Numpy
