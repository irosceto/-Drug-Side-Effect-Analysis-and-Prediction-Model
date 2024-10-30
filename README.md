


pip install pandas matplotlib seaborn scikit-learn openpyxl Prepare Your Data:

Place the Excel file named side_effect_data.xlsx in the appropriate directory or update the path in the code accordingly. Run the Script:

Execute the Python script to perform data analysis and model training. The script performs the following steps: Data Loading: Reads the Excel file into a Pandas DataFrame. Exploratory Data Analysis (EDA): Displays the first few rows of the dataset. Prints dataset information and summary statistics. Checks for missing values and visualizes correlations between relevant features. Data Pre-Processing: Handles missing values by imputing numerical features with the mean and categorical features with the most frequent value. Encodes categorical variables and standardizes numerical features using pipelines. Model Building: Defines a preprocessing pipeline and integrates it with a RandomForestClassifier for model training. Splits the data into training and testing sets. Trains the model and evaluates its accuracy on the test set. Results: Outputs the model's accuracy to evaluate its performance. View Results:

The script prints the accuracy of the model after training and evaluation. This will be visible in the output console.
