## Synopsis

Data scraper for IMDB movies

## Installation

Install with npm
```
npm install git@github.com:IvanS1991/imdb-data-scraper.git
```

## API Reference

The module exports a single function
```
scrapeMovies(pageCount, ...genresList)
```
which returns a promise that resolves with unique movie objects
