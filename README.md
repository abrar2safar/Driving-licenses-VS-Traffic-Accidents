


# Web scraping & creating dataset 

**by : Abrar Safar**




## Dataset 

here's the link for the dataset on [Kaggle](https://www.kaggle.com/abrar2safar/condos-for-rent-in-riyadh)



## Problem Statment

opensouq is a website for different types of products , cars , estats , electronics ...etc .
the data I extracted is condos listed for rental so an individual can gather infos about area , space , number of bedrooms and features of the condo . 




## Executive Summary

Extracted data from opensuoq website using WebScraber tool installed in Chrome Browser , then joined them into one dataest cosists 143 rows and 6 columns ready for EDA





## Data dictionary

|Feature|Type|Description|
|---|---|---|
|Name|object|Name of the add for the condos| 
|NeighborHood|object|The neighborhood of the condos | 
|Bedrooms|object|Number of bedroms in the condo| 
|Baths|iobject|Number of baths| 
|Price|object|Price of annual rental| 
|Space|object|Space of the condo in squared meter| 




## Conclusions and Recommendations

* I noticed all columns typed object and that need to be converted .
* Bedroom and baths values needed to be numric instead of objects .
* data is almost 145 rows and the search in the website is adjusted to find only annual rentsal so it might been more usful if we adjusted the search to find monthly rental condos .






