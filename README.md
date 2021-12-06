# Gapmindaers Dataset Analysis
## by Michael Mathias
### Dataset
Gapminder has collected a lot of information about how people live their lives in different countries, tracked across the years, and on a number of different indicators. In this project I will be analysing how `happiness_score` relates to 14 different indicators.
#### Happiness_score
This is the national average response to the question of life evaluations asking the following “Please imagine a ladder, with steps numbered from 0 at the bottom to 10 at the top. The top of the ladder represents the best possible life for you and the bottom of the ladder represents the worst possible life for you. On which step of the ladder would you say you personally feel you stand at this time?” This measure is also referred to as Cantril life ladder. Gapminder has converted this indicator's scale from 0 to 100 to easly communicate it in terms of percentage. 

The 14 indicators are;
1. `population_total`: Total population in each region by year [`1_indicator.csv`]
2. `aged_15plus_employment_rate_percent`: Percentage of total population, age group 15+, that has been employed during the given year. [`2_indicator.csv`]
3. `freedix_fh`: Freedom index is the average of political rights and civil liberties rating and is used to determine countries' freedom status. It ranges on a scale of 1(most free) to 7(least free). [`3_indicator.csv`]
4. `democracy_score_use_as_color`: Overall Polity score from the Polity IV dataset, calculated by substracting an autocracy score from a democracy score. It is a summary measure of a country's democratic and free nature. -10 is the lowest, 10 is the highest. [`4_indicator.csv`]