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
![image](https://github.com/user-attachments/assets/54fb65fe-08e6-4b29-8874-a01e40400c17)
Rating Distribution: Histogram of IMDb ratings.
![image](https://github.com/user-attachments/assets/1522b03d-848a-4eae-b1f3-c45baf2d9792)

Yearly Rating Trends: Trends in IMDb ratings over time.
![image](https://github.com/user-attachments/assets/6d3d4cf8-8bcb-445a-a171-e297faa075d7)

Top Countries by Content: Analysis of content availability across countries.
![image](https://github.com/user-attachments/assets/161ff5c3-aa89-4c24-86cb-97e8d98199b4)

Most Common Genres: Most frequently occurring genres in the dataset.
![image](https://github.com/user-attachments/assets/6aac64eb-4a6d-4d1f-b229-395ae6aac55b)

Contributions are welcome! Please submit a pull request or create an issue to suggest improvements.

License
This project is licensed under the MIT License.
