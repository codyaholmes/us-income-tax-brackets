# Historial U.S. Federal Income Tax Rates and Brackets with Max and Min Levels: 1913-2021

In some light political discourse with a friend, I realized that there was not many good sources for cleaned and tidy data to analyze historical marginal tax rates and brackets. This dataset is posted to fill that void.
## Data Source
Data is sourced from the Tax Foundation's [website](https://taxfoundation.org/historical-income-tax-rates-brackets/), titled *Historical U.S. Federal Individual Income Tax Rates & Brackets, 1862-2021*.

## Notes
- The original data source did not have max and min rate and bracket levels or max-to-min rate and bracket differences. Those were added by me.
- Some of the early years in the data were different levels of granularity (eg. classified as 1895-1912 instead of a single year). For that reason, I removed all years prior to 1913.
- Bracket values represent the bottom range of the bracket, not the top.
- Dollar amounts are represented by nominal dollars.
