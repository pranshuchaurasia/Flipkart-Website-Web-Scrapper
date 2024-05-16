# Flipkart Website Web Scraper

This repository features a Python-based web scraping application designed to extract product data from Flipkart, one of India's largest online shopping sites. It utilizes Flask for the backend, allowing deployment both locally and on web servers such as Heroku.

## Introduction

The Flipkart Web Scraper is crafted for educational purposes to provide practical experience in web scraping using Python libraries, showcasing data extraction from real-world e-commerce platforms.

## Repository Structure

The repository is organized as follows:

- `app.py`: Main Flask application script with routes and scraping logic.
- `requirements.txt`: Lists all Python dependencies for the project.
- `Procfile`: Specifies commands for running the application on Heroku.
- `static/`: Contains static assets used in the web application.
  - `css/`: Includes CSS files for styling the application.
    - `main.css`
    - `style.css`
- `templates/`: Holds HTML templates for the web interface.
  - `base.html`: Base template for all pages.
  - `index.html`: Homepage template.
  - `results.html`: Template for displaying the scraping results.
- `*.csv`: Sample data files (`iphone11.csv`, `iphone13.csv`, `ufo.csv`) containing scraped information.

## Technologies Used

- **Python**: Core programming language.
- **Flask**: Web framework used to create the application.
- **HTML/CSS**: Used for creating and styling web pages.
- **Pandas**: Utilized for data manipulation during the scraping process.
