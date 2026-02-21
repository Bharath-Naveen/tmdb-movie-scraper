# TMDB Movie Listings Scraper (Notebook)
---
A simple Python notebook that scrapes movie listing pages from **TMDB (The Movie Database)** and exports the results to CSV for quick analysis.

> ✅ Portfolio note: This is an older notebook project that I’m publishing to showcase web scraping + data handling in Python.

---

## What is TMDB?

**TMDB (The Movie Database)** is a popular online database for movies and TV shows. It’s commonly used by developers and data folks to explore:
- movie metadata (titles, ratings, genres, cast)
- trending/popular content
- search and discovery experiences (like Netflix-style browsing)

This notebook scrapes publicly available *movie listing pages* to build a small dataset for analysis.
url: [themoviedb](https://www.themoviedb.org/movie)

---

## Problem / Why this exists

Many movie sites display valuable info (rating, genre, cast, etc.) on pages that are easy to browse, but not immediately available as a clean dataset.

This project solves that by:
- collecting the movie listing information from multiple pages
- converting it into a structured table (pandas DataFrame)
- exporting it to CSV for analysis / dashboards / downstream ML experiments

---

## Impact / What you can do with the output

With the exported dataset you can:
- compare rating distributions across pages
- analyze common genres in popular movies
- build a quick “movie explorer” dataset for visualization
- create a starter dataset for recommendation / clustering experiments (later)

Even though this is a small project, it demonstrates turning messy web content into an analyzable dataset.

---

## Skill Showcase

**Web Scraping**
- `requests`
- `BeautifulSoup (bs4)`
- working with HTML structure and parsing repeated elements

**Data Handling**
- `pandas` DataFrames
- cleaning / organizing scraped records
- exporting to CSV

**Engineering Habits**
- modular functions inside the notebook
- repeatable workflow (scrape → structure → export)

---

## How to run

### 1) Install dependencies
```bash
pip install -r requirements.txt
