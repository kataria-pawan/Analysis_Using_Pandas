The IEA's latest "Global EV outlook" (https://www.iea.org/reports/global-ev-outlook-2024). The data is downloadable from their "data explorer" page:

https://www.iea.org/data-and-statistics/data-tools/global-ev-data-explorer'
You can download the data, or parts of it, by going to the above URL and selecting "ev sales," "cars," and "world" on the pull-down menus. Then click on "download data," and the CSV file should be downloaded to you.

Here are my six tasks and questions which contains filtering, grouping, multi-indexes, pivoting, piping, and also styling Pandas data frames. 

1. Read the EV data into a data frame. Remove rows from the "world" region. Keep only those rows with "EV sales" and "EV stock" parameters.
2. Create a data frame showing the number of cars sold each year, in each country, with a BEV ("battery electric vehicle") powertrain.
3. In which five countries have we seen the greatest percentage growth in the number of EV cars sold between 2019 and 2023?
4. Compare, for each year, the "stock" value with the "sales" value for cars with BEV powertrains. How much of the stock was sold, in each year, for each country? In what countries + years were sales equal to the stock? In what countries + years were sales less than 10% of the stock? Did such a low proportion of sales happen in 2022 or 2023?
5. Which five countries, on average, have the highest percentage of sales / stock?
6. Once again, compare, for each year, the "stock" value with the "sales" value for cars with BEV powertrains. Add a column, "sales_pct_stock", showing the percentage of the stock that was sold. Wherever that percentage is >= 75%, color it light green. Wherever it's <= 10%, color it light red.
