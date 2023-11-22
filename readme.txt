Earthquake Analysis with PySpark
Overview
This project uses PySpark to analyze earthquake data. The analysis includes answering several questions related to earthquake
 occurrences, magnitudes, and geographic distribution.

Setup
1. Environment Setup
Make sure you have Python, PySpark, and MySQL installed.
 You can install the required Python packages using:

bash
Copy code
pip install pyspark mysql-connector-python
2. Dataset
Download the dataset and save it as a CSV file in the local directory.

3. MySQL Database
Set up a local MySQL database and configure the connection details in the Python script.

4. Running the Python Script
Execute the Python script (code_submission_pyspark.py) 
to read the dataset and push it into the MySQL database.

bash
Copy code
python code_submission_pyspark.py
PySpark Analysis
How to Run
Execute the PySpark script (code_submission_pyspark.py) to perform the analysis.

bash
Copy code
spark-submit code_submission_pyspark.py
Questions Answered
How does the Day of a Week affect the number of earthquakes?
What is the relation between the Day of the month and the Number of earthquakes that happened in a year?
What does the average frequency of earthquakes in a month from the year 1965 to 2016 tell us?
What is the relation between Year and Number of earthquakes that happened in that year?
How has the earthquake magnitude on average been varied over the years?
How does the year impact the standard deviation of the earthquakes?
Does geographic location have anything to do with earthquakes?
Where do earthquakes occur very frequently?
What is the relation between Magnitude, Magnitude Type, Status, and Root Mean Square of the earthquakes?
Code Structure
The code is organized into the following files:

code_submission_pyspark.py: Python script to push data into the MySQL database.
Also has a PySpark script to read data from the MySQL database and perform the analysis.
Additional Notes
Ensure that the CSV file is well-formatted with a header row.
Handle potential errors or edge cases gracefully in the code.
The assumptions made during the analysis are documented within the code as comments.

Contact
For any inquiries or issues, please contact bdevorshi100@gmail.com.