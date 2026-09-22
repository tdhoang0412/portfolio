---
title: "New York City Taxi Trips: Trends, Patterns, and Change from 2015 to 2026"
layout: single
permalink: /pages/nyc-taxi-trip-analysis/
categories: [data-science, portfolio, pyspark]
description: "Analyzing NYC taxi trip patterns using PySpark"
header:
  overlay_color: "#24292e"   # dark GitHub-like header
---
<p style="text-align: justify;">
New York City (NYC) is the largest city in the United States by population. An iconic image of this city in the memory of many is a picture of many yellow cabs cruising through busy streets. 
</p>

![New York City taxies](../assets/images/nyc-real-yellow-taxi.jpg)

This analysis investigates all NYC taxi trips from 2015 to 2026 using trip records published by 
 <a href="https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page">
    the NYC Taxi and Limousine Commission (TLC)
  </a>
. We are interested in changes in user behaviours and shifts in the industry over the last ten years, especially during the adoption of mobile applications and after COVID-19. This should provide insights to help the company make suitable adjustments to the business in the coming years to adapt to constant changes in the current economy.

The market witnesses significant changes in the number of trips. As in Fig. 1, the total number of trips rises significantly from 2015 to 2019, an over 60% increase from around 220 million to over 360 million trips in those 5 years. The market took an enormous hit from COVID-19 in 2020, seeing a 50% drop as citizens of the city had to stay at home to prevent the spread of the pandemic. Since then, the market has gradually recovered to a mark of over 300 million trips in 2025, equivalent to 85% of the peak traffic in 2018.

![Taxi trips](../assets/images/trip_counts_by_year.png)

*Figure 1: Heatmap showing trip counts by hour (y-axis) and year (x-axis)*

The market share has seen a shift between the providers: yellow, green taxi, and for-hire vehicle (fhv) over the last decade (see Fig. 2). In 2015, over 70% of trips were with the traditional yellow and green taxi, in which a person takes a cab by waving at a nearby taxi. The fhv, in which a vehicle is pre-arranged, such as ordering an Uber, had only around 30% of the market share. The adoption of the fhv gradually increased its market share to a peak of 85% in 2020 and has been staying around that level for 6 years until now. It is unclear whether the expansion in the fhv's market share reached a saturation level at 85% in 2020 or the expansion trend was suspended by changes in user behaviours after COVID-19. Notably, the market share of green taxis has dropped to a critical level below 0.2% in 2025, questioning whether this taxi brand can continue to survive in the coming years. 
![Taxi trips 2](../assets/images/trip_count_composition_by_year.png)
