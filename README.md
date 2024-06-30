# Week-6-Assignment

This project analyzes storm events in the United States for the year 1996, merging the event data with state information to produce a scatter plot showing the relationship between land area and the number of storm events, colored by region.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Setup](#setup)
- [Usage](#usage)
- [Plot Description](#plot-description)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project reads storm event data, filters it for 1996, and counts the number of events per state. It then merges this count with state information to create a scatter plot. The plot shows the number of storm events by land area and is colored by region.

## Data

- **Storm Event Data**: Contains records of storm events in the United States. Please see https://www1.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/ for the data. 
- **State Data**: Comes with base R and includes state names, abbreviations, regions, divisions, areas, and geographic centers.

## Setup

1. **Clone the repository**:
    ```sh
    git clone [https://github.com/yourusername/storm-events-analysis.git](https://github.com/yingyingli1111/Week-6-Assignment/tree/main)
    cd Week-6-Assignment
    ```

2. **Install necessary packages**:
    Ensure you have R installed, then install the required packages:
    ```r
    install.packages(c("readr", "dplyr", "ggplot2","stringr","tidyr"))
    ```

3. **Download the data**:
    Place your storm event data file in the project directory. Ensure the file path in the script matches the location of your data file. Please see https://www1.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/ for the data. The specific dataset used in this analysis is StormEvents_details-ftp_v1.0_d1996_c20220425.csv.gz. 

## Usage

1. **Run the script**:
    Open `Week-6-Assignment.R` in RStudio or your preferred R environment and run the script.

2. **View the output**:
    The script will create a scatter plot showing the number of storm events in 1996 by state area, colored by region.

## Plot Description

The scatter plot produced by the script includes:
- **X-axis**: Land area of each state in square miles.
- **Y-axis**: Number of storm events in 1996.
- **Color**: Represents different regions (Northeast, South, North Central, West).

The plot helps visualize the relationship between the land area and the frequency of storm events across different regions of the United States.

