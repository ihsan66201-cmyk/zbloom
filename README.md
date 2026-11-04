# Z BLOOM

A lightweight, responsive luxury fragrance storefront concept built with plain HTML, CSS, and JavaScript. It uses an original CSS bottle illustration, layered atmosphere, and a small local product catalog; no external image, 3D, payment, or database service is required.

## Run locally

Open `index.html` in a modern browser. For a local server, run:

```sh
python -m http.server 5173
```

Then visit `http://localhost:5173`.

## Shopping workflow

- Browse and cycle through the six example fragrances in the collection.
- Open a fragrance to choose a configured size and quantity.
- The shopping bag and order requests are saved in browser `localStorage` (`zbloom-bag` and `zbloom-orders`).
- Checkout validates delivery details and produces a clearly labeled order request reference. It does not charge a payment method or send the request to a server.
- Easypaisa and JazzCash are marked pending integration. There is no merchant payment integration or backend in this project.

Prices, note descriptions, and sizes are illustrative sample catalog data in `app.js`. Adjust these values before taking real orders. Product availability/stock is not connected to inventory. The newsletter form is a local demo interaction; it does not collect or transmit email addresses.

## Production notes

This is a self-contained frontend prototype rather than a production order system. A production launch needs a secure server-side catalog and inventory source, order API and storage, privacy and delivery policies, verified payment integrations, and real business contact details. No admin authentication or dashboard is included.
