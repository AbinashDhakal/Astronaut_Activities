# Exploring Astronaut Activities in SQL
Welcome to the GitHub repository for the "Exploring Astronaut Activities in SQL" project. In this project, we analyze astronaut activities in a SQL database and visualize the results.

## Setup
To set up your integration and work with the provided SQL queries, follow these steps:

Create a PostgreSQL integration with the following credentials:
Integration Name: Astronaut Codealong
Hostname: workspacedemodb.datacamp.com
Database: astronauts
Username: astronauts
Password: astronauts
Note: You will need to set up your own integration using the provided credentials to run the SQL queries in this workspace.

### Data Exploration
Exploring the Data
We begin by exploring the dataset and looking at the table named evas. We examine various aspects of astronaut activities using SQL queries. The queries provide insights into EVAs (Extravehicular Activities) conducted by astronauts.

### Common Types of EVAs
We use CASE expressions to categorize different types of EVAs based on their purpose. The types include photography, collection, installation, retrieval, jettison, and repair. We then present the counts of each EVA type using a query that calculates the occurrences of these purposes.

### Extracting Material from EVAs
We extract information about the material extracted during EVAs, such as geologic material and rock samples. Using regular expressions, we identify the weight of the material collected and present it alongside the corresponding purpose.

### Total EVA Time by Astronauts
We analyze the duration of EVAs for different astronauts. By splitting the crew column and summing the durations, we calculate the total time each astronaut has spent in EVAs. The results are presented in descending order of total EVA time.

### Cumulative EVA Time Over Time
We investigate the cumulative amount of time spent in EVAs over the years and within different space programs. By using window functions and subqueries, we calculate and visualize the cumulative EVA time for each year and program.

### Usage
To explore the project and run the provided SQL queries, follow these steps:

Set up your PostgreSQL integration with the provided credentials.
Execute the SQL queries provided in the project's SQL files using your preferred SQL client or interface.
### Data Sources
The data used in this project is available in the SQL database named "astronauts." The specific tables and columns used are detailed in the SQL queries provided.
