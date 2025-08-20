# Netflix-Data-Analysis

Overview
This project analyzes Netflix content data to uncover insights about the types of content available, their distribution across countries, release trends over time, and more. The analysis is performed using Python and popular data science libraries like Pandas, Matplotlib, and Seaborn.

Dataset
The dataset used in this project is netflix.csv, which contains information about Netflix shows and movies. The dataset includes the following columns:

show_id: Unique identifier for each show/movie

type: Type of content (Movie or TV Show)

title: Title of the show/movie

director: Director of the content

cast: Cast members

country: Country of origin

date_added: Date when the content was added to Netflix

release_year: Year the content was released

rating: Content rating

duration: Duration of the content (in minutes or seasons)

listed_in: Categories or genres the content belongs to

description: Brief description of the content

Project Structure
The project is organized in a Jupyter Notebook (netflix.ipynb) and includes the following steps:

Data Loading and Initial Exploration

Load the dataset and display the first and last few rows.

Check the shape of the dataset and data types of columns.

Identify missing values.

Data Cleaning

Handle missing values (if necessary).

Exploratory Data Analysis (EDA)

Analyze the distribution of content types (Movies vs. TV Shows) using a pie chart.

Identify the top 10 countries with the most content using a horizontal bar chart.

Examine the number of releases per year (for the earliest years).

Visualizations

Pie chart for content type distribution.

Horizontal bar chart for top 10 countries.

Additional visualizations as needed (e.g., time series for release years).

Key Insights
Content Type Distribution: The majority of Netflix content consists of Movies, followed by TV Shows.

Top Countries: The United States produces the most content, followed by India and the United Kingdom.

Release Trends: The dataset includes content released as early as 1925, with a gradual increase in releases over time.

Requirements
To run this project, you need the following Python libraries:

pandas

numpy

matplotlib

seaborn
