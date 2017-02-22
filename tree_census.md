## Analysis on 2015 NYC Street Tree Census 

##### Abstract

Trees are essential to human beings. They absorb carbon dioxide and release oxygen, provide habitats for a variety of animals and play a significant role in ecosystem.
In order to help professional people better know the health status of the street trees in the city and also help raise the public's awareness,
our Shinny app is desiged to present abundant information based on the data from 2015 NYC Street Tree Census.

##### Data Processing

The dataset we used comes from 2015 NYC Street Tree Census, downloaded from [NYC OpenData](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/pi5s-9p35/about), which is conducted by volunteers and staff organized by NYC Parks & Recreation and partner organizations.
The size is 89.2 MB and it has 683788 samples, after we selected the 20 columns as follows:
'tree_id', 'status', 'health','spc_common','guards', 'sidewalk','root_stone','root_grate', 'root_other', 'trunk_wire', 'trnk_light', 'trnk_other','brch_light', 'brch_shoe', 'brch_other', 'address', 'zipcode', 'borocode','latitude','longitude'.


##### What we've found

#####  Focus on the street trees that are alive:

  * trees that have poor health status 

  * trees that have good health status but have problems coming from their roots, trunks or branches


#####  Choropleth Map
 
The Choropleth Map visualizes the propotion of dead trees, stump trees and healthy trees across the NYC area.
The zipcodes of the areas with the highest propotion of dead trees are 11697,	11451, 10006,	10048, 10018,	10474,	10069,	      10005,	10452, 10456,	11224, mainly distributed in upper Manhattan.The stump street trees are mainly distributed in Queens.


#####  Focus on species

We also drew a scatterplot reflecting the propotion of healthy trees and unhealthy trees of each species.
This is meant to give insights on which species of trees can thrive better in NYC area and which are not.
In this scattterplot, each point represents a specific species and its X represents its healthy propotion while the Y the      unhealthy propotion. So we conclude that Black Pine, Norway Maple, Katsura Tree, Pond Cpress and Amur Cork Tree might not      fit well in NYC area.

##### What could be improved

* Add the function of showing current location
* Expore the health problems more deeply, in terms of root, trunk and branch

[back](index)
