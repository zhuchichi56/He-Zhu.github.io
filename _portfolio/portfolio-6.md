---
title: "DataMining Final Project"
excerpt: "Shenzhen cab data visualization platform <br/><img src='/images/kl1.png' style='zoom:50%'> <img src='/images/kl2.png' style='zoom:50%'>"
collection: portfolio
---



Smart cities originated in the media field, which refers to the use of various information technologies or innovative concepts to connect and integrate the systems and services of a city in order to enhance the efficiency of resource utilization, optimize urban management and services, and improve the quality of life of citizens. 2012, the introduction of the Interim Management Measures on National Smart City Pilot kicked off the construction of smart cities in China. Just recently, Shenzhen released its action plan for 2022-2025, **formally announcing the creation of a global digital pioneer city so that citizens can fully enjoy the dividends of a digital society.** How to make full use of the large-scale data in the city and build a digital twin city has become the focus of our attention. Taxis, as one of the main means of transportation in cities, are fully present in the streets and alleys of cities, fully integrated into urban transportation, and have the characteristics of wide coverage, high flexibility, easy management and data collection. The integration and analysis of cab data in the city can uncover important information such as traffic information and hotspot areas of the city, which is of great value to the construction of data twin cities.



### Basic Visualization

![KDD1](/images/KDD1.png)

The figure shows the image of the data we intercepted from 8:30 am to 9:30 am, we can most intuitively see the basic distribution of cabs in Shenzhen in the morning, more in the urban area in general, and less in the eastern Shenzhen-Shantou Cooperation Zone and Yantian District. And there are a few lines running outside the obvious in accordance with the road network extended to Dongguan, Shantou, Zhuhai and other places.



### Visualization of cab loading status

![KDD2](/images/KDD2.png)

The figure shows our cab load situation at 12:03 a.m. You can see that the red dots indicate cabs that are carrying passengers, and the blue dots indicate cabs that are not carrying passengers. We can see that the overall distribution is relatively even, and the vehicles are not very obviously carrying passengers in some parts and not in others, which is in line with our perception. Zooming in on this graph, we can also see some special cases. For example, on the right side of the graph, we zoomed in on a piece of the Futian district, and we can see that there are clearly some vehicles here that are not carrying passengers, so we think this is probably a place where cabs are **concentrated at noon for lunch or some places waiting to pick up passengers.** We found that this is a **complex urban village**, which is basically in line with our previous inference.





### Comprehensive analysis of cab ridership/business district data

![KDD3](/images/KDD3.png)

We continued to cluster all the locations of the cabs at this time and obtained several distinct clusters, which corresponded to the **core business** **districts** of Shenzhen.





### Visualization of OD flow

![KDD4](/images/KDD4.png)

Traffic origin and destination survey, also known as **OD survey**, its visualization we usually call him OD flow, it is from the boarding point connected to the point of disembarkation of the connecting line. (Here the pick-up and drop-off points are roughly estimated from the **sampled data** based on the change of passenger status, but the small error does not affect the global observation). OD flow can facilitate our analysis of cab order information, showing the order status of cab rides. Here, because there is too much information about cabs, we sample out a small part of the cab order information using OD stream to show that **we can see that the cross-district flow demand in Shenzhen is still relatively large,** and many cab orders will have a relatively large cross-district, especially the majority of Baoan District to Nanshan, Futian and Luohu, most likely because of the Baoan Airport. And in Longgang District there will be a more obvious local center.



### 3D visualization of cab loading status

![KDD5](/images/KDD5.png)

Previously we showed the cab data using points, and later we will visualize the data for statistical analysis. We analyzed the number of cabs carrying passengers in different areas, and we can see that the cabs carrying passengers are significantly more distributed in central areas such as Nanshan District and Futian District.



![KDD7](/images/KDD7.png)

Having just analyzed cabs carrying passengers, we also analyzed the number of cabs passing with or without passengers, and we can see that overall there are still far more commercial areas in the south than in the mountainous areas in the north.





### 3D visualization of cab speed

![KDD6](/images/KDD6.png)

Cabs, distributed throughout the traffic network, and observing the vehicle speed of cabs in a certain area can also reveal the overall traffic flow in Shenzhen. We took a 3D histogram of the vehicle speed visualized by our system during **morning rush hour, afternoon rush hour, evening rush hour and after 9pm**.（Just Plot morning rush hour） We can see that in the graph there is clearly a slower traffic speed in the southern central area, and the traffic speed is on average slower in the morning peak and evening peak hours than in the afternoon. We also found the characteristic "996" late night peak in Shenzhen through the analysis of vehicle speed.



#### The Tool we use:

###### 1.kapler.gl git@github.com:keplergl/kepler.gl.git

###### 2.Deck.gl git@github.com:visgl/deck.gl.git

###### 3.From http://rstudio-pubs-static.s3.amazonaws.com/273435_fae224d6bfc24779a165ee49427bb57f.html

###### 4.From https://blog.csdn.net/u013410354/article/details/121304747?spm=1001.2014.3001.5501
