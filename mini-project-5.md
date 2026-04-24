# Mini Project 5: Geospatial Analysis of Movement

## Hypothesis
Professor Wirfs-Brock spent most of her time near Whitman College during her visit.

## Data Processing
I calculated the distance between each recorded location and Whitman College using the haversine formula. 
I then created a new variable ('near_whitman') to classify whether each point was within 1 km of campus.

## Visualization 1: Map of Locations
<iframe src="" width="100%" height="500"></iframe>

### Interpretation
This map shows Professor Wirfs-Brock’s recorded locations, with points colored based on whether they are near Whitman College.

## Visualization 2: Distribution of Locations
![Bar Chart](bar_chart.png)

### Interpretation
The bar chart shows the number of location points that are near Whitman College compared to those that are farther away. 
There are more points near Whitman than far from it, suggesting that Professor Wirfs-Brock spent most of her time around the campus area.
