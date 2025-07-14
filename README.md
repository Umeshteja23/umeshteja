Project Summary -
This project focuses on exploring and analyzing the Play Store apps data and user reviews to identify key factors driving app engagement and success. The initial data loading and wrangling steps involved:

Loading Datasets: Two datasets, Play Store Data.csv and User Reviews.csv, were loaded into pandas DataFrames. Handling Missing Values: Missing values in both datasets were removed using the dropna() method. Handling Duplicates: Duplicate rows were removed from both datasets using the drop_duplicates() method. Data Cleaning and Type Conversion: The 'Installs' column in the Play Store data was cleaned by removing ',' and '+' characters and converted to a numeric type. The 'Price' column was cleaned by removing the '$' sign and converted to a numeric type. The 'Size' column was processed to convert 'M' and 'k' to their numerical equivalents, handle 'Varies with device' by replacing it with NaN, and then impute missing values with the median size. The column was converted to a numeric type. The 'Reviews' column was converted to a numeric type. Merging Datasets: The two dataframes were merged based on the 'App' column using an inner merge to create a combined dataframe (merge_df) containing app details and their corresponding user reviews and sentiment analysis. The merged dataset provides a comprehensive view, allowing for the analysis of relationships between app characteristics (like category, rating, size, installs, type, and price) and user sentiment metrics (sentiment, sentiment polarity, and sentiment subjectivity). The next steps will involve visualizing these relationships and extracting actionable insights to understand what drives app success in the Play Store.

GitHub Link -
Provide your GitHub Link here.

Problem Statement
Explore and analyse the data to discover key factors responsible for app engagement and success..

Define Your Business Objective?
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Each app (row) has values for category, rating, size, and more. Another dataset contains customer reviews of the android apps.Explore and analyse the data to discover key factors responsible for app engagement and success.

General Guidelines : -
Well-structured, formatted, and commented code is required.

Exception Handling, Production Grade Code & Deployment Ready Code will be a plus. Those students will be awarded some additional credits.

The additional credits will have advantages over other students during Star Student selection.

    [ Note: - Deployment Ready Code is defined as, the whole .ipynb notebook should be executable in one go
              without a single error logged. ]
Each and every logic should have proper comments.

You may add as many number of charts you want. Make Sure for each and every chart the following format should be answered.

# Chart visualization code
Why did you pick the specific chart?
What is/are the insight(s) found from the chart?
Will the gained insights help creating a positive business impact? Are there any insights that lead to negative growth? Justify with specific reason.
You have to create at least 20 logical & meaningful charts having important insights.
[ Hints : - Do the Vizualization in a structured way while following "UBM" Rule.

U - Univariate Analysis,

B - Bivariate Analysis (Numerical - Categorical, Numerical - Numerical, Categorical - Categorical)

M - Multivariate Analysis ]
