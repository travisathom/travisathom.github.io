---
title: "Climatic data for green building design in Zambia"
date: 2025-05-12T10:00:00-04:00
categories:
  - Green Buildings
  - Climate Data
---
A fundamental step in our buildings becoming a little greener, is them adapting to their climate. 

Generally, a building is not "green" if it has been designed and built with little regard for the heat from the sun, the temperature and humidity of the air, or the speed and direction of the wind throughout the year.

Weather conditions are all too often ignored, or simply overcome with the latest technologies - larger sized air conditioning or more solar panels. This leads to higher complexity, build and operational costs, and in some instances greater environmental impact. 

A climate responsive building employs initiatives that lead to a more comfortable and lower energy building - effective natural ventilation that reduces the build up of heat or external sun shading that prevents the sun's heat from making the space too hot. 

A common starting point for designing climate-adaptive, sustainable, green buildings is to complete an analysis of the climate it is located in. 

### Climate anaylsis tool - CBE Clima Tool
I find that the free and open source web based tool [CBE Clima Tool][clima-tool] developed by University of Berkeley Center for the Build Environment is a great starting point.

The tool allow users to analyse weather data (aka weather files) for over 27,000 locations across the world. 

The tool provides weather files for over 20 locations across Zambia - including populations centres like Lusaka, Chipata, Kabwe, Livingstone, Ndola, Chipata, Kasama, Mongu. 

Unfortunately, there are some significant locations where weather data is unavailable - Kitwe, Chingola & Luanshya. 

I will provide guidance on a simple process for generating weather files for any location. These files can be uploaded to CBE Clima Tool and analysed.

The weather files provided on CBE Clima Tool are known as a Typical Meteorological Year (TMY), in which historical weather data is statistically condensed into a year of the most usual conditions. This is a common weather file type used for climate analysis and also building energy modelling - EnergyPlus or IES VE. 

### Limitations
Tool useful for getting a pick.
But doesn't neccessarily test passive design initiatives such as natural ventilation, evaporative cooling etc.
Some of the limitations of the datasets can include:
* A lack of rainfall data for some locations

### Example climate analysis for Lusaka Zambia
Some of the basic conclusions that can be drawn from high level climate analysis (Lusaka International Aiport TRY) illustrated in the analysis below includes:

#### Climate Summary
* The Koppen Geiger Climate Zone: Cwa, Humid Subtropical, dry winter <br>
* Relatively temperate climate with an average yearly temperature of 20.5 degC
* Air temperature across the year between 9 to 33 degC

#### Yearly air temperature
Although Lusaka's seasons are commonly described wet and dry season, when considering air temperature I find it helpful to think of it in three seasons. Observations include:
* Comfortable: Four month period (Dec - Mar) where daily temperature range relatively comfortable. Overnight minimums commonly slightly less than lower comfort band.
* Cool: Four to six month period (Apr - Sep) where daily minimums (commonly overnight)) are less than the lower comfort band. 
* Warm / hot: Four month period (Aug - Nov) where daily maximum air temperatures commonly exceed upper adaptive thermal comfort band.

![LusakaTemp](/assets/images/posts/2025-05-13-climatic-data/lusakatemp.png){: .align-center}

The heatmap chart also provides a useful visual insights into how the air temperature varies throughout the year across a 24 hour period.

![LusakaHeatMap](/assets/images/posts/2025-05-13-climatic-data/lusakaheatmap.png){: .align-center}

#### Wind speed and direction

![LusakaWind](/assets/images/posts/2025-05-13-climatic-data/lusakawind.png){: .align-center}
Wind rose

#### Solar and cloud

![LusakaSolar](/assets/images/posts/2025-05-13-climatic-data/lusakasolar.png){: .align-center}

![LusakaCloud](/assets/images/posts/2025-05-13-climatic-data/lusakacloud.png){: .align-center}



[clima-tool]: https://clima.cbe.berkeley.edu/
[climate-cons]: https://www.sbse.org/resources/climate-consultant


<!--
**AMY** - Alternately, a Actual Meteorological Year (AMY), consisting of actual hourly data sets over a a year time period, put into the same format as a TMY file maybe used. In a future post I will talk an excellent resource for generating these files for any location in the world.

The format of the weather file used as a basis for the analysis is a EPW file. This is a common file input file used for building energy modelling software - Energy Plus or IES Virtual Environment.

Some of outputs that I find useful from the tool include:

The best place to start to understand the tool and its input data is here: https://cbe-berkeley.gitbook.io/clima

However, using the tool is only half the equation - 
Limitations of the tool

Included below are some of fantastic graphical outputs that maybe generated from the tool.

This is not how buildings have historically been built either.

A great place to climate data to inform building 


* Green Building design using climatic data - typically test reference year
* Quality data hard to come for many developing countries due to lack of 
* Rubbish in is equal to rubbish out
* "Computer simulation is never accurate, but some models are useful" quote
* Great source of data is ....
* Alternately one can download historical weather data for many locations

* Next post will explore power of [Climate Consultant][climate-cons] to help explore passive design opportunities relevant to Lusaka.

-->
