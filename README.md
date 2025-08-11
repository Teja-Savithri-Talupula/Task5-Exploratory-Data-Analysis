Exploratory Data Analysis (EDA) – Titanic Dataset

📌 Objective
Perform Exploratory Data Analysis (EDA) to extract insights from the Titanic dataset using visual and statistical exploration.

🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

📂 Dataset
File: `train.csv`  
The dataset contains passenger details such as demographics, ticket information, and survival status.

🔍 Steps Performed
1. Data Loading & Inspection
   - Used `pd.read_csv()` to load the dataset.
   - Checked structure with `.info()`, `.describe()`, and `.head()`.

2. Data Cleaning
   - Identified missing values with `.isnull().sum()`.
   - Checked data types and converted where necessary.

3. Univariate Analysis
   - Distribution plots for numerical variables using `sns.histplot()`.
   - Frequency counts for categorical variables.

4. Bivariate Analysis
   - Correlation heatmap for numeric features.
   - Pairplots to explore relationships.
   - Boxplots and countplots to compare survival rates.

5. Outlier Detection
   - Used boxplots to identify potential outliers in numeric features.

6. Visualization
   - Histograms, boxplots, scatterplots, and heatmaps for trend analysis.

7. Observations
   - Males had a lower survival rate compared to females.
   - Higher class passengers (Pclass 1) had higher survival rates.
   - Age distribution of survivors showed more children survived.

8. Summary of Findings
   - Passenger class, gender, and age significantly influenced survival.
   - Strong negative correlation between `Pclass` and `Survived`.
   - Some features require transformation for modeling.

📊 Deliverables
- Jupyter Notebook - containing all analysis steps.
- PDF Report- summarizing visuals and key insights.

