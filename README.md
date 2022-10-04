# surfs_up

# Surfs_Up
---
## Overview of Project
Our potential investor W.Avy has asked us to perform some data analysis on the weather as we intend to open a surf shop in Oahu. The initial findings looking at the weather throughout one year were positive and W.Avy would now like more specific analysis on the months of June and December. 

### Purpose
The purpose of this analysis is to look at weather statistics for the avaliable data in the months of June and December. This project intends to have the summary statistics on the temperatures during the months of June vs December. 

## Results
The analysis can be found in the notebook below:

[SurfsUp_Challenge.ipynb](https://github.com/gopivasanth/surfs_up/blob/db130e70ecf3bc101454026feb5c26a2203f8305/SurfsUp_Challenge.ipynb)

### June Summary Statistics:
The results from the June month analysis are summarized in the image below:

![June Temp Summary.PNG](https://github.com/gopivasanth/surfs_up/blob/d5a78905c0f4477daf330492605ad2ffdf5b981b/June_Summary.png)

### December Summary Statistics:

The results from the December month analysis are summarized in the image below:

![December Temp Summary.PNG](https://github.com/gopivasanth/surfs_up/blob/d5a78905c0f4477daf330492605ad2ffdf5b981b/Dec_Summary.png)

### Results Summary:
From the summary statistics we observe the following

1.  overall tempature remains relatively stable between the two months with mean temparatures only varying ~3.5 degrees F. 
    - The average temperatures in June fall around 75 degrees F and in December around 71 degrees F. 
    - Additionally we know from the standard deviations that this is not a significant difference, the standard deviations are 3.26 and 3.75 degrees F respectively. This means the averages deviate less than 2 std from the mean.

2. the temperatures in December do decrease slightly. We can see that the minimum temperature during december was 56 degrees F where as the lowest temperature in June was 64 degrees F. 
    - From this we know that although the average temperatures are not all that different there are colder days in December as opposed to June.

3. evaluating the quartiles for each data set we observe the june temperature spread seems to be quite even as the temperature difference between the 1st, 2nd and 3rd quartile is even at 2 degrees F. 
    - This is similar to the spread of the December temperatures where the difference between the 1st and 2nd quartiles is 2 degrees F and the diffrence between the 2nd and 3rd quartiles is 3 degrees F. 
    -- This means the spread of temperatures is quite similar only that the overall temperaturesare lower in December compared to June 
    
## Summary

Two additional queries were generated to look at the percipitation data for June and Decemeber. These can be found once again in the notebook:

[SurfsUp_Challenge.ipynb](https://github.com/gopivasanth/surfs_up/blob/db130e70ecf3bc101454026feb5c26a2203f8305/SurfsUp_Challenge.ipynb)


From these additionaly queries we can see observe
- low amounts of precipitation overall that during the months of June and December
- On average the percipitation during June was 0.14 and 0.22 in December; therefore we know on average there is more percipitation in December. 
- We can also see from this analysis that the max percipitation in the month of June was 4.4 where as in December it was 6.4. 
- We can see that during the heaviest rainfalls there is more percipitation in Decemeber as compared to June. 
