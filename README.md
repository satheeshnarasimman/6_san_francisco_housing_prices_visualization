## week6_visualization_project
In this project, the San Francisco Real Estate market from 2010- 2016 is analyzed, the prices are further broken down by neighborhood and the realtionship between the various categories, viz., Sale price per square foot, Gross rent, Number of housing units sold and the Neighborhood are visualized as a parallel plot.

## Technologies and Libraries used
- Python
- Pandas
- Operating System
- Plotly
- Matplotlib
- Pandas hvplot
- Pathlib
- Dotenv

## Tools used
- Gitbash
- Jupyter lab
- Panel Dashboard
- Microsoft CSV
- Mapbox API
- Operating System: Windows-10, 64-Bit

## Data Given
- San Francisco real estate market from 2010- 2016 grouped by various neighborhoods, sale price per square foot, housing units sold and gross rent.
- Latitude and Longitude coordinates of San Francisco's neighborhoods.

## Notebooks created
- Rental Analysis
- Dashboard

## Metrics calculated
- Mean housing units
- Average gross rent per year
- Average sale price per year
- Average price per neighborhood
- Top 10 most expensive neighborhoods
- Mean values for each neighborhood

## Plots created
- Mean housing units per year
- Average gross rent per year
- Average sale price per year
- Average price/sq ft by neighborhood
- Top 10 most expensive neighborhoods
- Parallel Coordinates
- Parallel Categories
- Mapbox plot

## Functions defined
- housing_units_per_year()
- average_gross_rent()
- average_sales_price()
- average_price_by_neighborhood()
- top_most_expensive_neighborhoods()
- parallel_coordinates()
- parallel_categories()
- neighborhood_map()

## Dashboard plots
- Mapbox plot: Displays the gross rent by neighborhood
- Yearly trend: Row plots; shows the mean housing units per year, average gross rent per year and the average sale price per year
- Neighborhood plot: Column plot; depicts the average price/ sq ft. and the most expensive neighborhoods
- Parallel plot: Column plot; provides an understanding of how the different categories are related to each other

## Interpretation from the plots
### Yearly plot
- The number of housing units have steadily increased from 2010- 2016.
- The average gros rent has shot up from under 1500 USD in 2010 to almost 4500 in 2016.
- The average sale price/sq ft. experienced a slight drop in 2011 and then accelerated to 700 USD in 2016.

### Neighborhood plot
- Union Square District is the most expensive neighborhood followed by Merced Heights and Miraloma Park.

### Mapbox plot
- The style of the map is 'stamen- terrain'

### Parallel plots
- While Union Square might hold the top spot of the average price/ sq ft., Westwood Park has the most number of housing units sold and also the highest gross rent with 3959 USD.
- Among the Top 10 neighborhoods, South Beach has the lowest price/ sq ft., lowest number of housing units sold and the lowest gross rent.

## Conclusion
- If I was buying a property during the timeframe in consideration, I would have put my money in Westwood Park neighborhood, because the mean sale price was only 687 USD/sq ft., while the mean gross rent I could have earned by renting it out was 3959 USD per month.

## How to run the Dashboard
- Download the file to the local machine and run the following command on the Jupyter Lab terminal to view the interactive plot:
- "panel serve dashboard.ipynb --log-level debug --show"

## Contributors
- Satheesh Narasimman

## People who helped
- Khaled Karman, Bootcamp Tutor

## References
- https://plotly.com/python/plotly-express/

- https://plotly.com/python/builtin-colorscales/

- https://plotly.com/python/mapbox-layers/

- http://holoviews.org/user_guide/Customizing_Plots.html

- https://hvplot.holoviz.org/user_guide/Plotting.html