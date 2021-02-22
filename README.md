

Project: NYC accident prone locations 
======================================

Abstract
========

NYC is known for its traffic jams. So, going around on a bike is a big time saver. But there’s some risk of having an accident. We have two datasets to do some research on them: <br>
• Bike Stations: https://feeds.citibikenyc.com/stations/stations.json <br>
• Vehicle crashes: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95


Results
============

- See the **"Bike_Accidents"** notebook for the code behind my analysis.<br>
- You will also find a RESULTS.md in the same core folder. <br>
- It also includes a much appreciated HTML format of the notebook easily sharable with vairous stackeholders and various screenshots of relevant results. <br>
- You will also find the predictive model, the weights and the training history in the core folder.


Instructions
============

### The Data:
Download [Motor Vehicle Collisions data](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95) csv format <br>
The data and external images included in the notebook should be in the same folder. You can also change the directory path in the notebook. 

### The environment:
Please instell geopy if you dont have it in your environment.
```
! pip install geopy
```

### General Requirements
+ Python 3.5+
+ Keras
+ Pandas
+ Numpy
+ matplotlib
+ seaborn
+ plotly.express
+ IPython.display 
+ datetime  <br>
All the libraries are listed in the head of the notebook.<br>
We could provide a requirements.txt or a docker container.<br>
The code can also be run on google colab or on other clould environments

