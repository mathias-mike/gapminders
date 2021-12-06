# Gapmindaers Dataset Analysis
## by Michael Mathias
### Dataset
Gapminder has collected a lot of information about how people live their lives in different countries, tracked across the years, and on a number of different indicators. In this project I will be analysing how `happiness_score` relates to 14 different indicators.
#### Happiness_score
This is the national average response to the question of life evaluations asking the following “Please imagine a ladder, with steps numbered from 0 at the bottom to 10 at the top. The top of the ladder represents the best possible life for you and the bottom of the ladder represents the worst possible life for you. On which step of the ladder would you say you personally feel you stand at this time?” This measure is also referred to as Cantril life ladder. Gapminder has converted this indicator's scale from 0 to 100 to easly communicate it in terms of percentage. 

The 14 indicators are;
1. `population_total`: Total population in each region by year [`indicator_1.csv`]
2. `aged_15plus_employment_rate_percent`: Percentage of total population, age group 15+, that has been employed during the given year. [`indicator_2.csv`]
3. `freedix_fh`: Freedom index is the average of political rights and civil liberties rating and is used to determine countries' freedom status. It ranges on a scale of 1(most free) to 7(least free). [`indicator_3.csv`]
4. `democracy_score_use_as_color`: Overall Polity score from the Polity IV dataset, calculated by substracting an autocracy score from a democracy score. It is a summary measure of a country's democratic and free nature. -10 is the lowest, 10 is the highest. [`indicator_4.csv`]
5. `corruption_perception_index_cpi`: Transparency internation's score of perception of curruption. Higher score indicates less curruption. [`indicator_5.csv`]
6. `income_per_person_gdppercapita_ppp_inflation_adjusted`: Gross domestic product per person adjusted for differences in purchasing power (in international dollars, fixed 2011 prices, PPP based on 2011 ICP). [`indicator_6.csv`]
7. `internet_users`: Percentage of the total population using internet. [`indicator_7.csv`]
8. `literacy_rate_adult_total_percent_of_people_ages_15_and_above`: Adult litracy rate is the percentage of people ages 15  and above who can, with understanding, read and write a short, simple statement in their everyday life. [`indicator_8`]
9. `owid_education_idx`: Education index calculated based on Avg years of schooling, taking values 0 as minimum and 15 as maximum. [`indicator_9.csv`]
10. `at_least_basic_water_source_overall_access_percent`: The percentage of people using atleast basic water services. This indicator emcompasses both people using basic water services as well as those using safely managed water services. Basic drinking water services is defined as drinking water from an improved source, provided collection time is not more than 30 minutes for a round trip. Improved water sources include piped water, boreholes or tubewalls, protected dug wells, protected springs, and packaged or delivered water. [`indicator_10.csv`]
11. `at_least_basic_sanitation_overall_access_percent`: The percentage of people using at least basic sanitation services, that is, improved sanitation facilities that are not shared with other households. This indiccator encompasses both people using basic sanitation services as well as those using safely managed sanitation services. Improved sanitation facilities include flush/pour flush to piped sewer systems, septic tanks or pit latrines; ventilated improved pit latrines, compositing toilets or pit latrines with slabs. [`indicator_12.csv`]
12. `roads_paved_percent_of_total_roads`: Roads, paved (% of total roads). [`indicator_12.csv`]
13. `suicide_total_deaths`: Total number of estimated deaths from self-inflicted injury. [`indicator_13.csv`]
14. `murder_total_deaths`: Total number of estimated deaths from interpersonal violence. [`indicator_14`]