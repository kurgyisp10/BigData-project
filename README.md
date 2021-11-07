# BigData-project
Homework for BMEVIMIAV02

# Tasks
- Download data for every particle size (PM01, PM1, PM2.5, PM10) for the estimate territory of Budapest from 2021-01-01 to 2021-10-31 from [https://opensensemap.org/](https://opensensemap.org/).
- Exploratory data analysis: Based on Bamboolib, including bivariate cross effects (kétváltozós kereszthatás).
- Big Data visualization: Based on Datashader (HoloViz), interactive, heatmap of Budapest where the particle size is selectable. Cell aggregation in case of small zoom and interpolation due to the small number of measurements monitoring stations. (Indicate visually the interpolation.)
- Analysis: Predict with the help of a decision tree: district, time-of-day is workday or not, week, season. How much it indicates the difference from the median? (It is allowed to work with quantized differences.) Investigate the quality of the predictions.
