This analysis explores the correlation between Google search trends for "Netflix," Netflix title additions, and COVID-19 cases in France over the past five years. By processing and visualizing these datasets, it is aimed to identify patterns and potential relationships.

- Data Processing
Google Trends: Extracted daily search counts, computed daily differences, handled missing values, and aggregated by month.
Netflix Data: Filtered date_added and type, reformatted dates, removed missing values, and grouped by type to count added titles per day.
COVID-19 Data: Extracted ICU and hospitalized patients, computed daily changes, handled missing values, filtered data until 2022-01-31, and aggregated by month.

- Merging & Visualization: Merged Google Trends and COVID-19 data (left join), replaced missing pre-2020 COVID values with 0, and created:
(1) Bar plots of new searches and COVID-19 cases per month.
(2) Line graph of total searches and cases over time.
(3) Daily Netflix title additions.