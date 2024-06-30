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

This project reads storm event data, filters it for the year 1996, and counts the number of events per state. It then merges this count with state information to create a scatter plot. The plot shows the number of storm events by land area and is colored by region.

## Data

- **Storm Event Data**: Contains records of storm events in the United States.Please see https://www1.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/ for the data. 
- **State Data**: Comes with base R and includes information such as state names, abbreviations, regions, divisions, areas, and geographic centers.

## Setup

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/storm-events-analysis.git
    cd storm-events-analysis
    ```

2. **Install necessary packages**:
    Ensure you have R installed, then install the required packages:
    ```r
    install.packages(c("readr", "dplyr", "ggplot2"))
    ```

3. **Download the data**:
    Place your storm event data file in the project directory. Make sure the file path in the script matches the location of your data file.

## Usage

1. **Run the script**:
    Open `storm_events_analysis.R` in RStudio or your preferred R environment and run the script.

2. **View the output**:
    The script will create a scatter plot showing the number of storm events in 2015 by state area, colored by region.

## Plot Description

The scatter plot produced by the script includes:
- **X-axis**: Land area of each state in square miles.
- **Y-axis**: Number of storm events in 2015.
- **Color**: Represents different regions (Northeast, South, North Central, West).

The plot helps visualize the relationship between the land area and the frequency of storm events across different regions of the United States.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
