# Analysis of Soil Moisture at USFS Rangeland Monitoring Sites with Python
*Author: ORNL DAAC*  
*Date: May 1, 2019*  
*Contact for ORNL DAAC: uso@daac.ornl.gov*

## Summary
Forests in the western U.S. have been more and more affected by drought. For example, there was a severe drought event in the Kaibab National Forest in late 2017. The lack of precipitation on Kaibab National Forest has made 2017-2018 the second driest winter in the past 25 years. It significantly affected the biomass productivity in following years. 

<img src="https://westernnews.media.clients.ellingtoncms.com/img/photos/2018/02/20/Boundary_Fire_t715.jpg"/>

*Image source: https://www.williamsnews.com/news/2018/feb/20/dry-winter-sparks-fire-fears/*

In this tutorial, we will dynamically access soil moisture data of multiple sources (i.e. satellite, airborne, and in-situ observations) in the past 10 years from the ORNL DAAC's Soil Moisture Visualizer (https://airmoss.ornl.gov/visualize/) at selected USFS rangeland monitoring sites. We then analyze the time series trends of both surface- and rootzone-level soil moisture at the monitoring sites and compare with the time series trends of the larger USFS Regions. We will also analyze the monthly cycle of soil moisture at those rangeland monitoring sites in years 2017/2018 and compare with the historical mean monthly cycle during 2010-2016.

<img src="https://webmap.ornl.gov/img/DAAC_logo_blue_text_transparent_bg_web_0.png" width="500"/>


## Earthdata Account

A NASA Earthdata account is required to access data through the Soil Moisture Visualizer (SMV). Running the cell below will prompt you for your username and password. If you do not have a NASA Earthdata, follow the link that is displayed and register before logging in.

## Click this to launch a binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yaxingwei/usfs_nasa_workshop_day3/master)
