# Earthquake Analysis with PySpark

This project analyses earthquake data using PySpark, a Python library for distributed computing. The dataset used in this analysis contains information about earthquakes, including their date, time, location, magnitude, depth, and other attributes.

Requirements
To run this project, you need to have the following installed:

1. Create a virtual environment using python3 - python3 -m venv venv
2. Activate the virtual environment and install the following packages in this environment- source venv/bin/activate
3. Python (with PySpark): pip install pyspark
4. install JAVA: https://www.geeksforgeeks.org/how-to-install-java-on-macos/
5. Jupyter Notebook (optional, for interactive analysis) - pip install notebook
6. Dataset: Download and place the dataset in a suitable location.
   
(Note- The above commands may differ for different operating systems)

Usage

1. Clone the repository: git clone https://github.com/Ambika0731/earthquake_analysis.git
2. Navigate to the project directory: cd earthquake-analysis
3. Launch Jupyter Notebook or your preferred Python environment: jupyter notebook
4. Open and run the earthquake_analysis.ipynb notebook to execute the analysis steps.

Analysis Steps
1. Data Loading: Load the earthquake dataset into a Spark DataFrame.
2. Data Cleaning: Clean the dataset by converting date and time columns to timestamps.
3. Filtering: Filter earthquakes with a magnitude greater than 5.0.
4. Aggregate Statistics: Calculate the average depth and magnitude of earthquakes for each earthquake type.
5. Magnitude Categorization: Categorize earthquakes into levels (e.g., Low, Moderate, High) based on their magnitudes.
6. Distance Calculation: Calculate the distance of each earthquake from a reference location.
7. Save Results: Save the final DataFrame as a CSV file.

References
1. PySpark Documentation
2. Dataset Source

Contributor: Ambika Gupta









