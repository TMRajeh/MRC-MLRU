# GRU-MLRU - Modeling multi-regional temporal correlation with gated recurrent unit and multiple linear regression for urban traffic flow prediction
 # Traffic Flow Prediction
Paper : ‘Modeling multi-regional temporal correlation with gated recurrent unit and multiple linear regression for urban traffic flow prediction’ , Rajeh, Taha M., Tianrui Li, Chongshou Li, Muhammad Hafeez Javed, Zhpeng Luo, and Fares Alhaek, In Knowledge-Based Systems. 2022 Dec 28:110237.
# Introduction
This repo contains datasets for predicting traffic flow within the Second Ring Road of Chengdu and Xi'an cities, China for two months, between Oct 1st and Nov 30, 2016, derived from the ordered datasets of the ride requests collected by DiDi company https://gaia.didichuxing.com.
# data
-	_borders.xlsx: file contains the latitude and longitude that describe the study area in the city.
-	Regions_coordinate.csv: file contains the latitude and longitude of each region.
-	adjacency_matrix_xian.csv: contains the neighbor matrix for each region (0 not neighbor , 1 neighbor )
-	Region_scal_3min(  ).csv : contains the traffic dataset measured every 3 minutes
*	Area_ID ： (int) represent the region ID.
*	From_time : The start time of sample counting.
*	To_time : The time sample counting is completed.
*	Avg_time: The average time between the start time(From_time) and end time (To_time)
*	Timestamp : represents the sample number
	Cnt : represents the traffic value.
# To cite this dataset and for more information see the appendix :
T. M. Rajeh, T. Li, C. Li, M. H. Javed, Z. Luo, and F. Alhaek, “Modeling multi-regional temporal correlation with gated recurrent unit and multiple linear regression for urban traffic flow prediction,” Knowledge-Based Systems, vol. 262, p. 110237, 2023. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S0950705122013338
