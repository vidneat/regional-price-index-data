# Regional Price Index: Digital Subscription Prices by Country

Local list prices for digital subscriptions, games and devices across 18 storefronts and four checkout channels: iOS App Store, Google Play, direct web checkout and Steam. Each price is converted to USD, with landed cost adjusted for taxes and gift cards, IMF PPP, work-hour affordability and a verification tier.

Every row was observed on an official storefront or vendor page. Storefronts that haven't been observed are left out, never estimated.

- **Website:** https://regionalpriceindex.com/
- **Open data page and methodology:** https://regionalpriceindex.com/open-data/ · https://regionalpriceindex.com/methodology/
- **Kaggle:** https://www.kaggle.com/datasets/regionalpriceindex/regional-price-index

## Files

Each monthly release has its own folder in `data/YYYY-MM/`:

| File | Contents |
|---|---|
| `prices.csv` / `prices.json` | One row per product × plan × storefront × channel × billing cycle |
| `countries.csv` | Storefront metadata: tax, gift cards, index score, IMF PPP rate |
| `history.csv` | Price change log with the USD value at the time |
| `datapackage.json` | Frictionless Data schema with column descriptions |

New releases are published on the 1st of each month. Each GitHub release is archived on Zenodo with a DOI.

## Cite

RegionalPriceIndex.com (2026). *Regional Price Index: Multi-Channel Digital Subscription Prices by Country*. https://regionalpriceindex.com/open-data/

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit "RegionalPriceIndex.com" and link to https://regionalpriceindex.com/.
