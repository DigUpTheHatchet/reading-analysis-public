
# Reading History Analysis

This repository hosts the Jupyter notebook I used to create the [Five Years of Reading](https://www.dyl.dev/posts/five-years-of-reading) blog post on my personal website [dyl.dev](https://www.dyl.dev) :) 

The [/data](./data) directory contains the source data for this analysis:
* `book_log_<year>.tsv` files contain my book log data, which was  exported from my [Book Log Google Sheet](https://docs.google.com/spreadsheets/d/1-IsFCGCjujAlEyGNrNsE4YEuAaP6yfWOOmWyAGZAAGA/edit?usp=sharing).
* `ratings_<year>.json` files contain data scraped from Goodreads (the Puppeteer code for this scraper might be added to this repo later).
* `Author Genders.txt` contains gender information for the authors from my Book Log. ChatGPT was used to retrieve this information.

There is also a `final_df.tsv` file. This is an export of the analysis-ready Pandas Dataframe. You can explore the contents of this dataframe on this publicly available [Google Sheet](https://docs.google.com/spreadsheets/d/1hu6RKi9gbpZ9N4WpCnXZXLMTNI-j81pPATsYQ-tmECs/edit?usp=sharing). 