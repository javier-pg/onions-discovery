# Review data

## Articles

See [```bibliography```](bibliography) to learn the survey methodology and the selected works.

## Files

- `review.xlsx`: Excel datasheet with extracted features for _Google Scholar_ and _Scopus_ results.
- `hidserv-dir-onions-seen.csv`: CSV file with [official TOR metrics](https://metrics.torproject.org/hidserv-dir-onions-seen.html) around onions services.
- `analysis.ipynb`: Notebook for descriptive analysis


### Tabular data for `hidserv-dir-onions-seen.csv`. 

Date | Onions | Frac
| :-- | :-- | :-- |
UTC date when relays have been listed as running [`YYYY-MM-DD`] | Estimated number of unique .onion addresses observed by onion-service directories [$N > 0$] |  Total network fraction of statistics reported by onion-service directories [$0-1$]