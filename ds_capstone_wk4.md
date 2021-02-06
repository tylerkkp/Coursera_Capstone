# IBM Data Science Capstone
## Week 4 - Problem Statement

Beer tourism is becoming increasingly common, and (fortunately) there is an abundance of choices for destinations. According to [this article](https://fortune.com/2019/08/06/new-craft-breweries-2019-data/), over 1,000 opened in 2018. That's a bit less than 3 per day! One of the more popular cities for beer tourism is Portland, Oregon. I went to college in Portland, but was underage and did not have the palate for good beer at the time. However, in the years since leaving Portland, I've become increasingly involved in the craft beer industry. Most recently, I started contributing to the OpenBreweryDB project, which seeks to catalog craft breweries across the USA and the world (currently including England and Scotland, although additional countries are anticipated in the future). 

As with many large cities, Portland has quite a few distinct neighborhoods, each with its own unique personality and characteristics. In this project I will be looking at the neighborhoods as defined on the City of Portland Open Data portal [here](https://gis-pdx.opendata.arcgis.com/datasets/neighborhoods-regions?geometry=-123.656%2C45.374%2C-121.678%2C45.711). I will also be using the [OpenBreweryDB](https://www.openbrewerydb.org/) dataset, either through directly downloading the dataset, or using the API. I want to do a couple of analyses. In the spirit of 'Battle of Neighborhoods', I want to see which neighborhood can claim:

1. The most breweries
2. The 'best' breweries based on Foursquare reviews
3. Whatever else I can see from the initial exploratory analysis

The OpenBreweryDB dataset has a number of interesting datapoints which could provide some insights. For example, the predominant 'type' of brewery in a neighborhood. Brewpubs and other similar establishments would likely be more prevalent in tourist areas, and larger breweries would be found in more industrial areas where land and rent are cheaper. I would expect Nano and Micro Breweries to be in neighborhoods since they could be sustained by a small local population. My analysis will help determine if my assumptions hold true. 

