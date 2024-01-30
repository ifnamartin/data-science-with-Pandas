# Data science with Pandas: Restaurant KPIs

The purpose of this project is to conduct a detailed analysis of a dataset describing restaurants in Barcelona. The main objective is to identify relevant Key Performance Indicators (KPIs) that provide a meaningful insight into the performance of these establishments. Subsequently, these indicators are stored in XLS files, organized into specific groups of restaurants. This structure allows for a clearer and more detailed perspective on various aspects of restaurant performance in the city.

Pandas has been chosen for these actions due to its efficiency in vectorized operations, which are essential in calculating the necessary KPIs. Since the initial data filtering and transformation work is not too complex, we have decided to forgo the use of other libraries such as Pymongo and perform these tasks in Pandas as well.

PROJECT CONTENT

- pipeline_summary.pdf:
	Summary of the workflow used in the project.

- datamodel_graph.pdf:
	Graph data model used in the system.

- data folder:
	Contains the initial data in JSON format: restaurant_data.json and comments.json.

- python_code folder:
	Contains the Python code developed with Pandas for data analysis.

- database_dump folder:
	Stores "dumps" of auxiliary databases and results obtained during the analysis.

- grouped_results_excel folder:
	Contains Excel files with groups of restaurants based on specific criteria.

PROJECT DESCRIPTION

In this project, detailed information about restaurants and their associated comments is loaded. Then, restaurants in Barcelona open within a specific interval are filtered, considering criteria such as the city and opening dates. Auxiliary databases are created to facilitate the calculation of KPIs, including monthly information, opening hours, and peak hours. Calculations are performed to obtain relevant KPIs such as averages, sums, days open, occupancy rates, and repetitions of the term "wine" in comments.

Once the KPIs are obtained, the results are stored and grouped according to different criteria such as postal code, opening hours, and relevance of the term "wine." Finally, the grouped results are exported to Excel files for a more detailed analysis.
