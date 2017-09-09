### Air Quality Dataset(Source: UCI)


#### Why is it Interesting?!
Local air quality affects how you live and breathe. Like the weather, it can change from day to day or even hour to hour. 
Air pollution is one of the most serious problems in the world. It refers to the contamination of the atmosphere by harmful chemicals or biological materials. To solve the problem of air pollution, it's necessary to understande levels of harmful gases, and the issues that it causes and look for ways to counter it. We can do predictive modelling and develop an air quality model based on the given data. *The reason this dataset caught my eye is, as I am a Pro-Environmentalist, I was apalled at the increasing levels of the harmful gases in the air that we breathe. Also, since Im new to Data Analysis, I found a few starter scripts in R and Python, which will make the regression analysis and predictive modelling easier.*


#### Dataset Information
The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level,within an Italian city. Data were recorded from March 2004 to February 2005 (one year)representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer.

It has 9358 rows and 15 columns and is available in both .csv and .xlsx formats.

##### Sample column headers(Attribute information)

0 Date	(DD/MM/YYYY) 
1 Time	(HH.MM.SS) 
2 True hourly averaged concentration CO in mg/m^3 (reference analyzer) 
3 PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)	
4 True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer) 
5 True hourly averaged Benzene concentration in microg/m^3 (reference analyzer) 
6 PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)	
7 True hourly averaged NOx concentration in ppb (reference analyzer) 
8 PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted) 
9 True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)	
10 PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)	
11 PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted) 
12 Temperature in Â°C	
13 Relative Humidity (%) 
14 AH Absolute Humidity 


#### Details of the license or terms of use

##### Source: UCI, Machine learning repository
There are no terms of use mentioned in UCI, Machine learning 
repository as such, but the home page is as follows:
http://archive.ics.uci.edu/ml/index.php

It does have a citation policy, which is as follows:
https://archive.ics.uci.edu/ml/citation_policy.html

##### Source cited in UCI website: Saverio De Vito (saverio.devito '@' enea.it), ENEA - National Agency for New Technologies, Energy and Sustainable Economic Development.

There is no terms of use mentioned in this site either and the site is not operational anymore.
It does mention this - Pursuant to art. 37 of Law no. 99 of July 23rd, 2009, the Agency’s activities are targeted to research, innovation technology and advanced services in the fields of energy - especially nuclear.


#### Potential data users and decision-makers for this data

Potential data users can be someone who wants to come up with air quality model or regression analysis or predictive modelling. This data is mainly used for research purposes as cited in the source: ENEA - National Agency for New Technologies, Energy and Sustainable Economic Development


#### Research Questions
* What is the cause for this increase in levels of the gases?
* What pattern of changes can be seen in Air Quality Index(AQI) from the data?
* Can we establish a pattern between people's health and the levels of the gases at a given period of time?
* What prediction modelling technique can be used to develop an air quality model based on the data?


#### References
Lichman, M. (2013). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

S. De Vito, E. Massera, M. Piga, L. Martinotto, G. Di Francia, On field calibration of an electronic nose for benzene estimation in an urban pollution monitoring scenario, Sensors and Actuators B: Chemical, Volume 129, Issue 2, 22 February 2008, Pages 750-757, ISSN 0925-4005. 
[http://www.sciencedirect.com/science/article/pii/S0925400507007691?via%3Dihub]
