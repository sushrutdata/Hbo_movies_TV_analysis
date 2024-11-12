# Hbo_movies_TV_analysis

HBO Max Data Analysis
Welcome to the HBO Max Data Analysis repository! This project provides an in-depth exploration and visualization of HBO Max content data, including analysis of genres, IMDb ratings, availability across countries, and other factors. The goal is to uncover insights that help understand content trends, viewer preferences, and engagement.

Project Overview
This analysis focuses on answering questions such as:

What are the top genres on HBO Max based on IMDb ratings?
How has the popularity of genres changed over time?
Which countries have the highest availability of content?
Is there a relationship between IMDb rating and number of votes?
Features
Data Cleaning: Handling missing values, data type conversions, and splitting genre data for detailed analysis.
Data Visualization: Insightful plots showcasing trends, such as:
Top genres by IMDb rating
Distribution of IMDb ratings across content
IMDb ratings by release year and by decade
Top 10 countries by content availability
Exploratory Analysis: Analysis of content types, rating trends, and correlation between ratings and votes.
Dataset
The dataset includes information about various titles available on HBO Max:

Title: Name of the content.
Type: Content type (movie, series).
Genres: Content genres, allowing multiple genres per title.
Release Year: Year the title was released.
IMDb Average Rating: IMDb rating for the title.
IMDb Number of Votes: Total votes on IMDb.
Available Countries: List of countries where the title is available.
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/HBO-Max-Data-Analysis.git
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Open and run the HBO Max.ipynb Jupyter Notebook:

bash
Copy code
jupyter notebook "HBO Max.ipynb"
Dependencies
This project uses the following Python libraries:

pandas
matplotlib
seaborn
Install them via the requirements.txt file or individually.

Results
The notebook contains visualizations and summaries of the findings, including:

Top Genres: Genres sorted by average IMDb rating.
Rating Distribution: Histogram of IMDb ratings.
Yearly Rating Trends: Trends in IMDb ratings over time.
Top Countries by Content: Analysis of content availability across countries.
Most Common Genres: Most frequently occurring genres in the dataset.
Contributing
Contributions are welcome! Please submit a pull request or create an issue to suggest improvements.

License
This project is licensed under the MIT License.
