# Week 10: Conda, Dask, rioxarray

UW Geospatial Data Analysis  
CEE498/CEWA599  
David Shean  

We made it to Week 10! No formal assignment this week, so please use the time to work on your final projects. During class, we will discuss conda and the simple steps needed to migrate from the course Jupyterhub to your local computer.  We will also explore some of the fantastic Pangeo tutorials, discuss Dask for distributed computing, and how you can scale processing for larger datasets and more complex workflows.

## Tutorials and Discussion Topics

### conda
* [Conda overview](../../resources/conda.md)
* conda vs. pip
* Python site-packages

### Migrating from course Jupyterhub
* [Notes and instructions](../../resources/jupyterhub_migration.md)

### Collaboration with git/Github
* forking, merging upstream changes, pull requests

### rioxarray
* https://corteva.github.io/rioxarray/stable/index.html 

### Dask
* https://docs.dask.org/en/latest/array-best-practices.html 
* https://github.com/pangeo-data/pangeo-tutorial/blob/agu2019/notebooks/dask.ipynb

### Pangeo (http://pangeo.io/)
> "A community platform for Big Data geoscience"
* Examples: https://gallery.pangeo.io/ 

Excellent tutorials from December 2019 AGU Fall meeting:
* https://github.com/pangeo-data/pangeo-tutorial/blob/agu2019/README.md

Take a look at the rendered pangeo notebooks on Github (you can also clone the repo to our jupyterhub/locally if desired, or access through binder or their pangeo AWS hub).  I recommend you work through the xarray and dask notebooks in the top-level directory and the amazon-web-services/landsat8.ipynb notebook.

One thing that I forgot to mention - if you are using the pangeo hub, when you are done running notebooks, please go to **File->Shut Down**.  This will free up the node allocated to you, and stop the clock on the cloud charges.  If you forget, it’s OK, your server should automatically time out and shut down, but best to be a good citizen here and avoid unnecessary resource consumption

#### Landsat-8 time series
* https://github.com/pangeo-data/pangeo-tutorial/blob/agu2019/notebooks/amazon-web-services/landsat8.ipynb
    * Launch on AWS hub
    * In-class demo of using Dask KubeCluster for scaleable processing

## Other Discussion topics
### Licenses, Zenodo and other options for publishing repos

### QGIS
* Full-fledged GIS
* Great for one-off processing and analysis
* Excellent map production tools
* Python interface, but often more flexible to stick with approaches we've covered this quarter
