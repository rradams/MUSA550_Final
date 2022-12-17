---
title: "Predicting Home Prices"
date: 2022-12-16

tags: 
excerpt: "Use a Random Forest Regression to predict my in-laws' new home value, based on proximity to the highway and sales data from highway towns."
published: true
altair-loader:
  #altair-chart-1: "assets/charts/kmeans_plot.json"
hv-loader:
  #hv-chart-1: ["assets/charts/kmeans_map.html", "500"]
toc: true
toc_sticky: true
---

Our K-means analysis shows that, on average, otherwise similar homes are worth about 18% more in highway towns than in non-highway towns.

But what does this mean for my in-laws, specifically? I predicted their new home value using a random forest regression.

My model was trained and tested on 76,000 home sales in highway towns, based on the homes' acreage, livable square footage, year of sale, year built, story height, style of the home, and its distance to NC-540; the Raleigh city center, and the RDU airport.
