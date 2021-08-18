# AgriTech---USGS-LIDAR-Challenge
week 6 challenge@10 academy
<h1>Overview</h1>
<b>Business Need</b>
At AgriTech, we are very interested in how water flows through a maize farm field. This knowledge will help us improve our research on new agricultural products being tested on farms.

How much maize a field produces is very spatially variable. Even if the same farming practices, seeds and fertilizer are applied exactly the same by machinery over a field, there can be a very large harvest at one corner and a low harvest at another corner.  We would like to be able to better understand which parts of the farm are likely to produce more or less maize, so that if we try a new fertilizer on part of this farm, we have more confidence that any differences in the maize harvest 9are due mostly to the new fertilizer changes, and not just random effects due to other environmental factors.  
Water is very important for crop growth and health.  We can better predict maize harvest if we better understand how water flows through a field, and which parts are likely to be flooded or too dry. One important ingredient to understanding water flow in a field is by measuring the elevation of the field at many points. The USGS recently released high resolution elevation data as a lidar point cloud called USGS 3DEP in a public dataset on Amazon. This dataset is essential to build models of water flow and predict plant health and maize harvest. 

<h1>FINDINGS:</h1>

You work at an AgriTech, which has a mix of domain experts, data scientists, data engineers. As part of the data engineering team, you are tasked to produce an easy to use, reliable and well designed python module that domain experts and data scientists can use to fetch, visualise, and transform publicly available satellite and LIDAR data. In particular, your code should interface with USGS 3DEP and fetch data using their API.
<b>Task 1 - Data Fetching and Loading<b/>
LIDAR high definition elevation data - USGS 3DEP - The USGS recently released high resolution elevation data as a lidar point cloud in a public dataset on Amazon. This dataset is complicated to understand and use, and it would be useful to have an easy way to access and use it in order to build models of water flow and predict plant health and maize harvest. 

Your task is to write a modular python code/package to connect to the API, query the data model to select with  a specified input and get a desired output. For example, submit a boundary (GPS coordinates polygon) and receive back a raster of the height of the terrain within the boundary. 

<b>Task 2 - Terrain Visualization</b>
	
Include an option to graphically display the returned elevation files as either a 3D render plot or as a heatmap. The following is an example visualisation.

<b>task 3 - Data Transformation </b>

Topographic wetness index (TWI) - as an additional column returned with geopandas dataframe

<h1>Expected Outcomes</h1>
Any industry working with satellite, or agriculture would likely be impressed to see a project like this on a portfolio.

<b>Skills:</b>
Working with satellite imagery as well as geographical data files
Exposure to building API that interacts with satellite imagery
Code packaging and modularity
Building data pipelines and orchestrations workflows


<b>Knowledge:</b>
Satellite and geographical Image processing 
Functional and Modular Coding
API access to Big Data

<h1> useful links </h1>
https://www.earthdatascience.org/courses/use-data-open-source-python/data-stories/what-is-lidar-data/explore-lidar-point-clouds-plasio/
https://towardsdatascience.com/how-to-automate-lidar-point-cloud-processing-with-python-a027454a536c
https://pdal.io/tutorial/iowa-entwine.html
	https://aws.amazon.com/blogs/machine-learning/extracting-buildings-and-roads-from-aws-open-data-using-amazon-sagemaker/
