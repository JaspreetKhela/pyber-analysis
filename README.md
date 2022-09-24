# PyBer Analysis

## Overview of the Analysis
The purpose of this analysis is to determine the differences between the total weekly fares by city type for a ride-sharing service. This analysis allows stakeholders to determine how to better serve different city-type demographics.

## Results
The tables below outline the ride-sharing data imported from the provided "city_data.csv" and "ride_data.csv" files including data covering the total rides, total drivers, total fares, average fare per ride, and average fare per driver.

_____

![city_data_df](https://user-images.githubusercontent.com/80941606/192052027-fa731e39-0952-4cd4-9089-db74d8f34d9e.png)

**Table 1**: Raw city data DataFrame.

_____

![ride_data_df](https://user-images.githubusercontent.com/80941606/192052043-7ef33175-b98d-4853-880c-3614a8c6374d.png)

**Table 2**: Raw fare data DataFrame.

_____

![pyber_(merged)_data_df](https://user-images.githubusercontent.com/80941606/192052155-0508755c-3133-4a9f-995a-5344270eaa78.png)

**Table 3**: Merged city and fare data DataFrame.

_____

![pyber_summary_df_formatted](https://user-images.githubusercontent.com/80941606/192052268-c275636d-fc68-4871-beb3-8ac6c5f11ecf.png)

**Table 4**: Merged city and fare data summary DataFrame.

_____

![sum_fares_pivot_table_2019_week](https://user-images.githubusercontent.com/80941606/192052289-696fe063-746d-4252-a79c-e70f817ca382.png)

**Table 5**: Weekly fares by city type summary DataFrame.

_____

Table 5 was used to construct the follwing graph.

_____

![PyBer_fare_summary](https://user-images.githubusercontent.com/80941606/192052309-8330b892-af29-435a-be6f-855e34ee14c2.png)

**Graph 1**: Weekly fares by city type graph.

_____

### General Trends
From Table 4, we can observe that the average fare per ride and per driver decreases from rural to suburban to urban areas. This demonstrates that the urban ride-sharing services are more affordable for customers, most likely due to the higher population density in urban areas in comparison to rural and suburban areas.

### Urban Ridership
From the graph above, we can see that the total fares tend increase as one goes from rural to suburban to urban areas; this may be explained by the increase in the population density going from rural to suburban to urban areas, which means that urban areas would have the most rides-sharing customers per unit time. In other words, urban ride-sharing customers generate most of the revenue for the ride-sharing service.

### Suburban Ridership
We can also notice that urban ridership increases during the summer months most likely to people (both from within and outside of the urban area) engaging in summer vacation activities. This can also be seen with suburban ridership but to a lesser extent.

### Rural Ridership
Rural ridership seems to remain roughly constant throughout the year. This perhaps can be explained by the idea that most of the users of rural ride-sharing services may be locals; in constrast, suburban and urban riders may include both locals and tourists.

## Summary
In summary, based on the results above, three business recommendations for addressing any disparities among the city types are:
* Revenue generated from urban ridership can be used to subsidize rural and suburban fare prices to increase ridership in rural and suburban areas (assuming that most customers are price-sensitive);
* More resources can be allocated for increasing urban ridership in an effort to establish a monopoly in that market; and
* Rural ride-sharing services can be discontinued due to low ridership in an effort to cut costs if the previous recommendations do not pan out.
