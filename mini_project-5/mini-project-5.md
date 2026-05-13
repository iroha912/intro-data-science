# Mini Project 5: Geospatial Analysis of Movement

## Hypothesis
Professor Wirfs-Brock spent most of her time near Whitman College during her visit.

## Data Processing
calculated the distance between each recorded location and Whitman College using the haversine formula, which accounts for the curvature of the Earth.
Based on this distance, I created a new variable called “near_whitman”, which classifies each location as either within 1 km of campus or farther away. 
This allowed me to clearly compare time spent near versus far from Whitman.

## Visualization 1: Map of Locations
This map displays all recorded locations, with points colored based on whether they fall within 1 km of Whitman College.
<iframe src="map.html" width="100%" height="500"></iframe>

### Interpretation
While many points fall within the “near Whitman” category, there is a noticeable clustering of points around the downtown area, particularly near the Marcus Whitman Hotel, rather than directly on campus. In addition, several points appear along roads connecting these areas, suggesting movement between locations.

This pattern may indicate that Professor Wirfs-Brock was staying near the Marcus Whitman Hotel, using it as a central location during her visit. From there, she appears to have moved between downtown and the Whitman College campus.

## Visualization 2: Distribution of Locations
This bar chart compares the number of location points classified as “near Whitman” versus “far from Whitman.”
<iframe src="bar_chart.html" width="100%" height="500"></iframe>

### Interpretation
We can see that there are substantially more points near Whitman, with the count being nearly twice as large as those farther away. This suggests that a significant portion of Professor Wirfs-Brock’s recorded locations fall within the 1 km radius of campus.

## Conclusion
Overall, the data suggests that Professor Wirfs-Brock spent most of her time within 1 km of Whitman College, as there are nearly twice as many location points classified as “near Whitman” compared to those farther away. However, the map shows that many of these “near Whitman” points are actually concentrated in the downtown area, particularly around the Marcus Whitman Hotel, rather than directly on campus.
This indicates that while the hypothesis is supported in a general sense, the “near Whitman” category includes multiple distinct locations, and does not necessarily mean that most time was spent on campus.
