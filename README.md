# Analysis of Covid-19 situation in Russia (I used plotly library so graphs cannot shown there)
In this project I analysed the situation of Covid-19 the spreading in Russian regions between 29.01.2020 and 31.07.2020 .

The dataset is taken from the kaggle.com website: https://www.kaggle.com/kapral42/covid19-russia-regions-cases?select=covid19-russia-cases.csv

Below is data that I used for my analysis.

Region_ID - ID of the regions for table matching.
Region - region name in Russian.
Region Eng - region names in English.
Population - region population.
Day-Confirmed - confirmed cases for the day.
Day-Death - death cases for the day.
Day-Recovered - recovered cases for the day.
Confirmed - sum of confirmed cases in the region presently(cumulative).
Deaths - sum of death cases in the region presently(cumulative).
Recovered - sum of recovered cases in the region presently(cumulative).
Tests - number of performed tests (cumulative).
Control - people under medical control (cumulative).
Control_active - people under medical control at given day.
Recovered - people who recovered from Imported_SARS (cumulative).
Isol_idx - Self-Isolation index.

The main libraries I used are pandas and numpy.
