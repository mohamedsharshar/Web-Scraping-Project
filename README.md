# Web Scraping Sports Matches

This project involves web scraping to collect sports match data from a specific website, process it, and store it in a PostgreSQL database. 

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Database Schema](#database-schema)
- [License](#license)

## Overview

The `webscrab.ipynb` notebook scrapes match data based on the user-specified date. It retrieves match timings, results, team names, and the championship type, then saves this information to a CSV file and a PostgreSQL database.

## Technologies Used

- Python 3
- Requests
- BeautifulSoup
- Pandas
- PostgreSQL

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
2. **Install required libraries:
   Make sure you have the required libraries installed:
   pip install requests beautifulsoup4 pandas psycopg2
   
3. **Run the Jupyter Notebook:
   Open the webscrab.ipynb file in Jupyter Notebook and run the cells.
   When prompted, enter the date in one of the following formats:
   DD/MM/YYYY
   MM/DD/YYYY
   YYYY/MM/DD
   YYYY/DD/MM
4. **Check the Output:
   The results will be saved to a CSV file named mtv1.csv, and the data will be inserted into a PostgreSQL database named DB1.

## Database Schema

The database table matchs has the following schema:

Column Name	Data Type
CHAMPION_TYPE	VARCHAR(100)
TEAM_A	VARCHAR(100)
TEAM_B	VARCHAR(100)
TIME	TEXT
RESULT	VARCHAR(100)
License
This project is licensed under the MIT License - see the LICENSE file for details.

License
This project is licensed under the MIT License - see the LICENSE file for details.
