# Commerce Admin — Shopify-inspired analytics demo

A standalone, responsive dashboard inspired by the supplied Shopify admin screenshot. The reference numbers are **sample/demo data**, not real sales, visitors, orders, or customer records. This project is not affiliated with Shopify.

## Run

Open `index.html` in a modern browser, or serve this folder with a static web server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Included

- Reference sales: ₹668.48K
- Reference sessions: 19.2K
- Reference total orders: 776
- Reference online visitors: 194 (static sample)
- Reference conversion: 0.04%
- Interactive sidebar navigation, date range selector, report page, CSV export
- Demo product addition and local browser persistence (`localStorage`)
- Responsive desktop/mobile layout

## Caveats

- The chart is a stylized approximation of the image's daily trend, not raw chart data.
- Selecting a date changes the label only, because no historical backend data was supplied.
- Sales figures and product records are separate; adding products does not create orders or revenue.
- Product details were not provided in the two screenshots, so the product catalog starts empty.
- For production, connect authenticated APIs, a database, actual orders, and analytics events.
# shopify
