<img src="https://i.ibb.co/bJcZLW5/ga-logo.png"  align="middle" width="800">

<br>
<br>
<h2><center>Project 1: Local Traffic and Licenses, Statistical Summaries and Inference</center></h2>

**Table of Contents:**
- [**Overview:**](#overview)
- [**What is about?**](#what-is-about)
	- [Problem Statement:](#problem-statement)
	- [Executive Summary](#executive-summary)
- [**Datasets**](#datasets)
	- [Provided Data:](#provided-data)
	- [Additional Data:](#additional-data)
	- [**Data dictionaries:**](#data-dictionaries)
		- [Driving licenses 1993-2017:](#driving-licenses-1993-2017)
		- [Traffic accidents 2016-2017:](#traffic-accidents-2016-2017)
		- [Updated Driving licenses and accidents 2018-2019 :](#updated-driving-licenses-and-accidents-2018-2019-)
- [**Conclusions and Recommendations:**](#conclusions-and-recommendations)

---

# **Overview:**
- First project in DSI covers:
 - basic statistics
 - many Python programming concepts
 - programmatically interacting with files and directories
 - visualizations
 - EDA


# **What is about?**

## Problem Statement:
- Everyday in every region we see or encounter or hear about an accident happen, and we lose peoples from these accidents, sometimes from a mistake from another driver and sometimes from the environment it self. By analyzing these two datasets we are trying to get and understand the relationship between the driving licenses and the accidents and find a technique or solution to decrease the number of accidents in Saudi Arabia. by using the Driving Licenses, Traffic Accidents datasets from 1993-2019 for licenses and from 2016-2019 for the accidents.

## Executive Summary
 - We&apos;re going to take a look at the number of traffic accidents and driving licenses issued in Saudi Arabia. We'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing the outcomes of traffic accidents in the various regions in Saudi Arabia. And we will use graphs, statistics and some other out resources to provide a good overview for the accidents in the Saudi Arabia and how to improve and reduce the accidents that happen here. we will be looking in:
- **Which region has the most accidents.**
- **Which region has the most licenses.**
- **How the regions are doing over years.**
- **And some other general information about the time period of this data.**
---

# **Datasets**
## Provided Data:
- For this project, i will use two datasets provided by [**GA**](https://generalassemb.ly/) and an updated version of them from [**kapsarc**](https://www.kapsarc.org/) :
 - [Traffic Accidents and Casualties by Region 2016-2017](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-traffic-accidents-2008.csv)
 - [Driving Licenses Issued By Administrative Area 1993-2017](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-driving-licenses-2004-2008.csv)

## Additional Data:
- Outside datasets and department site:
 - [Updated Driving Licenses 2018-2019 ](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008)
 - [Updated Traffic Accidents 2018-2019](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008)
 - [Website of the General Department of Traffic](https://www.moi.gov.sa/wps/portal/Home/sectors/publicsecurity/traffic/!ut/p/z1/04_iUlDg4tKPAFJABjKBwtGPykssy0xPLMnMz0vM0Y_Qj4wyizfwNDHxMDQx8nZ3CTQ1cAz0dvX3dDE2MnA00vfSj8KvIDg1T78gO1ARAHn-YJg!/)

---

## **Data dictionaries:**
### Driving licenses 1993-2017:

|Feature|Type|Dataset|Description|
|:--|:-:|:--|:---|
|**year**|*int*|Driving_Licenses|A time period for extracted driver licenses per year.|
|**region**|*object*|Driving_Licenses|Areas of Driver licenses.|
|**number_of_licenses**|*int*|Driving_Licenses|Total Number of driver licenses for each area over time.|
|**region_x**|*float*|Driving_Licenses|Latitude coordinate.|
|**region_y**|*float*|Driving_Licenses|Longitude coordinate.|

### Traffic accidents 2016-2017:

|Feature|Type|Dataset|Description|
|:--|:-:|:--|:---|
|**year**|*int*|Traffic_Accidents|A time period for accidents happened per year|
|**region**|*object*|Traffic_Accidents|Region of the accidents for each area. |
|**accident_indicator**|*object*|Traffic_Accidents|An indicator type for the accident for each area. No. of Accidents, Dead, or Injured |
|**indicator_value**|*int*|Traffic_Accidents|A value corresponding the indicator|
|**region_x**|*float*|Traffic_Accidents|Latitude coordinate|
|**region_y**|*float*|Traffic_Accidents|Longitude coordinate|

### Updated Driving licenses and accidents 2018-2019 :
|Feature|Type|Description|
|:--|:-:|:---|
|**year**|*int64*|An indicator for the year per region.|
|**region**|*object*|Name for the regions.|
|**number_of_licenses**|*int64*|Total Number of driver licenses for each area.|
|**no_accidents**|*int32*|Total Number of accident for each area.|
|**no_dead**|*int32*|Total Number of deads for each area.|
|**no_injured**|*int32*|Total Number of injured for each area.|

---

# **Conclusions and Recommendations:**
- You can read my Article on Medium for this project here [History of Saudi Arabia: Licenses and accidents a short overview](https://moh-01.medium.com/history-of-saudi-arabia-licenses-and-accidents-a-short-overview-2cba393f8360)
- We&apos;re expecting an increasing number of drivers on the roads each year from 1993 to 2017 we saw an increase in the numbers until 2015 it went down but in 2016 and 2017 it comeback with numbers more than any year before, and it's the same for accidents, injured, dead. With each year we see a region increasing and others get decreased. And based on what we did until now we can say: 'Riyadh', 'Makkah' and 'Eastern_Region', are having a high number when we talk about the number of licenses and no accidents over all-region and years. But for the number of licenses 'Riyadh' is highest with great numbers between regions with almost 500k licenses in a single year for 2017.

- And Riyadh is expecting an increase in the number of licenses because each year the number is increasing in 2016 we got `242,851` and in 2017 we got `495,307`, `+49%`incresing over a single year. So based on that and what we found from the research 'Riyadh' got more licenses in 2018-2019 more than in past years. And the same for 'Makkah' and 'Eastern_Region'. In 2017 it got an increasing in Number of licenses we can see an increase with a number of accidents for some regions and some are lower based on `2016`, the `2017` is better for some regions like 'Riyadh', And we can see 'Makkah' around `140k` licenses it got `+145k` accidents. But for Riyadh, it&apos;s Not.

- All death and injured in 2017 for each region, 'Makkah' is the highest number of injured then 'Riyadh' which is good for 'Eastern' that they dropped from what happens in 2016 but 'Riyadh' increased by almost `10%`. But 'Makkah' still the highest among all of the regions with over `10,600` but they did well decreasing from `12,600` to know is a good thing. For death, Makkah still in front with `2243` deaths over `2017` then 'Riyadh' with `1430` deaths.
