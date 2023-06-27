# This project analyzes historical data from the NASA dataset on meteorite landings to identify high-probability zones for future meteorite impacts. It utilizes two clustering techniques: K-Means and density-based clustering.

The dataset is preprocessed to extract latitude and longitude coordinates for each meteorite landing. K-Means clustering is then applied to divide the data into clusters, optimizing the number of clusters using established methodologies.

Next, density-based clustering, specifically Mean Shift, is used to identify clusters based on data point density, without requiring a predefined number of clusters.

The resulting clusters are visualized on a scatter plot, revealing spatial patterns in meteorite landings. The cluster with the largest number of data points is considered the high-probability impact zone.

Geolocations within this cluster are saved in a CSV 'Impact_Zone' file, providing precise coordinates for further analysis. This information aids researchers in studying meteorite impacts, assessing potential risks, and planning targeted observation campaigns.

By combining K-Means and density-based clustering, this project provides insights into meteorite landing patterns, highlighting regions with a heightened likelihood of future meteorite impacts. It contributes to advancing meteorite impact research and understanding the distribution of these events on Earth.
