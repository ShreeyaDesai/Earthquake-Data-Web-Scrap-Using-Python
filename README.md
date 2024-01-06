# Earthquake-Data-Web-Scrap-Using-Python
**Purpose:**
This Python script retrieves earthquake data from two tables on a Wikipedia page, performs basic operations on the data, and generates visualizations.

**Dependencies:**
pandas: Data manipulation library
numpy: Numerical operations library
statistics: Statistical functions library
matplotlib: Plotting library
google.colab: Colab-specific library for file handling

**Steps:
Data Retrieval:**
The script fetches earthquake data from the Wikipedia page List_of_earthquakes_in_2021 using pandas' read_html function.

**Table Selection:**
Two tables (table1 and table2) are extracted from the HTML data for further analysis.

**Data Presentation:**
The script prints the contents of both tables and saves them as CSV files.
The first table is modified by dropping a specific row.

**Basic Operations on Table 2:**
Basic statistical operations (sum, min, max, mean, median, mode) are performed on the 'Magnitude' column of table2.

**Graph Generation - Table 1:**
The script creates a line graph representing earthquake magnitudes over the years (2011–2021) using data from table1.
The graph is saved as 'graph1-1.png' and can be downloaded.

**Graph Generation - Table 2:**
Commented out in the code (to use after the first graph), this section plots a graph showing the relationship between intensity scale, magnitude, and depth from table2. The graph is saved as 'graph2.png' and can be downloaded.

**Usage:**
Run the script in a Colab environment.
View and download the CSV files for table1 and table2.
Examine and download the first graph ('graph1-1.png').
(Optional) Uncomment the section for the second graph and repeat the process.
