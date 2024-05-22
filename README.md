# Web Scraping Project: Extracting “Interstellar” Film Reviews from Letterboxd
## Overview
This fun project involves web scraping using the BeautifulSoup4 library. The goal is to extract film reviews from the movie [Interstellar](https://letterboxd.com/film/interstellar/reviews/) directed by Christopher Nolan, from the social media platform Letterboxd. Letterboxd is a community for film enthusiasts, where users can rate and review movies.

## Project Details
Film Title: Interstellar

Director: Christopher Nolan

Platform: Letterboxd

Purpose: Explore web scraping techniques and gather film reviews for analysis.
## How to Use This Python Project
1. Clone the Repository:
    Clone this repository to your local machine using the following command:

    ```
    git clone https://github.com/Alanjamlu34/NLP.git
    ```


2. Install Dependencies:
    Make sure you have Python installed.
    Install the required packages by running:
    ```
    pip install -r requirements.txt
    ```

3. Run the Web Scraping Script:
    - Open the `Review Letterboxd.ipynb` Jupyter Notebook.
    - Execute the code cells to scrape reviews from the provided Letterboxd URL.
    - The extracted data will be stored in a DataFrame.
4. Data Analysis (Optional):
    The notebook also includes an NLP section for analyzing the reviews. However, due to imbalanced data (too many 5-star ratings), the results may not be conclusive. You can explore alternative approaches or use a more diverse dataset for better insights.

> [!WARNING]
> Feel free to modify the code, add more features, or adapt it for other films.
Remember to respect website terms of use and robots.txt guidelines when scraping data.
