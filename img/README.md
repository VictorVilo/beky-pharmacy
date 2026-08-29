# BEKY Pharmacy — product images

Square 1000×1000 white-background JPEGs for the BEKY Holdings Pharmacy (Gigiri)
Glovo catalogue. Each file is named after the product's SKU / item code, e.g.
`456.jpg`, `abd.jpg`, `accu-lan.jpg`, `ado-125mg.jpg`.

Served for free through jsDelivr's CDN:

```
https://cdn.jsdelivr.net/gh/VictorVilo/beky-pharmacy@main/img/<sku>.jpg
```

The `Images (mandatory)` column of `BEKY_GLOVO_READY_REHOSTED.xlsx` already points
at these URLs.

If you replace an image, purge jsDelivr's cache for that file:
`https://purge.jsdelivr.net/gh/VictorVilo/beky-pharmacy@main/img/<sku>.jpg`
