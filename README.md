# 3120-final-project

This is my final project for 3120. For my project, I am building an application called "MovieLens Insights", which would analyze and visualize trends in movies based on the TMDb API. My application enables users to explore movies based on genre, release year, popularity in order to provide meaningful insights into cinematic trends over time. 

I created a class that retrieves the data - including subclasses with different ways to retrieve.
In my analysis I have retrieved data based on:
- Genre: Fetch and analyze movies categorized under specific genres like Action, Comedy, or Drama.
- Release Year: Discover movies released in specific years and analyze their trends over time.
- Popularity: Investigate trends in movie popularity over time and visualize the most popular movies.

I created a class to process the data into a df for enhanced visualizations. I used to_datetime for the 'Release Date' column so that I can more easily visualize my data based on date. 

Finally, I created a class to handle data visualizations. I made two different types of visualizations:
-plotting the popularity of the top N movies (bar chart)
-plotting the trend of movie popularity over time (line chart)

I used the TMDb API as my movie database. It is a popular API for accessing information about movies, including popularity, release date, and ratings. I looked at columns like Title, Release Date, Popularity Score, and Average Rating.

Instructions:
1. Clone my repository
git clone https://github.com/arsmnvj/3120-final-project

2. Once you download the .env file I gave you (containg the API key), make sure to put it in the same directory as my repository. Then, add .env to .gitignore (in order to ensure security).

3. Open the Jupyter notebook file MovieLens.ipynb

4. Run each cell

5. You're done!!

Youtube video link: https://youtu.be/39yeyVF9MIM?si=jmNoEcY6GBTM2YYm