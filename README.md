
## Usage

From a terminal 

1. Install Requirements `pip3 install -r requirements.txt`

## Scrape Product Details from Product Page

1. Add URLS to [urls.txt](urls.txt)
1. Set selector in [selectors.yml](selectors.yml)
1. Run `python3 single_page.py`
1. Get data from [output.jsonl](output.jsonl)

## Scrape Products from Search Results

This scraper only scrapes product from the first page of search results

1. Add URLS to [search_results_urls.txt](search_results_urls.txt)
1. Set selector in [search_results.yml](search_results.yml)
1. Run `python3 searchresults.py`
1. Get data from [search_results_output.jsonl](search_results_output.jsonl)


### Search Results 
Each result would look similar

```json
{
"title": "Dell Latitude E6430 Laptop WEBCAM - HDMI - Intel Core i5 2.6ghz - 8GB DDR3-128GB SSD - DVD - Windows 10 Pro 64bit - (Renewed)",
"asin": "B01M293O5P"
}

```
