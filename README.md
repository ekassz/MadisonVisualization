# MadisonVisualization
In my project, I focused on analyzing the relationship between population density and land use in Wisconsin's counties. Using geospatial data from a GeoJSON file and a SQLite database, I worked with data on various land use categories, such as developed areas and open water, and their impact on population distribution.

I utilized geospatial processing libraries like GeoPandas to read and merge spatial data, and Matplotlib for visualizing population densities across the state. To predict population, I built and compared two machine learning models: a linear regression model and a polynomial regression model. The linear model considered the relationship between land area and population, while the polynomial model captured more complex patterns by including higher-order terms.

I found that while the linear model had limited predictive power, the polynomial model showed a significantly better fit, explaining about 38.6% of the variance in population based on developed land area. This demonstrated that population distribution is influenced by more complex factors than just land area alone. The insights gained from this analysis could be valuable for urban planning and resource allocation in the state.

