# EV_EDA
In the provided Colab notebook, I performed exploratory data analysis (EDA) on the Electric Vehicle Data (1997-2024) dataset obtained from the Washington State Department of Licensing (DOL). Here's a summary of the analysis conducted:

1. Data Loading and Overview:
   - Imported the necessary libraries and downloaded the dataset using the `opendatasets` package.
   - Loaded the dataset into a Pandas DataFrame and inspected the first few rows, columns, and data types.

2. Description of Columns:
   - Described the meaning and significance of each column in the dataset, such as model year, make, model, electric vehicle type, CAFV eligibility, electric range, base MSRP, legislative district, DOL vehicle ID, electric utility, and geographical coordinates.

3. Exploratory Analysis and Visualization:
   - Analyzed the adoption of electric vehicles across different cities present in the dataset:
     - Extracted unique city names and determined the count of electric vehicles in each city.
     - Plotted a bar chart to visualize the adoption of electric vehicles in the top 10 cities with the highest count.
     - Created a density plot to show the distribution of electric vehicle counts across all cities.
     - Identified cities with more than 1000 electric vehicles and plotted their distribution separately.
     - Also examined the distribution of cities with only one electric vehicle.

   - Explored the top electric vehicle brands in the dataset:
     - Calculated the count of vehicles associated with each brand.
     - Plotted a bar chart to visualize the count of electric vehicles for the top 10 brands.

   - Analyzed the electric vehicle adoption trends by year:
     - Determined the number of electric vehicles registered in each model year.
     - Created a line plot to visualize the adoption trends over the years.

   - Examined the distribution of electric vehicle types adopted by the market:
     - Counted the occurrences of battery electric vehicles (BEVs) and plug-in hybrid electric vehicles (PHEVs).
     - Visualized the distribution using a pie chart.

   - Explored the Clean Alternative Fuel Vehicle (CAFV) eligibility distribution:
     - Counted the occurrences of different CAFV eligibility categories.
     - Visualized the distribution using a pie chart.

   - Analyzed the electric range of electric vehicles:
     - Calculated the maximum, minimum, and average electric range of vehicles in the dataset.
     - Aggregated electric range statistics by city.

   - Explored the geographical distribution of electric vehicles:
     - Plotted a scatter plot of latitude and longitude coordinates using the `seaborn` library.
     - Utilized the `folium` library to create interactive maps:
       - Plotted individual cities with markers on a map.
       - Generated a heat map to visualize the density of electric vehicles in specific areas.

The provided Colab notebook demonstrates various aspects of exploratory data analysis on the Electric Vehicle Data (1997-2024) dataset, providing insights into electric vehicle adoption trends, brand popularity, vehicle types, CAFV eligibility, electric range, and geographical distribution. The analysis contributes to a better understanding of the dataset and enables further exploration and decision-making based on the findings.
