# Advertising-Data-Analysis
Exploratory Data Analysis - Advertising Data <br>
In this repository, I have taken Advertising data from Kaggle and I have done:<br>
1. Data Preparation:<br>Data Loading and Initial Exploration: The notebook likely starts by loading the car price dataset using pd.read_csv() or a similar function. Initial exploration might involve checking the dataset's shape, viewing the first few rows using head(), and examining the data types of columns using info().<br>

2. Data Cleaning:<br> This step addresses data quality issues. It might include:<br>

Handling inconsistent entries: For example, standardizing car model names using string functions like str.replace() or str.lower().
Correcting erroneous values: Fixing incorrect prices, mileage values, or other numerical data.<br>

Dealing with missing values: Using imputation methods like filling with the mean, median, or using more advanced techniques.<br>

Removing duplicate entries: Identifying and deleting duplicate rows using the duplicated() and drop_duplicates() functions.<br>

Outlier Detection and Removal: This step focuses on identifying and handling extreme values that could skew the analysis. Techniques like box plots and statistical methods (e.g., Z-score, IQR) might be used to detect outliers.<br>
Outliers might be removed or treated using techniques like winsorization.<br>

3. Data Transformation:<br>

Data Normalization/Scaling:<br> This step involves adjusting the scale of numerical features to ensure they have a similar range. This is crucial for machine learning models. Common techniques include:<br>

Min-Max Scaling: Scaling features to a specific range (e.g., 0 to 1) using MinMaxScaler from scikit-learn.<br>

Standardization: Transforming features to have zero mean and unit variance using StandardScaler from scikit-learn.<br>
4. Data Visualization:<br>

Data Visualization:<br> This step uses visual representations to gain insights into the data. It might include:<br>

Histograms: Showing the distribution of numerical features like price, mileage, horsepower, etc. using histplot() or hist() functions from libraries like seaborn or matplotlib.<br>

Scatter plots: Exploring relationships between two variables (e.g., price vs. mileage) using scatterplot() or scatter() functions.
Box plots: Visualizing the distribution and identifying potential outliers for numerical features using boxplot() functions.<br>

Correlation matrix: Examining the relationships between multiple variables using a heatmap generated from the correlation matrix using heatmap() from seaborn.<br>

Feel free to download the code and data.
