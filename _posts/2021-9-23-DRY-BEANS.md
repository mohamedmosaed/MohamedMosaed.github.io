---
layout: post
title: Dry Beans
subtitle: predict what kind of dry beans
cover-img: /assets/img/download (1).jpg
thumbnail-img: /assets/img/images.jpg
share-img: /assets/img/NYC_image.jpg
tags: [python]
---



## Introduction: 

Beans are a key food for much of the world’s population and a key ingredient in traditional recipes worldwide. Dry beans belong to the diverse Fabaceae family,sometimes referred to as Leguminosae. Beans are often called by other names, such as legumes or pulses. Yet not all legumes are beans and beans harvested in the green state are considered vegetables. Conversely, when harvested in the dried grain state, the edible seeds are called pulses. Beans are known as an economical source of protein. In addition, they are low in fat and a rich source of fiber and other important nutrients. Also, they are associated with a wealth of environmental and human health benefits, such as improved soil fertility and reduced risk of chronic disease. Dry beans are shelf-stable and can be kept safely at room temperature. They should be stored in a food-grade container or bag in a cool, dry, dark place. Warmer temperatures, higher humidity, and longer storage times can all contribute to longer cooking times. There are many countries in the world that producing dry bean. India takes the first place in the producing of dry beans, where it produces about 6.4 million Tonnes. The second place is Myanmar where it produces 5.47 million Tonnes. Then come Brazil, then United State of America, China and many more countries.

After knowing the importance of the dry bean how we can distinguish between them. There are about 18 kinds of dry beans in the world.This Machine learning algorithm is to predict the kind of beans out of 7 types of beans. The seven dry bean kinds are “Horoz, Bombay, Dermason, Barbunya, seker, Sira, Cali”. 


## DATASET: 
I obtain the training dataset form the UCI Machine Learning Repository website. For this dataset Seven different types of dry beans were used in this research, taking into account the features such as form, shape, type, and structure by the market situation. A computer vision system was developed to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification. For the classification model, images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. Bean images obtained by computer vision system were subjected to segmentation and feature extraction stages, and a total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains.
The 12 dimensions are:
-	Area: The area of a bean zone and the number of pixels within its boundaries.
-	Perimeter: Bean circumference is defined as the length of its border.
-	Major axis length: The distance between the ends of the longest line that can be drawn from a bean.
-	Minor axis length: The longest line that can be drawn from the bean while standing perpendicular to the main axis.
-	Aspect ratio: Defines the relationship between Major axis length and Minor axis length. 
-	Eccentricity: Eccentricity of the ellipse having the same moments as the region.
-	Convex area: Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
-	Equivalent diameter: The diameter of a circle having the same area as a bean seed area.
-	Extent: The ratio of the pixels in the bounding box to the bean area.
-	Solidity: The ratio of the pixels in the convex shell to those found in beans.
-	Roundness: Calculated with the following formula: (4*pi*Area)/(Perimeter^2)
-	Compactness: Measures the roundness of an object: (Equivalent diameter)/(Major axis length)
Form my data set I know it is a multivariate classification problem where my target is the Class columns which consist of seven different classifications which are are “Horoz, Bombay, Dermason, Barbunya, seker, Sira, Cali”. 


## Models:

I to further understand the data I used visualization tools like histograms and plots to further understand the data. The first visualization tool I used is heatmap to understand the correlation of the model and know if there is a high correlation or low correlation between the features. 
![image](https://user-images.githubusercontent.com/59778377/134404480-f5ab26f7-bd41-458c-8ecd-b8ac2e6257e5.png)
``Figure 1: correlation heatmap






