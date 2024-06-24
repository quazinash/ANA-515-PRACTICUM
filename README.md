# ANA-515-PRACTICUM
#Justification
Missing Values
Empty Strings to NA: Empty strings do not provide any information and should be treated as missing values.
Specific "NA" Values: Sometimes, "NA" might be inputted as a string instead of being left blank. These need to be converted to proper NA values for consistency.
Dropping Rows with Missing Age: Age is crucial for this analysis. Without it, the row cannot contribute meaningfully to our study of age distribution.
Outliers and Errors
Age Range (18-100): This range is chosen based on typical age expectations for survey respondents. Values outside this range are likely errors or outliers that can distort the analysis.
Data Type Conversion: Ensuring correct data types allows for accurate computations and visualizations. For example, treating Age as numeric enables arithmetic operations and histogram creation.
Visualization
Histogram with Bin Width 5: This bin width provides a balance between granularity and readability, showing detailed distribution without being overly fragmented.
Bar Graph for Employment Status and Family History: This bar graph allows us to compare the counts of respondents based on their employment status and whether they have a family history of mental illness. By using different colors for family history, we can easily see the distribution and relationship between these two factors.
