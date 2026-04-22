# Data Sources and Ownership

### FRED
The economic indicator data accessed using the fredapi python package which pulls from the Federal Reserve Bank of St. Louis' (FRED) api
- FRED Website: https://fred.stlouisfed.org/
- Python Package Docs: https://github.com/mortada/fredapi
- API is publicly accessible

### Y-Finance
The stock market data was access using the yfinance python package which pulls from the yahoo finance api
- Yahoo Finance Website: https://finance.yahoo.com/
- Python Package Docs: https://ranaroussi.github.io/yfinance/index.html
- API is publicly accessible

### Good Trends Data
The google trends data was accessed using the python package which pulls from the google trends data
- Google Trends Website: https://trends.google.com/trends/
- Python Package Docs: https://pypi.org/project/pytrends/
- API is publicly accessible

### SEC EDGAR
The SEC financial filing data was accessed using the secedgar python package and the SEC EDGAR public REST API
- SEC EDGAR Search Website: https://www.sec.gov/search-filings
- EDGAR Company Facts API(company CIK required): https://data.sec.gov/api/xbrl/companyfacts/CIK{cik_here}.json
- Python Package Docs: https://edgartools.readthedocs.io/en/latest/
- API is publicly accessible; requests require a User-Agent header identifying the project per SEC guidelines
