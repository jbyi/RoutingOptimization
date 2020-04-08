# brightwalkinsight
- Created and deployed a Flask-based web application routing safe walking paths using Heroku
- Wrangled Boston streetlight, crime, accident and OpenStreetMap sidewalk datasets using the GeoPandas
package based on geographical adjacency, and assigned safety weights to the 25k sidewalk segments
- Formulated the safety weights as a function of streetlight, crime, and accident factors and optimized them
using Monte Carlo simulation
- Parallelized the data wrangling process using a python multiprocessing package in Google Cloud Platform
and reduced the processing time by a factor of 32
- Applied Dijkstra’s algorithm using the NetworkX and optimized the routing in terms of safety, achieved
30% increased streetlight density, 60% lower accident rate, and 90% lower crime rate compared to the
fastest route
