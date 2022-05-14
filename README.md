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

['monty python shirt', 'monty python and the holy grail', 'monty python', 'monty python blu ray', 'monty python gifts', 'monty python and the holy grail merchandise', 'monty python flying circus complete series', 'monty python dvd', 'monty python door mat', 'monty python fluxx']
```

3. AS.query returns a list of strings with the results.