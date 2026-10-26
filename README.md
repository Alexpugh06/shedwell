# Shedwell

Storefront for the Shedwell reusable pet hair roller. It's one static page (`index.html`) served with GitHub Pages.

## Editing store settings

Open `index.html` and find the `STORE` object near the bottom of the script:

- `paymentLinks`: Stripe Payment Link for each pack (1, 2 and 3 rollers)
- `supportEmail`: address shown on the Contact page
- `legalName`: name used in the policies
- `handling` / `delivery`: shipping times shown across the site
- `bundles`: pack names and prices. If you change a price here, change the matching Stripe Payment Link too.

## Fulfilling an order

1. Stripe emails you the order and shipping address.
2. Place the order in CJ Dropshipping to that address.
3. Email the customer their tracking number when CJ provides it.
