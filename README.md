# Uber Data Analysis With Python
**Uber Technologies, Inc.**, commonly known as **Uber**, is an American technology company. Its services include ride-hailing, food delivery, package delivery, couriers, freight transportation, and, through a partnership with Lime, electric bicycle and motorized scooter rental.

We will mainly use data regarding **Uber ride**

We will use Python to analyze data from Uber.

## We will use Python to:

* Check how long do people travel with Uber?
* What Hour Do Most People Take Uber To Their Destination?
* Check The Purpose Of Trips
* Which Day Has The Highest Number Of Trips
* What Are The Number Of Trips Per Each Day?
* What Are The Trips In The Month
* The starting points of trips. Where Do People Start Boarding Their Trip From Most?

## Project Steps:

### STEP 1:

The following libraries were been installed and imported before we start working on the 
dataset which was available . 
* import pandas as pd
* import numpy as np
* import datetime
* import matplotlib
* import matplotlib.pyplot as plt
* import seaborn as sns
* import calendar

### STEP 2:
Once the libraries above were been imported , We continued by locating our dataset in our local
Machine and passing it into our work enviroment and then storing it into a pandas dataframe . 

### STEP 3:
Once we had already read our data into a dataframe. we continue by then checking for missin values
in the data , this step is very important because without handling the missing values which are been 
found in the data appropriately, we might miss some important information and also note that missing 
values where not been drop from the dataset as all data which is available provide very important insides.

### STEP 4:
After the data was been clean , we use various functions to make sure the data was in the appropriate data
types and also all columns were orderly arrange. In addition to that, we use the various functions below to
get more insides from the data.
* The head function
* The info function

# Data Visualization
Once all the data was been properly analyse and clean , we carried out some visualization using  the following
libraries below. 

* matplotlib
* seaborn

The following visualization were been carried out below.

#### Visualization To Check The Purpose Of trip:

After analyzing the data provided , it was notice that most people use **Uber** just for business purposes.
What this means is, they just use it for a single day or less than few hours. 

#### Visualization To Check The Day Of The Week That Had the Highest Rides: 

It was clearly seen in the data that most people turn to use uber on Friday , therefore it will be wise or good 
if the company could provide more ads for their rides on friday or provide more discount on friday since people 
tend to used it more on friday.

## Also The Following Visualization Where Been Made After Analysis.

* Visualization to know the number of trips per day. 
* Visualization to know the month with the highest number of trips
* Visualization to know where most customers start their rides using **Uber**

# Insights:

Face some difficulties working with the date column. reason been converting it to the appropriate datetime format
kept upbringing some warnings but the data type was converted though. 

# Future Work:
I am looking at working more on seaborn plot types. some of the plot available both in seaborn and matplotlib are still quite unfamiliar to me.

# Stand Out Section:
More analysis was been done to know the average time which people had a ride and also knowing the maximum time which  someone 
use **Uber ride**












































