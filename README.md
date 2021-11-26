# Surf's Up Analysis

## Overview

W. Avy, a potential investor, has requested a weather analysis to ensure that the Surf n' Shake business plan is a sound investment and is sustainable year round. After providing an initial analysis on the precipitation he has asked for an additional analysis on temperature trends for the months of June and December. Using SQLite and SQLAlchemy in conjunction with numpy and pandas, Python queries were created to look at historical temperature data spanning multiple years for the months of June and December.

## Results
![june_temp_statistics](https://user-images.githubusercontent.com/90863226/143627043-d899bf19-5f1e-4ab0-bf61-fc3c1a56cc4d.png)
![dec_temp_statistics](https://user-images.githubusercontent.com/90863226/143627097-ff47ea76-0918-4b07-b004-648b6fb8df15.png)

- The average temperature in both June & December is in the low to mid 70's
- The temperature range for June is 64-85
- The temperature range for December is 56-83

## Summary
Based on our current Oahu weather analysis Surf n' Shake looks to be sustainable year round.  Average & high temps in both months are similar with averages in the 70's and highs in the 80's. These are ideal for both surfing and ice cream!

Although the analysis that has already been provided contains useful data points to aid in the decision making, I would still suggest completing the following additional analyses: 

1. Expand the temperature analysis to look at average highs/lows in all months, doing a deeper analysis in any months that have lower temperatures than what was found in the December analysis 
2. Perform an analysis on wind conditions, similar to what has already been performed on both precipitation and temperatures
