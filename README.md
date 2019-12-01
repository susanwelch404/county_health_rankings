# County Health Rankings Project

I wanted to learn to work with map data in R. I am interested in healthcare and public health, so I thought an interesting dataset to work with would be the County Health Rankings released by the Robert Wood Johnson Foundation. You can read more about this data at their website at this link: https://www.countyhealthrankings.org/. This dataset is compiled from various sources, which you will find listed here: https://www.countyhealthrankings.org/explore-health-rankings/measures-data-sources/2019-measures. 

I chose just a few of the many measures from the full dataset to work with for this initial project: Poor or Fair Health, Adult Obesity, Adult Smoking, Physical Inactivity and Uninsured. I plan to examine more measures from the County Health Rankings in a later project.

There are many R packages for visualizing maps. After investigating a few of them, I chose to use the **urbnmapr** package, because it seemed relatively easy to use to make nice choropleth maps at the county level. Additional plots were made using **ggplot2** and **plotly**.

The original dataset can be found in the data subfolder. The file **chr_analysis.Rmd** contains the code for the analysis and discusses the results.

The report can be viewed at https://susanwelch404.github.io/county_health_rankings/.
