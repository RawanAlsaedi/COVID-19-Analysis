# COVID-19-Analysis



## Project Overview

The goal of this project is to visualize the COVID-19 pandemic and its effects using various data visualization techniques. This analysis utilizes a comprehensive dataset of COVID-19 cases worldwide, covering the period from January 22, 2020, to March 29, 2020.


## Dataset

We will use [COVID-19 dataset](https://www.kaggle.com/imdevskp/corona-virus-report#covid_19_clean_complete.csv), which have 8 numeric features.

* Lat: Latitude of the location
* Long: Longitude of the location
* Date: Date of cumulative report
* Confirmed: Cumulative number of confirmed cases till this day
* Deaths: Cumulative number of deaths till this day
* Recovered:Cumulative number of recovered cases till this day


## Installation

To run this project, make sure you have the following packages installed:

```
pip install numpy pandas matplotlib seaborn
```

## Steps
1. Import the necessary packages:

```
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd
%matplotlib inline
```
2. Load the dataset:

```
df = pd.read_csv('covid_19_clean_complete.csv')
```

3. Explore the data:
 
   - Check the shape and columns of the DataFrame.
   - Calculate descriptive statistics and handle any missing values.



4. Visualizations:

   - Plot total confirmed cases over time.
   - Analyze top countries by confirmed cases and deaths.
   - Plot US's active cases over time
   - Visualize COVID-19 cases in the U.S.
 
## Results:

Below are visualizations that highlight key findings from the COVID-19 analysis.


## Total Confirmed Cases Over Time

<img src="https://github.com/RawanAlsaedi/COVID-19-Analysis/blob/main/img/Worldwide%20Confirmed%20Cases%20Over%20Time.png" alt="Worldwide Confirmed Cases Over Time" width="900" height="400">




## Top 10 countries with higher cases

<img src="https://github.com/RawanAlsaedi/COVID-19-Analysis/blob/main/img/Top%2010%20countries%20having%20most%20confirmed%20cases.png" alt="Top 10 Countries with Most Confirmed Cases" width="900" height="400">

##  Top 5 countries with the highest death



<img src="https://github.com/RawanAlsaedi/COVID-19-Analysis/blob/main/img/Top%205%20countries%20with%20the%20highest%20death.png" alt="Top 5 Countries with the Highest Deaths" width="900" height="400">

## US's Active Cases Over Time

<img src="https://github.com/RawanAlsaedi/COVID-19-Analysis/blob/main/img/US's%20Active%20Cases%20Over%20Time.png" alt="US's Active Cases Over Time" width="900" height="400">




## COVID-19 Cases Overview in the US

<img src="https://github.com/RawanAlsaedi/COVID-19-Analysis/blob/main/img/COVID-19%20Cases%20Overview%20in%20the%20US.png" alt="COVID-19 Cases Overview in the US" width="900" height="400">
