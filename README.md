# Payment · fanzx

A personal payment page for fanzx services. Built with vanilla HTML, CSS, and JavaScript for lightweight performance and simplicity.

**Live:** https://payment.fantzy.my.id

## Overview

This project provides a clean, fast payment interface supporting multiple payment methods. The application is hosted on Vercel with a custom domain configured through IDWebHost.

## Payment Methods

- Dana
- GoPay
- OVO
- QRIS (All Payment)

## Project Structure

```
./payment
├── index.html                      # Main page
├── favicon.ico                     # Favicon (ICO format)
├── favicon.svg                     # Favicon (SVG format)
├── favicon-96x96.png               # Favicon (96x96 PNG)
├── apple-touch-icon.png            # iOS home screen icon
├── site.webmanifest                # Web app manifest
├── web-app-manifest-192x192.png    # PWA icon (192x192)
├── web-app-manifest-512x512.png    # PWA icon (512x512)
└── media/
    ├── dana.jpg                    # Dana logo
    ├── gopay.jpg                   # GoPay logo
    ├── ovo.jpg                     # OVO logo
    ├── qris.jpeg                   # QRIS logo
    └── og-preview.png              # Open Graph preview image
```

## Technology Stack

- **HTML5** — semantic markup
- **CSS3** — styling and layout
- **Vanilla JavaScript** — no frameworks or dependencies
- **PWA Support** — installable web app capabilities

## Configuration

### Custom Domain

The domain `payment.fantzy.my.id` is configured via IDWebHost with DNS pointing to Vercel.

### Web App Manifest

The `site.webmanifest` file enables PWA functionality. Update display preferences and app icons as needed.

## Deployment

Hosted on Vercel with automatic deployments from the main branch. The custom domain is configured through IDWebHost's DNS management.

To deploy locally:
1. Clone the repository
2. Open `index.html` in a browser
3. Deploy to Vercel by connecting your GitHub repository

## License

Private — © 2026 fanzx. All rights reserved.
