# NYC Taxi Fare Analysis
NYC Taxi Fare Analysis: A Jupyter Notebook project that explores and visualizes a dataset containing taxi trip details in New York City. The analysis includes descriptive statistics, data cleaning, and histogram plots to examine the distribution of trip distances and total fare amounts.

-------------------------------------------

# Summary of Data Types for Each Variable:

Unnamed: 0 - int64
VendorID - int64
tpep_pickup_datetime - object
tpep_dropoff_datetime - object
passenger_count - int64
trip_distance - float64
RatecodeID - int64
store_and_fwd_flag - object
PULocationID - int64
DOLocationID - int64
payment_type - int64
fare_amount - float64
extra - float64
mta_tax - float64
tip_amount - float64
tolls_amount - float64
improvement_surcharge - float64
total_amount - float64
Minimum, Mean, and Max for the Two Variables:

# Trip Distance:

Min: 0.00 miles
Mean: 2.91 miles
Max: 33.96 miles
Total Amount Paid:

Min: -$120.30
Mean: $16.31
Max: $1200.29
Relevant and Irrelevant Columns:

# Relevant columns:
trip_distance, total_amount, and any other variables that might be of interest depending on the analysis objectives (e.g., passenger_count, payment_type, fare_amount, tip_amount).

# Irrelevant columns:
Unnamed: 0 (index column), store_and_fwd_flag (not essential for this analysis), and any other columns not directly related to the analysis objectives.

# Summary of the Data Visualization:
From the data visualization, we can observe the distribution of trip distances and total amounts paid. Most of the trips are concentrated within shorter distances, with a majority covering less than 3.06 miles. The distribution of total amounts paid follows a similar pattern, with a majority of trips having a total amount less than or equal to $17.80. These visualizations support the findings from the descriptive statistics and provide a graphical representation of the data to help stakeholders better understand the patterns and trends in the NYC taxi trips dataset.
Footer
