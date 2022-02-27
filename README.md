# Surf’s Up with Advanced Data Storage and Retrieval

## Overview of the analysis

For this project, we’re working with an investor named W. Avy to determine the viability of a potential surf-and-ice cream shop in Hawaii. Weather data containing temps and precipitation from the island of Oahu has been provided to us in .sqlite format. Using Python, Pandas, and SQLAlchemy, we will analyze historical temps for the months of June and December to help assess the year-round sustainability of the shop. This will help to determine if this is a sound investment.  

## Results

Our analysis yielded two summary statistics tables, one for June and one for December, which helped to support our decision. Below are a few key findings.  

![June stats](/Resources/June_temp_stats.PNG) ![December stats](/Resources/Dec_temp_stats.PNG)  

- Over the period surveyed, a little more than 7.5 years, the lowest December recorded temperature (56 degrees) was just 8 degrees less than the lowest June recorded temperature (64 degrees).
- The maximum temperature recorded in June for this period was 85 degrees. Again, December wasn’t far off from this, with the highest recorded temp of 83 degrees.
- Similarly, average temperatures in June were just about 75 degrees, as compared to average December temps of 71 degrees.
- The inner quartile range is narrow in both months, indicating temps that don’t vary drastically in either month.

## Summary

Based on our review of historical temperature data for these two months, on the basis of temperature alone the island of Oahu seems viable for a surf-and-ice cream business. For the months of June and December, temps are consistent. The inner quartile ranges are narrow for both months, and the mins and maxes aren’t far off the 25th and 75th percentiles (respectively). Even better, December temps aren’t much lower than June temps.

To help round out our analysis, we would propose a couple of additional queries and visualizations:  
- Run summary stats for precipitation for both months to understand rainfall ranges and frequency. Warmth and precipitation are both important to the viability of the shop.
- Create a multi-line chart for June and one for December to show daily trends by year, with each line representing a year. The summary statistics alone tell a compelling story but getting a more detailed view might help to highlight more specifics to support the investment.
- Leverage existing code to build a better understanding of all months, and plot results to a series of box-and-whisker plots. If possible, plot these all on one chart, with the month on the x-axis. A view like this would help to summarize all this data in one spot.