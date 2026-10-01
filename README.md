# The Deal Stock Scanner

A browser-based inventory lookup app for The Deal daily SOH CSV files.

## Features
- Barcode camera scan
- Audio Voice Dictation for price lookups ("Price is X dirhams") with Voice ON/OFF toggle
- Supplier / Consignment Item status display
- Manual Barcode / Product ID search
- QR Code Maker: paste item details or a barcode, preview the QR code, then save or cancel
- Camera scan limited to EAN-13, EAN-8, UPC-A, UPC-E, Code 128 and Code 39, with 2x zoom
- Manual keyword lookup: partial words, any order, across description, brand and VPN; tap a result for full details
- Shows Retail Price, Daily Closing SOH, and VPN
- Related items lookup by VPN
- IndexedDB storage for offline & large file support
- CSV file replacement preview and upload safety
- Mobile-friendly responsive design

## GitHub Pages Deployment
1. Extract all files to your GitHub repository (`cymongurung/full_pathfinder_sep`).
2. Go to **Settings > Pages** on GitHub.
3. Select `main` branch and `/ (root)` folder, then save.
