# World Cup Data Mining
This is a project that performs data mining on the historical World Cup data from 1930 to 2018. It uses Python libraries such as pandas, plotly, and numpy to explore, analyze, and visualize the data. It also uses MS Excel files to store and manipulate the data.

## Data Source
The data source for this project is the Fjelstul World Cup Database, which is a comprehensive database that covers all 21 World Cup tournaments. The database includes 27 datasets (approximately 1.1 million data points) that cover all aspects of the World Cup, such as tournaments, teams, players, managers, referees, stadiums, matches, and awards. The data has been extensively cleaned and cross-validated.

The original database can be found here: https://github.com/jfjelstul/fjelstul-world-cup-database

For this project, some of the datasets have been modified and merged to create new datasets that are more suitable for data mining purposes. These new datasets are:

prepared_data.csv: This dataset contains information about each match played in the World Cup, such as the tournament year, the stage, the teams involved, the goals scored, the result, and the attendance.
prepared_goals_data.csv: This dataset contains information about each goal scored in the World Cup, such as the match id, the player who scored, the team who scored, the minute of the goal, and the type of goal (normal, penalty, or own goal).
players_teams.csv: This dataset contains information about each player who participated in the World Cup, such as their name, team, position, number of matches played, number of goals scored, number of assists made, and number of yellow and red cards received.

##Data Mining Tasks
The main data mining tasks performed in this project are:

Descriptive statistics: Calculating summary statistics such as mean, median, mode, standard deviation, variance, etc. for different variables in the data.
Data visualization: Creating charts and graphs to display the distribution and relationship of different variables in the data.
Association rule mining: Finding frequent itemsets and association rules among different variables in the data using the Apriori algorithm.
Clustering: Grouping similar objects in the data using different clustering algorithms such as K-means and hierarchical clustering.
Classification: Predicting the class label of an object in the data using different classification algorithms such as decision tree and logistic regression.
Technologies
This project is built with Python using Jupyter Notebook as an interactive environment. The main libraries used are:

pandas: A library for data analysis and manipulation.
plotly: A library for creating interactive charts and graphs.
numpy: A library for scientific computing and linear algebra.
sklearn: A library for machine learning algorithms and models.

## Installation
To run this project, you need to have Python 3 and Jupyter Notebook installed on your system. You can install Jupyter Notebook using pip:

pip install jupyter
Copy
Then you can clone this repository or download it as a zip file. To run the project, navigate to the project folder and execute:

jupyter notebook
Copy
This will open a web browser with a list of files in the project folder. Click on World Cup Case study.ipynb to open the notebook.

Usage
The notebook contains cells with code and comments that explain each step of the data mining process. You can run each cell by clicking on it and pressing Shift+Enter. You can also modify the code or add new cells according to your needs.

The notebook will show you the output of each cell as well as any charts or graphs that are generated. You can also download or export the notebook as a PDF or HTML file.

