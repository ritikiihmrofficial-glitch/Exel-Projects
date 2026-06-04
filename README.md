India CPI Inflation Case Study
This project analyzes India’s Consumer Price Index (CPI) to identify inflation trends across rural, urban, and combined consumer groups. It focuses on category-level behavior, month-to-month changes, and notable inflation spikes in food and other essential segments.

Overview
CPI is a fixed-basket index that measures changes in the general price level over time rather than a quantity that can be summed across months. The workbook explains that the dataset contains CPI values for multiple categories such as food, clothing, housing, fuel, health, education, transport, and miscellaneous goods and services. The analysis uses these values to study inflation patterns and compare trends across Rural, Urban, and RuralUrban sectors.

Dataset
The dataset begins in 2013 and includes monthly index values for a wide range of CPI components. The key columns include Sector, Year, Month, and category-level indices such as cereals and products, vegetables, fruits, milk and products, transport and communication, and the general index. The workbook also notes that some values were missing and were handled through running-average style imputation.

Data Cleaning
The workbook documents two main cleaning steps: handling missing values and converting the data format to numeric with consistent decimal precision. It also notes that CPI values are indices, so they should not be added across months as if they were direct prices. This makes trend analysis and percentage change more meaningful than totals.

Analysis Focus
The analysis appears to examine several important themes:

overall CPI movement over time.

food inflation and category volatility.

rural versus urban inflation differences.

the impact of COVID-era disruptions.

the relationship between CPI and crude oil prices.

category-specific trends in items like cereals, vegetables, milk, transport, and fuel.

Suggested README Extras
If you want this README to look more complete, add these sections:

A charts or findings section with 3–5 key insights.

A methodology section describing year-on-year change and smoothing.

A limitations section noting that CPI is an index, not an additive measure.

A screenshots section showing the workbook output or charts.

Short Example
A useful summary sentence for the README would be: “Food categories showed the strongest inflation volatility, while transport, housing, and general index movements helped explain broader CPI trends across rural and urban India”
