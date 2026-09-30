# Sidekick Mobile

A small mobile-phone shop desk for browsing products, building in-store orders, and tracking order status. Orders and stock changes are saved in this browser using local storage.

## Run it

```sh
npm install
npm run dev
```

Open the local URL printed by Vite. Run the data checks with `npm test` and create a production build with `npm run build`.

## Shop desk

- Search and filter phone, audio, and accessory inventory.
- Add products to an order, adjust quantities, enter an optional customer name, and choose cash or card.
- Review recent orders, filter the order list, and mark in-progress orders ready for pickup.
- Browse inventory levels and identify low-stock products.

Product photos and display fonts load from Unsplash and Google Fonts when internet access is available.