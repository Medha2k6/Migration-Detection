# Migration Data Analysis and Prediction

This project utilizes a dataset containing migration-related data, including arrivals, departures, and net migration statistics. The primary tasks are to preprocess the data, apply various machine learning models, and analyze migration trends.

Data
File: data.csv
Columns: Country, Citizenship, Measure, Year, Value

Preprocessing
Replaced migration measures with numeric values.
Encoded categorical data.
Filled missing Value entries with median.
Dropped unused columns.

Modeling
Random Forest Regressor: Evaluated with R-squared score.

Visualization
Line plot showing annual migration growth.

Usage
Clone the repo:
git clone https://github.com/yourusername/yourrepository.git

Install dependencies:
pip install -r requirements.txt

Run the script:
python your_script_name.py

Dependencies
pandas
scikit-learn
seaborn
matplotlib
numpy
