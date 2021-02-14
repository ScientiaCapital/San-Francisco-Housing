# San Francisco Housing

In this challenge, your job is to use your data visualization superpowers, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

Instructions:  Use the san_francisco_housing.ipynb notebook to visualize and analyze the real-estate data.

Note that this assignment requires you to create a visualization by using the integration between Plotly and the Mapbox API. Be sure to create your environment file (.env) and include your Mapbox API access token. Then import your Mapbox API access token into the san_francisco_housing.ipynb notebook, and set it by using the px.set_mapbox_access_token function.

Additionally, you need to read the sfo_neighborhoods_census_data.csv file from the Resources folder into the notebook and create the DataFrame that you’ll use in the analysis.

The main task in this Challenge is to visualize and analyze the real-estate data in your Jupyter notebook. Use the san_francisco_housing.ipynb notebook to complete the following tasks:

     - Calculate and plot the housing units per year.
     - Calculate and plot the average prices per square foot.
     - Compare the average prices by neighborhood.
     - Build an interactive neighborhood map.
     - Compose your data story.
     
![San Francisco Housing](images/2021_image.jpg)

---

## Technologies


Before attempting to execute any _Python_ code in `san_francisco_housing.ipynb`, it is imperative that your development environment holds the following modules:

[pandas](https://pandas.pydata.org/pandas-docs/stable/) - Data analysis module.
[plotly.express](https://plotly.com/python/plotly-express/) - Graphing Libraries
[hvplot](https://hvplot.holoviz.org/getting_started/index.html) - High-level plotting API for PyData ecosystem built on HoloViews

---

## Installation Guide

With your _Python 3.7+_ environment, run the following commands via CLI:

```

pip install pandas
pip install plotly
pip install hvplot

```

## Usage

1. Clone repository onto your personal machine. 

2. Open _Jupyter Lab_ or _Jupyter Notebook_ via _Anaconda Navigator_ and navigate to the directory in which the file `san_francisco_housing.ipynb` is present. _All relevant code for this repository will be executed via Jupyter Notebook and no output will be printed to the command line_. Ensure that all relevant dependencies and _Python_ modules are installed (see __Technologies__ and __Installation Guide__ for more details) before attempting to execute code within _Jupyter Notebook_; otherwise, you will receive multiple interpreter errors! 

3. With the notebook open, start at the very first cell reading "Import the required libraries and dependencies" (a cell will be active when a rectangular border is surrounding the area in question). Run each cell in sequential order. _It is vital that all cells are ran in sequential order or your notebook will generate compiler errors_!. 

---

## Contributors

New development created by Scientia Capital. **Code from 'Uploaded Starter Files' commit originates from UC Berkeley Extension and I do not claim original ownership nor scholarship**.

---

## License

Software tool available for public use. 
