# EasyScrape-AmazonSuggest

Scrape Amazon Searchbar Suggested Terms

<img src="https://github.com/amazingjoe/amazingjoe.github.io/blob/main/imgs/Easyscrape.png" width="50%"/>

## Instructions

1. Install:

```
pip install easyscrape-amazonsuggest
```

2. Get Google Suggestions for a Search Term:

```python
from easyscrape_amazomsuggest import querysuggestions as AS

# Request suggestions for a search term
ASResults = AS.query("Mony Python")
ASResults

['monty python and the holy grail', 'monty python movies', 'monty python cast', 'monty python life of brian', 'monty python and the holy grail quotes', "monty python's flying circus", 'monty python rabbit', 'monty python quotes']
```

3. ES_query returns a list of strings with the results. You can optionally set the requests header as the second argument if you wish to include a custom header.