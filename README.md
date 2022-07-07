# INTRODUCTION

In this report, an Exploratory Data Analysis (EDA) will be preformed on Barcelona Open Data dataset, which is basically a dataset that Barcelona City Municipality collected in 2017 about its population demography, road accidents, transportations, and environment. The dataset is published freely on kaggle and it is retrieved from [Barcelona data sets](https://www.kaggle.com/datasets/xvivancos/barcelona-data-sets). The datasets has a lot of data files but the focus of this report will be on accidents, deaths, and air quality.

# DATASET

In this project, three files were used and their respective contents are as follow:

`Accidents_2017.csv`

| Variable          | Discription                                                                                           |
|-----------------|-------------------------------------------------------|
| ID                | The ID of the accident in the dataset                                                                 |
| District Name     | The name of the district of which the accident happened                                               |
| Neighborhood Name | The name of the neighborhood of which the accident happened                                           |
| Street            | The name of the street where the accident happened                                                    |
| Weekday           | The name of the day when the accident happened                                                        |
| Month             | The name of the Month when the accident happened                                                      |
| Day               | The date of the day when the accident happened                                                        |
| Hour              | The hour when the accident happened in the 24 format                                                  |
| Part of the day   | Categorical objects with three category represnting the period when the accident happened             |
| Mild injuries     | The number of mildly injured people in the accident                                                   |
| Serious injuries  | The number of seriously injured people in the accident                                                |
| Victims           | The total number of people involved in the accident; it is the summation of Mild and Serious injuries |
| Vehicles involved | The number of the vehicles involved in the accident                                                   |
| Longitude         | The geographical longitude where the accident happened                                                |
| Latitude          | The geographical latitude where the accident happened                                                 |

`air_quality_Nov2017.csv`

| Variable     | Description                                  |
|--------------|----------------------------------------------|
| Station      | The Station where the readings came from     |
| Air Quality  | A rating for the air quality; categorical    |
| Longitude    | The geographical longitude of the station    |
| Latitude     | The geographical latitude of the station     |
| O3 Hour      | The hour when the O3 reading was taken       |
| O3 Quality   | The quality of the O3 reading; categorical   |
| O3 Value     | The value of the O3 in the air               |
| NO2 Hour     | The hour when the NO2 reading was taken      |
| NO2 Quality  | The quality of the NO2 reading; categorical  |
| NO2 Value    | The value of the NO2 in the air              |
| PM10 Hour    | The hour when the PM10 reading was taken     |
| PM10 Quality | The quality of the PM10 reading; categorical |
| PM10 Value   | The value of the PM10 in the air             |
| Generated    | The specific date of the measurement         |
| Date Time    | A generated ID number                        |
