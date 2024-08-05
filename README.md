# Visualization of Traffic Accident Hot Spots on a Map

In this project, I aimed to achieve two primary goals: 1) identify hot spots of traffic accidents by mapping locations using Folium and 2) create interactive data visualizations using Dash and Plotly for a detailed analysis of the yearly, monthly, daily, and hourly occurrences of traffic accidents.

The map, powered by Folium, displays accident hot spots within the city by incorporating latitude and longitude information. Clicking on a specific area allows users to zoom in on the street, providing a detailed view of the exact locations that frequently experience accidents.

I executed the code in Databricks Community Edition.

*Project Files:

1. sampling_splitting_file.ipynb: This file extracts a subset of data from the original US traffic accidents dataset, reducing its size by randomly shuffling and selecting only 1,000,000 rows.
2. dash_and_folium.ipynb: This file includes all the code and outputs.

*Original Dataset Link: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

Note: Due to file size limitations, the outputs may not render directly. Please refer to the following nbviewer link to interact with the map:
https://nbviewer.org/github/Su-Jung-Choi/traffic_accident_hot_spots/blob/main/dash_and_folium.ipynb


Additionally, the outputs of plotly graphs are in the following:

![monthly_accident](https://github.com/Su-Jung-Choi/traffic_accident_hot_spots/assets/88897881/c52a2247-25d9-4c89-8c56-9761b734ac08)

![daily_accident](https://github.com/Su-Jung-Choi/traffic_accident_hot_spots/assets/88897881/b1167ac3-8431-43e6-9770-3ebc81bbb5ec)

![hourly_accident](https://github.com/Su-Jung-Choi/traffic_accident_hot_spots/assets/88897881/979a88db-e4c2-4b13-975d-ca713085ab4a)

![day_of_month_accident](https://github.com/Su-Jung-Choi/traffic_accident_hot_spots/assets/88897881/718447da-a6e2-42d7-8f87-64fa9f235594)
