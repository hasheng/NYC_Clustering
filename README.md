## NYC Neighborhood Clustering
### Midterm Project for Lighthouse Labs
by hasheng and iliketurtles83

### Datasets
- New York City neighborhood names, boroughs and geocodes.
- NYC rental prices by neighborhood.
- Lyft ride pickups by date and geocode.


### Feature Engineering / Additional Data
- For each neighborhood, we get nearby venue information via FourSquare API.
- For the Lyft rides, we count the number of pickups near each neighborhood.

### Modeling
- All combinations of venue information and lyft pickups are used as a training set (venues only, lyft only and both).
- Using Principal Component Analysis and KMeans clustering, we try to find relevant features and the optimal number of clusters.
- Rent prices data is used only for comparison.
