# IMDB Top 1000 Movies and Series API

## Overview
The IMDB Top 1000 API provides detailed information about the top-rated movies and series listed on IMDB in 2024. IMDB (Internet Movie Database) is one of the largest and most trusted sources of movie and television data, offering comprehensive insights into ratings, reviews, cast, and much more. This dataset is perfect for developers, analysts, and movie enthusiasts looking to explore trends in the film industry and discover popular titles.

---

## Content
The API provides:
- **Movie and Series Information**: Title, genre, director, cast, and synopsis.
- **Ratings**: IMDB ratings and the number of user votes.
- **Box Office Data**: Gross revenue for movies.
- **Release Information**: Year and country of release.

### Data Source
The data was scraped from the IMDB website for educational purposes and to enable users to perform custom analyses and build applications based on this dataset.

---

## Analysis Ideas
- **Revenue vs. Directors**: Explore how different directors influence the gross revenue of movies.
- **Actor Preferences**: Identify which genres are most commonly chosen by specific actors.
- **Actor Combinations**: Analyze the most successful actor pairings in terms of IMDB ratings and revenue.
- **Vote Patterns**: Examine the relationship between the number of votes and directors or stars.

---

## How to Access the API

### Prerequisites
- A RapidAPI account
- An API token (available through RapidAPI)

### Steps to Get Started

1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotfa-default/api/imdb-top-1000-movies-series) and create an account if you don’t already have one.

2. **Subscribe to the API**
   - Search for the "IMDB Top 1000 API" and subscribe to it.

3. **Get Your API Token**
   - After subscribing, navigate to the API's "Endpoints" section and copy your unique API token.

4. **Integrate the API**
   - Use the token to authenticate your requests. Here’s an example in cURL:
     ```bash
     curl -X GET "https://imdb-top-1000-movies-series.p.rapidapi.com/list/1" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: imdb-top-1000-movies-series.p.rapidapi.com"
     ```

---

## Example Endpoints

### 1. Movie or Series Details
Retrieve detailed information about a specific title:
```bash
GET /titles/{id}
```

### 2. Top Rated Titles
Get a list of the top-rated movies and series:
```bash
GET /bytitle
```

### 3. Search years
Search for movies or series by keywords:
```bash
GET /byyear
```

### 4. Filter by Genre
Get a list of titles filtered by genre:
```bash
GET /bygenre
```

---

## Contribution
If you have suggestions or would like to contribute to this project, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

