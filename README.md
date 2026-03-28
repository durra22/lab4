Dataset description
The dataset used in this project is an Uber dataset that contains information about ride requests and trips. It includes both numerical and categorical features such as fare_amount, trip distance, pickup location, drop-off location, and passenger count. These features represent different aspects of ride-sharing operations and require preprocessing before analysis.

In this lab, the dataset was prepared by handling missing values and removing duplicates to ensure data quality. Outliers were detected and treated using the Interquartile Range (IQR) method, especially for fare_amount and trip distance. Numerical features were also normalized using Min-Max scaling and Z-score standardization to improve model performance.

After exploring the relationships between variables through visualization and correlation analysis, Principal Component Analysis (PCA) was applied to reduce dimensionality while preserving the most important information in the dataset.
