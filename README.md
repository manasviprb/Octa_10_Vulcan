# Octa_10_Vulcan
**Aim**

Our project aims to formulate an IoT-based intelligent agricultural system to monitor pesticide control and soil moisture levels for planning and scheduling purposes. 

**Motivation**

Implementation of IoT based services in agriculture can boost the yield, predict adverse climatic conditions and promote sustainability by optimising the usage of chemical pesticides and fertilisers. 
The data collected will be made available to the farmers via cloud services to schedule and ensure high-quality products. This data will be easily accessible through a mobile application. 
The development of Intelligent Smart Farming IoT-based devices can enhance it and make it cost-effective and even reduce wastage.

**Introduction**

Agriculture plays a vital role in developing an agricultural country like India. Issues concerning agriculture have always been hindering the development of the country. The only solution to this problem is smart agriculture by modernising the current traditional methods of agriculture. Hence the proposed approach aims at making agriculture smart using automation and IoT technologies.

Pests hinder the growth of crops and hence affect agricultural yield. Additionally, excessive pesticide usage can damage the soil and crops. Therefore, it is essential to monitor the pesticide treatment. With IoT, pest control information gathered from the sensors can be easily exchanged with the farmers via mobile phone applications to ensure optimum yield. 

Soil moisture content is a vital indicator of soil health and crop yield. It is also crucial to determine the irrigation schedule. 
Crops mainly depend upon the root level of moisture present in the soil, and hence knowledge about the degree of wetness helps farmers ascertain the condition of the field and act on it.

Furthermore, over-irrigation is a leading cause of crop damage. This is because over-irrigation deprives the plants' roots of oxygen and causes them to decompose, ultimately leading to soil fungal diseases. IoT and use cases can play a vital role in preventing over-irrigation. 

**Methodology/Algorithm**

In order to determine the moisture content, the data regarding soil humidity, air temperature, wind speed and historical climate data can be used.
The IoT based smart irrigation systems can fetch the vital physical parameters from the agriculture field, which could help in real-time decision making about the watering of plants/crops.

The sensor node is based on Raspberry Pi and Arduino Uno based computation/processing and control platform with sensors for considering soil moisture, soil temperature, humidity, and air temperature. Pyroelectric infrared sensors are used in order to determine optimum pesticide usage and its effect on crop yield and soil fertility. 

Web services are used for data communication between the sensor node (deployed in the field) and the centralised database. Further, weather forecast data is fetched from the Internet for using the same in predicting soil moisture for the upcoming days. 

Moreover, to develop a more accurate system, historical data regarding the quantity of irrigation used in the previous period are considered to adjust the quantity of water needed for irrigation.

![WhatsApp Image 2022-01-19 at 11 30 25](https://user-images.githubusercontent.com/97897662/150106885-09b44523-a8c7-49b2-a6d9-59f517ce784c.jpeg)
 
Tech Stack used in the project is Python Libraries like Pandas, Matplotlib, Seaborn and ScikitLearn.
K - Nearest Neighbors algorithm is used in this project to perform the classification. The reasons behind using this algorithm are:
1. It is easy to use and is an efficient method for small datasets.
2. It utilises Lazy Learning Approach. Here, the training dataset is stored, and it is only used when making predictions, therefore, making it faster than other algorithms like Support Vector Machines (SVMs).
This is needed to ascertain the outcome of the harvest season, i.e. whether the crop would be healthy (alive), damaged by pesticides or damaged by other reasons. 


