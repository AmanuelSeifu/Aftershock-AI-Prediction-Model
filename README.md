# The Results

This python project uses federal csv data (U.S. Geological Survey) and a public seismological data API (Iris Federator) in addition to TensorFlow
to graph earthquake data, algorithmically extract aftershocks in the data, and to predict if an earthquake will be followed by an aftershock within 24-48 hours. 

The results varied between 92 and 94 percent accuracy based on the data sets that were used. The csv data (which was simpler and had a wider breadth of data)
was the more accurate data set with the normalized waveform graph data (from the API) not being too far behind.

## CSV Data Model
|![alt text](./CSV_ex.jpg)|
|:--:| 
|*Credit: USGS (U.S. Geological Survey)*|

|![alt text](./accuracy.PNG)|
|:--:| 


## Waveform Data Model
|![alt text](./Waveform_ex.png)|
|:--:| 
|*Credit: USGS (U.S. Geological Survey)*|

|![alt text](./acc2.PNG)|
|:--:| 

## Graphs of Earthquake Data Set
![alt text](./graphs1.PNG) ![alt text](./graphs2.PNG)
![alt text](./graphs3.PNG)
