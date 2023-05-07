# Danger zone: exploring associations among crime and urban characteristics in Chicago 

This project was done as a seminar work for "Seminar Geodata Analysis and Modelling" at the Institute of Geography, University of Bern.

# Purposes of research
  - &#9745; Collect and pre-process relevant dataset in Chicago.   
  - &#9745; Implement the algorithmic logics (Twinam, 2017) .  
  - &#9745; Explore the association among crime and other characteristics in Chicago.  

# Methods and datasets
- Algorithms and implements:   
  - &#9745; Self-built 'Module' and 'Function' in python   
  - &#9745; Spatial characteristics (e.g. Points in Circle, Points in Polygon, Spatial index, etc.)    
  - &#9745; Correlation analysis    

  This project use python to finish analysis process. First of all, I build up the module for accelerated processing interaction points in streets' networks. As for process part, this part is relying on the 'json', 'math', 'Shapely', 'Numpy' packages. In the end, for analyses part, relying on the 'Pandas', 'Numpy', 'Geopandas', 'matplotlib', 'time' packages.  

- Datasets:
  - &#9745; Crime dataset from 2001 to 2018 in Chicago  
  - &#9745; Commerical land use (e.g. restaurants and shops) from OpenStreetMap  
  - &#9745; Street weights (i.e. the combination between density and class) from Chicago  
  - &#9745; Population density of 2018 from Chicago  
  
# Results
![image](https://user-images.githubusercontent.com/43073850/236676978-d66878d0-c592-4e85-a157-6d2614346b24.png)  
As this figure shows, the association between 'street weight' and 'number of commerical land use' is around 0.26. For others, there is not clear association.

# Limitations and Outlook
  - Although I have extracted corresponding characteristics, I cannot ensure they represents the content in suitable scales. If not, there is modifiable areal unit problem existing. 
  - I didn't consider to the interaction among these variables and their causalities. If possible, we can introduce the instrumental variable to check. 
  - From temporal perspective, there is no histotrical dataset like the Twinam (2017), which means that this project is lacking of sensitivity analysis. 

# Contact
  Name: Haokun Liu  
  Email: haokun.liu@students.unibe.ch

# Reference
Lawhead, J. (2019). Learning Geospatial Analysis with Python: Understand GIS fundamentals and perform remote sensing data analysis using Python 3.7.   
Phillips, D. (2015). Python 3 object-oriented programming.   
Twinam, T. (2017). Danger zone: Land use and the geography of neighborhood crime. Journal of Urban Economics, 100, 104-119.   
Xiao, N. (2015). GIS algorithms. 
