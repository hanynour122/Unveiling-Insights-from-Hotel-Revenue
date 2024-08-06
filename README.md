Hotel Revenue Data Analysis
Overview
This project focuses on analyzing hotel revenue data to uncover actionable insights and trends that can inform strategic decisions in the hospitality industry. The analysis includes comprehensive data cleaning, outlier handling, and temporal corrections, followed by exploratory data analysis and visualization to reveal key findings.

Data Cleaning and Preparation
Adding and Correcting Arrival Date
A new arrival_date column was created by combining several date-related columns. This adjustment was essential for calculating lead_time, which measures the number of days between the booking date and the arrival date.

Handling Missing Values
Dropping Irrelevant Columns: Columns with excessive missing values and deemed unnecessary were removed, thereby streamlining the dataset and enhancing data quality.
Imputing Missing Values: Missing values in the agent column were imputed using the mode, ensuring a more accurate representation of the dataset.
Correcting Temporal Errors
Negative lead_time values, caused by incorrect booking dates, were corrected by adjusting the year to ensure that the booking date precedes the arrival date.

Handling Outliers
Identification and Treatment of Outliers
Outliers in the adr (average daily rate) were identified using the Interquartile Range (IQR) method. Values outside 1.5 times the IQR above the third quartile or below the first quartile were treated to prevent distortion in the analysis.

Exploratory Data Analysis
Monthly Trends Analysis
Analyzed monthly trends in adr to identify periods of high and low demand throughout the year. This analysis provided insights into seasonal revenue fluctuations.

Customer Behavior Insights
Examined data on deposit types and meal plans to understand customer preferences. Visualizations such as pie charts were employed to illustrate the distribution of bookings by deposit type and meal plan.

Visualizations and Key Findings
Correlation Heatmaps
Created heatmaps to explore relationships between features such as adr, lead_time, and others. These visualizations helped identify key revenue drivers and underlying patterns.

Ensuring Data Accuracy
Thoroughly checked and corrected all date-related values to ensure accurate lead_time calculations and overall data integrity.

Conclusion
This project provided valuable experience in data cleaning, outlier handling, and data visualization. The insights gained offer actionable information that can inform strategic decisions in the hospitality industry.

Future Work
Future analyses could explore additional factors affecting revenue, such as geographic location or booking sources. Further refinement of data cleaning methods and additional visualization techniques could also enhance the depth of analysis.

