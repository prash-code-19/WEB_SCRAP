# Web Scraping and API Practice

A hands-on collection of Jupyter notebooks for learning how to work with web APIs and scrape HTML pages with Python. The exercises use public APIs and the practice sites [Quotes to Scrape](https://quotes.toscrape.com/) and [Scrape This Site](https://www.scrapethissite.com/).

## Contents

| File or folder | Description |
| --- | --- |
| `APIs.ipynb` | Introduces HTTP requests and status codes, fetches data from the Stephen King and Pokémon APIs, and practices parsing a countries page with Beautiful Soup. The country data is exported to CSV. |
| `solution.ipynb` | Fetches paginated quote pages and saves the HTML responses for local parsing exercises. |
| `scrapped_data/` | Saved HTML pages and CSV output used by the notebooks. |

## Requirements

- Python 3
- Jupyter Notebook
- `requests`
- `beautifulsoup4`
- `lxml`
- `pandas`
- `numpy`

Install the Python packages in your environment:

```bash
python -m pip install requests beautifulsoup4 lxml pandas numpy jupyter
```

## Getting started

1. Open a terminal in this folder.
2. Install the requirements listed above.
3. Start Jupyter:

   ```bash
   jupyter notebook
   ```

4. Open either notebook and run its cells from top to bottom. Start with `APIs.ipynb` for the API and HTML-parsing exercises, then use `solution.ipynb` for paginated quote scraping.

The notebooks make HTTP requests, so an internet connection is needed to retrieve fresh data. Saved examples in `scrapped_data/` are available for local inspection.

## Notes

- These notebooks are learning exercises; cells may need adjustment as APIs and websites change.
- Run the notebooks from this folder so their relative paths to `scrapped_data/` resolve correctly.
- Follow the target sites' terms and usage guidance when making requests.
