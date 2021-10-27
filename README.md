# Time-Series-Analysis-of-Seouls-Air-Pollution
By: Rashid Karriti
# Overview
![image](https://user-images.githubusercontent.com/82670256/138161091-6e3846e7-bf6a-43a4-a9ed-5ee59d58a480.png)


# Business Understanding
Seoul, South Korea is one of the most polluted cities in the developed world, ranking [3rd](https://www.ft.com/content/b49a9878-141b-11e7-80f4-13e067d5072c) highest daily average as of 2017. Additionally, Seoul has reached PM2.5 levels which is [two times](https://smartairfilters.com/en/blog/air-quality-seoul-pollution/) the annual limit that the WHO recommends. This project analyses a series of time series models to provide insight to the South Korean Ministry of Health and Welfare, which is responsible for public health, to pinpoint what areas have the worst PM2.5, PM10, and NO2 levels that can lead to detrimental long term health effects to citizens across all districts of Seoul. Furthermore, this project investigates what could have caused these high levels of air pollution and what can be done to protect the public's health from these air pollutants. Looking at the root mean squared error
of every station of Seoul to see within what range my models can predict bad pollutants in specific districts.

![image](https://user-images.githubusercontent.com/82670256/139100853-d0795407-1323-4d29-b76d-967b9712a16e.png)

![image](https://user-images.githubusercontent.com/82670256/139100935-7f3ed1b3-cc98-4136-9487-cd66579bd4f0.png)

![image](https://user-images.githubusercontent.com/82670256/139100949-ad44f879-ee2a-4a99-844c-8de0c19ed966.png)

# Data Understanding
This project focuses on using Time Series Models, mainly SARIMAX and ARIMA models, running several iterations to find with what range the models can predict the levels of each dangerous pollutant in every one of Seoul's 25 districts. My data set comes from Seoul Metropolitan Government public data through the 'Open Data Plaza' from the year 2017 to 2019 for every hour of the day across 25 districts of Seoul. Furthermore, I manipulated the dataset to be the daily average, as it was a better indicator for the levels of pollutants and a better fit for Time Series models. Lastly, I broke up every district of Seoul into a seperate dataframe and looked at the pollutants in that area and focused on those that reached levels dangerous for the public's health.   

The other data sets that I am working with is Shanghai's Air Quality Index (AQI) from 2017 to 2019 focusing on air pollutants PM 2.5, PM10, and NO2, based on [scientific](https://www.nature.com/articles/s41598-020-68201-0) research that suggest that a large amount of air pollutants, specifically particulate matter (PM2.5 and PM10) travels from Shanghai to Seoul, and showing this data will show how Shanghai's rising levels of pollutants has the lasting effects to the levels of air pollutants in Seoul. Additionally, I incorporated weather data from the National Oceanic and Atmospheric Administration (NOAA), specifically from its National Centers for Environmental Information (NOAA), on Seoul's daily weather to see if it correlates and/or has a large effect to the general effect of air pollution in Seoul. 

# Results

# Conclusion & Future Steps
tbd most likely will recommend certain initiatives, what districts to pay the most attention to, and what South Korea can do to mitigate the damage that has been done.  
# Relevant Links 
- [Impact of the Clean Air Act on Air Pollution and Infant Health: Evidence from South Korea](https://ftp.iza.org/dp11542.pdf)
- [Air Pollution in the Republic of Korea](https://www.tandfonline.com/doi/pdf/10.1080/00022470.1984.10465820)
- [KORUS-AQ Rapid Science Synthesis Report](https://espo.nasa.gov/sites/default/files/documents/KORUS-AQ%20RSSR.pdf)
- [Changes in air pollution levels after COVID-19 outbreak in Korea](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7402377/)  
- [The Effects of Air Pollution on Mortality in South Korea](https://reader.elsevier.com/reader/sd/pii/S1878029615001929?token=BB5E1CA447BF2779433AA74A4C2F2FF5E8044C037CCFA4832A188E36BDC6A962A8152EA18FDF09806FED6A40F0EA822D&originRegion=us-east-1&originCreation=20211007173945)
