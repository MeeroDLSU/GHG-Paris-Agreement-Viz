# Greenhouse Gas Emissions Visualization

This repository contains Group 7’s Final Project for DATA101, which is a Dash web application made in Python that visualizes greenhouse gas (GHG) emissions data using interactive charts and maps. The application allows users to explore trends in GHG emissions, compare emissions between countries, and analyze the impact of emissions on global climate change.


### Installation

1. Clone this repository to your local machine:
 ```
 git clone https://github.com/MeeroDLSU/GHG-Paris-Agreement-Viz/
 ```
2. Install the required Python packages using pip:

```
pip install dash
pip install pandas
pip install geopandas 
pip install plotly.express
pip install dash_bootstrap_components
   ```

## Running the Application

To run the Dash application, follow these steps:

1. Set your Mapbox access token:

   Open the `.mapbox_token` file and replace its content with your own Mapbox access token.

2. Load and Prepare Data:

   - Make sure you have the necessary data files (“datasetss” folder, `GHGperGas_Cleaned.xlsx`, ‘GeoSpatialInExcel.xlsx’,‘`ne_10m_admin_0_countries.shp`) in the appropriate directory.

3. Run the Application:

   ```
   python final.py
   ```

4. Open a web browser and go to http://127.0.0.1:8050/ to access the application.

## Usage

1. **Line Chart**: The line chart displays the trend of total GHG emissions per country over time. Use the dropdown to select specific countries for comparison.

2. **Diverging Bar Chart**: This chart shows the top 5 countries with the highest positive and negative changes in emissions. Positive values indicate an increase, while negative values indicate a decrease in emissions.

3. **Choropleth Map**: The map visualizes total GHG emissions per country using color gradients. Use the year slider to select the year you want to visualize.

4. **Stacked Bar Chart**: Click on a country in the choropleth map to display a stacked bar chart showing the composition of different greenhouse gasses for that country.


