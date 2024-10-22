# Climate Data Processing

## Overview

This repository contains the code and resources developed along with the University of Toronto Climate Research Department. The project aimed to address climate change-related challenges using statistical downscaling techniques and quantile mapping. The team worked on the challenges faced in Toronto Heat Vulnerability.

## Team Members

- Mevan Solanga
- Samudra Perera
- Asli Bese
- Peter Angelinos

## Problem Statement

Estimating where to place cooling stations in Toronto based on summertime hot days(number of days where Tmax > 30 °C) in the future (2071-2100) under SSP5-8.5 using downscaled CanESM5 data

## Results
<div style="display: flex; align-items: center;">
  <h3>Climate Survey<h3/>
<img src="https://github.com/Mevan-Solanga/Climate-Data-Processing/assets/118385727/ec32d472-daca-4b9e-a114-1fe96bd364a6" width=80%>
    <h3>Frquency Histogram of Temperatures in Toronto<h3/>
<img src="https://github.com/Mevan-Solanga/Climate-Data-Processing/assets/118385727/b4491dc9-1f58-4120-b4ca-67d3bf8521d2" width=50%>
          <h3>Simulated Heatmap using Existing Temperature Data<h3/>
<img src="https://github.com/Mevan-Solanga/Climate-Data-Processing/assets/118385727/b1fcb5cb-4e68-4157-8d2d-8dc8a7ea082e" width=50%>
                <h3>Projected Heatmap with Cooling Centers Overlaid<h3/>
<img src="https://github.com/Mevan-Solanga/Climate-Data-Processing/assets/118385727/e72e3dd7-e9a8-494c-9881-3329cec4e65e" width=50%>
</div>
Based on the findings from our data exploration and analysis, we chose to place cooling centers where there were no existing solutions, and that overlaid with low socio-economic areas. For our solution, we identified key locations owned by the City of Toronto that would be converted to makeshift cooling centers in these high risk areas. 


## Contents

- `climate-data/`: Contains maximum temperature and vapor pressure from the Daymet dataset along with compiled data.
- `flowcharts/`: Visual respresentation of.
- `main-analysis/`: Includes all code files and notebooks developed, visualizations, and any other relevant results.
- `test/`: Intial analysis trials.
- `toronto-shape-models/`: Contains the the overlayed toronto shape files.
- `README.md`: This file.

## Acknowledgments

[Documentation](https://utcdw.physics.utoronto.ca/UTCDW_Guidebook/README.html)
[UTCDW](https://utcdw.physics.utoronto.ca/)
