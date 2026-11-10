# ZEEFA: Visual Website Prototype

A static design preview. No cart, checkout, accounts or backend.

## Preview on your computer
1. Unzip/copy the `zeefa` folder anywhere.
2. Double-click `index.html` to open it in your browser.
   (Internet is needed once to load the Google Fonts.)

Optional local server: open a terminal in the folder and run `python3 -m http.server 8000`, then visit http://localhost:8000

## Upload to Exabytes
Upload the **contents** of the `zeefa` folder (not the folder itself) into `public_html` using File Manager or FTP, keeping the folder structure exactly as is.

## Replace placeholder images
All images are labelled placeholder graphics in `assets/images/`. To use real photos, save them with the same file name and extension, or edit the `src` in the HTML (for example `assets/images/p1.svg` to `assets/images/p1.jpg`). Use 4:5 portrait photos for products.

## Change colours or fonts
Edit the tokens at the top of `assets/css/style.css` (the `:root` block).

## Files
- `index.html` Homepage
- `shop.html` Collection (12 placeholder products)
- `product.html` Product detail template
- `about.html` About
- `contact.html` Contact (placeholders only)
- `assets/logos/` ZEEFA wordmark and Z monogram (SVG)
- `assets/js/main.js` Mobile menu toggle only

All product names, prices, and contact details are placeholders.
