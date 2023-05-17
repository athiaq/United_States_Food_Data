# United States Food Data

As consultants from United States of Food Data, our group was interested in investigating national trends in sales and consumption of various food and beverage products across all regions of the US in order to inform and improve decision-making for policy-makers. 

We used data from the U.S. Department of Agriculture’s (USDA) Economic Research Service arm whose mission is to forecast trends and anticipate complications in farming, food and the environment. Specifically, we looked at the Weekly Retail Food Sales datasets available on the USDA’s website. This data was collected through direct point of sales scanning of food and beverage products from a sample of retail food establishments across the US from 2019 - 2022. The Weekly Retail Food Sales data includes two summaries both of which are aggregated to food/beverage category and subcategory levels. One dataset is representative at the national level and the other is representative at the State level. The State level data has totals for 43 States. 

We chose to work with this data because it provided the opportunity to analyze food and beverage trends over the past four years at both the national and state levels. The Weekly Retail Food Sales data also provided in depth categories and subcategories of food/beverage products allowing us to really hone in on specific products and their popularity or lack thereof. Furthermore, the data provided information on the total value of sales and total volume of sales which provided another interesting avenue for analysis. 

To collect population data, we pulled a table from the US Census Bureau website. We also needed state latitude and longitude to be able to construct one of the visualizations we wanted. These were obtained from the Geoapify API.

Exploring the data revealed some of the limitations of the dataset, such as the missing states, and missing values. Cleaning up the data involved merging the main dataset with the new contextual tables we pulled in and calculating new values, like per capita spending, after those merges.

National Data Set - Included data for 4 years (2019-2022), however the 2019 data was only for 3 months (Oct-Dec), while 2020 and 2021 both included 12 months of data. 2022 included 9.5 months of data.  

Authors and Acknowledgment

Phil Lonsdale, Gina Massari, Emily Pompa and Athia Qureshi

Thank you to the instructors, and TAs for all of your help.
