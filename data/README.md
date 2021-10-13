# Review data

## Articles

See [```bibliography```](bibliography) to learn the survey methodology and the selected works.

## Files

- `review.xlsx`: Excel datasheet with extracted features for _Google Scholar_ and _Scopus_ results.
- `scholar.csv`: CSV file with the features of articles found on _Google Scholar_.
- `scopus.csv`: CSV file with the features of articles found on _Scopus_.
- `hidserv-dir-onions-seen.csv`: CSV file with [official TOR metrics](https://metrics.torproject.org/hidserv-dir-onions-seen.html) around onions services.
- `analysis.ipynb`: Notebook for descriptive analysis


## Data format

### Tabular data for `review.xlsx`, `scholar.csv`, and `scopus.csv`. 

Article | Year | Discovery goal | Discovery method | Discovery bias | Discovery location | Discovery duration | Discovered hidden services | Daily discovery | Tools
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
[Article reference](bibliography) [$1-35, 44, 46$] | Year of onions discovery [$2012-2021$] | Reason for onions discovery [``Security``, ``Analysis``, ``Identification``, `Dataset creation`] | Technological technique/s for onions discovery [`Relays injection`, `Onions search engines`, `Repositories`, ``Tor crawling``, ``Non-onions search engines``] | Potential bias of discovered onions [``Random``, ``Search engine bias``, ``Repository bias``, ``Seeding bias``] | Targeted cyberspace for the discovering (from TOR perspective) [`Internal` (_deep web_), `External` (_surface web_), `Both`] | Number of days performing the discovery [_if specified_, $t > 0$; _if not_, $t = 1$] | Total number of active and unique discovered onion addresses [$n > 300$] | Number of active and unique onion addresses discovered per day [$ n / t $] | Resources, tools, or programs which supported the discovery

### Tabular data for `hidserv-dir-onions-seen.csv`. 

Date | Onions | Frac
| :-- | :-- | :-- |
UTC date when relays have been listed as running [`YYYY-MM-DD`] | Estimated number of unique .onion addresses observed by onion-service directories [$N > 0$] |  Total network fraction of statistics reported by onion-service directories [$0-1$]