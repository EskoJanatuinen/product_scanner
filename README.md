# Product Scanner

A mobile-optimized QR code scanner for retrieving product information from our e-commerce store. The scanner reads product QR codes and redirects users to the corresponding product page on our website.

## How It Works

1. The user scans a product's QR code using their mobile device.
2. The scanner extracts the product number from the QR code.
3. The user is redirected to the product page in the organization's e-commerce system.

## Technologies Used

- JavaScript
- ZBar WASM
- HTML5 & CSS3

## ZBar WASM Source

The project utilizes ZBar WASM from `@undecaf/zbar-wasm`, a WebAssembly implementation of the ZBar barcode scanner.

## Deployment

Currently hosted on Cloudflare Pages. You can access it here:

🔗 [Product Scanner](https://product-scanner.pages.dev/)
