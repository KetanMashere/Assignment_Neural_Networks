# Assignment_Neural_Networks
## 1. Content
## **Problem Statement**
+ PREDICT THE BURNED AREA OF FOREST FIRES WITH NEURAL NETWORKS.

# Data Description:

+ Forest fires can create ecological problems and endanger human lives and property. Understanding when they occur and what causes them is important for managing them. The data we'll be working with in this is associated with a scientific research paper on predicting the occurrence of forest fires in Portugal using modeling techniques. The focus will not only be about modelling for this project, but also on visualizing it. There will also be exploratory analysis on the data to better understand it and to find any relationships that might be present in it.

### About the Dataset
##### Attribute Information:

* **X**: X-axis spatial coordinate within the Montesinho park map: 1 to 9 
* **Y**: Y-axis spatial coordinate within the Montesinho park map: 2 to 9 
* **month**: Month of the year: 'jan' to 'dec' 
* **day**: Day of the week: 'mon' to 'sun' 
* **FFMC**: Fine Fuel Moisture Code index from the FWI system: 18.7 to 96.20 
* **DMC**: Duff Moisture Code index from the FWI system: 1.1 to 291.3 
* **DC**: Drought Code index from the FWI system: 7.9 to 860.6 
* **ISI**: Initial Spread Index from the FWI system: 0.0 to 56.10 
* **temp**: Temperature in Celsius degrees: 2.2 to 33.30 
* **RH**: Relative humidity in percentage: 15.0 to 100 
* **wind**: Wind speed in km/h: 0.40 to 9.40 
* **rain**: Outside rain in mm/m2 : 0.0 to 6.4 
* **area**: The burned area of the forest (in ha): 0.00 to 1090.84

## 2. Content
## **Problem Statement**
+ Predicting Turbine Energy Yield (TEY) using ambient variables as features.

### About Dataset

+ The dataset contains 36733 instances of 11 sensor measures aggregated over one hour (by means of average or sum) from a gas turbine. 
+ The Dataset includes gas turbine parameters (such as Turbine Inlet Temperature and Compressor Discharge pressure) in addition to the ambient variables.

# Attribute Information:
+ The explanations of sensor measurements and their brief statistics are given below.

|Variable|(Abbrivation)|Unit|Min|Max|Mean|
|:------|:------:|:------|:------|:------|:------|
|Ambient temperature |(AT)| C| 6.23| 37.10| 17.71|
|Ambient pressure |(AP)| mbar |985.85 |1036.56 |1013.07|
|Ambient humidity |(AH)| (%) |24.08 |100.20 |77.87|
|Air filter difference pressure |(AFDP)| mbar |2.09 |7.61 |3.93|
|Gas turbine exhaust pressure |(GTEP)| mbar |17.70 |40.72 |25.56|
|Turbine inlet temperature |(TIT)| C |1000.85 |1100.89 |1081.43|
|Turbine after temperature |(TAT)| C |511.04 |550.61 |546.16|
|Compressor discharge pressure |(CDP)| mbar |9.85 |15.16 |12.06|
|Turbine energy yield |(TEY)| MWH |100.02 |179.50 |133.51|
|Carbon monoxide |(CO)| mg/m3 |0.00 |44.10 |2.37|
|Nitrogen oxides |(NOx)| mg/m3 |25.90 |119.91 |65.29|
