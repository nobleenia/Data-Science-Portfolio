# Web Scraping Project: Nigerian Movies Data from IMDb
## Project Overview
This project is a web scraping exercise to gather data about Nigerian movies from the IMDb website. IMDb is a popular online database of movies, TV shows, and celebrities. In this project, we aim to scrape information about Nigerian movies, including titles, release years, durations, genres, directors, actors, ratings, and the number of votes.

## Acknowledgment
We would like to acknowledge the IMDb website (https://www.imdb.com/) for providing valuable information about movies, which served as the data source for this project. IMDb is an extensive online resource for movie enthusiasts, and we respect their terms of service during the scraping process.

## Project Requirements
To run this web scraping project, you will need the following software and libraries:

Python 3.x (Python 3.6 or later recommended)  
Pip (Python package manager)  
Required Python libraries (Install them using pip install):  
requests  
beautifulsoup4  
pandas  
numpy  

## Getting Started
Clone the project repository to your local machine:  
```git clone https://github.com/nobleenia/web-scraping-imdb-nigerian-movies.git```

Change your working directory to the project folder:  
```cd web-scraping-imdb-nigerian-movies```

Install the required Python libraries:  
```pip install requests beautifulsoup4 pandas numpy```

Run the Python script to start the web scraping process:  
```python scrape_nigerian_movies.py```

## Project Details
### Web Scraping Process
The web scraping process is conducted by making HTTP requests to the IMDb website's search results page, filtered by the country of origin (in this case, Nigeria). The script iterates through 50 pages to gather data about 13,365 movie titles.

The BeautifulSoup library is used to parse the HTML content of the webpages, extract relevant information, and store it in Python lists.

Extracted attributes include:  
Movie titles  
Release years  
Durations  
Genres  
Director names  
Actor names  
IMDb ratings  
Number of votes  

### Output
The scraped data is stored in a Pandas DataFrame and saved to a CSV file named "nigerian_movies.csv" in the project directory.

## Acknowledgments
We appreciate the IMDb website for providing a comprehensive platform for movie data. Please respect the website's terms of use and policies when conducting web scraping.