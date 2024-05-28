# Visualization-of-life-expectancy

# Life in Weeks Visualization

## Overview
"Life in Weeks" is a dynamic web visualization that presents an individual's life span as a series of weeks, each represented by squares on a grid. Each row consists of 52 squares, symbolizing one year, allowing users to visually comprehend their life in weeks according to various global life expectancy data.

## Data Sources
The visualization integrates life expectancy data from multiple authoritative sources:
- Swiss life expectancy is taken from the Swiss Federal Statistical Office (2021 data).
- U.S. life expectancy is sourced from the Social Security Administration (2020 data).
- Life expectancy for Chad and Russia is based on the United Nations World Population Prospects (2021 data).

Note: For Chad and Russia, the data reflects life expectancy at birth due to the unavailability of age-specific expectancy data.

## Features
- **Country and Demographic Selection**: Users begin by selecting their country, gender, and entering their age.
- **Weekly Life Grid**: The main visualization is a grid where each square represents one week of life.
  - **Dark Squares**: Indicate weeks already lived.
  - **Blank Squares**: Represent the remaining weeks, based on statistical life expectancy.
- **Time Scale**: Alongside the grid, a scale marks the year corresponding to each row.
- **Life Expectancy Display**: At the top of the grid, the years left, according to statistical data, are boldly highlighted.
  
This tool aims to offer a stark visualization of the passage of time, enhancing awareness of the finite nature of life through a weekly representation.

## Technologies
This project utilizes:
- **JavaScript**: For handling interactive elements and data manipulation.
- **D3.js**: Employed to draw and manage the visualization based on data dynamically.

## Getting Started
To run this project locally:
1. Clone the repository.
2. Open the `index.html` file in a browser to view the visualization.
3. Optional: Serve the project through a local server if modifications are made to the JavaScript files.

## Contribution
Contributions to improve the project are welcome. Interested contributors can fork the repository, make their changes, and submit a pull request.

## License
This project is released under the MIT License. See the `LICENSE` file for more details.
