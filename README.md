# Web-Scraping-and-Data-Handling-of-JustWatch-Platform

This project is a Python-based web scraping application to extract data about movies and TV shows from [JustWatch](https://www.justwatch.com/in/movies?release_year_from=2000). The extracted data is processed using Pandas for filtering and analysis, and the results are exported to a CSV file for further use.

---

## Features

### 1. Web Scraping

Using **Selenium**, **BeautifulSoup**, and **Python**, this project scrapes the following details for movies and TV shows:

#### Movie Information:
- **Title**
- **Release Year**
- **Genre**
- **IMDb Rating**
- **Streaming Services Available** (e.g., Netflix, Amazon Prime, Hulu)
- **URL to the Movie Page**

#### TV Show Information:
- **Title**
- **Release Year**
- **Genre**
- **IMDb Rating**
- **Streaming Services Available**
- **URL to the TV Show Page**

#### Scope:
- Scrape data for **at least 50 movies and 50 TV shows** from JustWatch.
- Diverse datasets are ensured by starting with popular content or specific genres.

---

### 2. Data Filtering & Analysis

After scraping, the data is processed using **Pandas** to achieve the following:

#### Data Filtering:
- Include only movies and TV shows released in the **last 2 years** from the current date.
- Include only those with an **IMDb rating of 7 or higher**.

#### Data Analysis:
- Calculate the **average IMDb rating** for the scraped movies and TV shows.
- Identify the **top 5 genres** with the highest number of available content.
- Determine the **streaming service** offering the largest number of movies and TV shows.

---

### 3. Data Export

- The filtered and analyzed data is exported to a **CSV file**.
- The CSV file is stored in Google Drive, with **view access shared for anyone**.

---

## Installation and Usage

### Prerequisites:
- Python 3.x
- Selenium
- BeautifulSoup4
- Pandas
- Webdriver for your browser (e.g., ChromeDriver)


## Contributing

Feel free to fork this repository, submit pull requests, or raise issues. Contributions are always welcome!

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

