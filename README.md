# Emerging Trend Radar

An independent research project testing whether search and online attention data
(Google Trends, Wikipedia pageviews) adds predictive information about publicly
traded consumer companies beyond price and conventional financial data.
A null result is an acceptable, useful outcome.

## Design principles
- Point-in-time integrity: every observation is stored immutably with its
  collection timestamp; no analysis uses information unavailable at that time.
- Pre-registered universe: tracked terms and companies are selected mechanically
  from companies' own SEC filings and frozen before any returns are examined.
- Baselines first: any signal is compared against price momentum and volume alone.
- Respect for data-source terms: identified clients, conservative request rates.

## Status
Storage layer and daily Wikipedia pageviews collection are running.
Google Trends integration awaiting API access.

## Policies
This project uses YouTube API Services.
- [Privacy Policy](PRIVACY.md)
- [Terms of Service](TERMS.md)
- [YouTube Terms of Service](https://www.youtube.com/t/terms) · [Google Privacy Policy](http://www.google.com/policies/privacy)
- 
Contact: dougfluttie@gmail.com
