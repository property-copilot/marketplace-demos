# Property Copilot Marketplace - Web Mockup

A static, single-page marketplace dashboard mockup that displays rental properties from Property Copilot.

## Features

- **Property Cards**: Displays 6 rental properties with photos, pricing, and details
- **Clickable Links**: Property cards link directly to actual Property Copilot property pages
- **Responsive Design**: Adapts to desktop, tablet, and mobile viewports
- **Interactive Elements**: Non-functional UI elements (search, filters) are disabled to indicate mockup status

## Structure

```
web/
├── index.html          # Main HTML structure
├── styles.css          # All styling (converted from Figma design)
├── script.js           # Property data loading and rendering
├── assets/             # Icons, logos, illustrations
│   ├── logo.svg
│   └── promo-illustration.svg
└── README.md           # This file
```

## How to View

### Option 1: Local File (Simple)

1. Open `index-standalone.html` directly in your browser
2. Properties will load automatically from `../data/prod_property_scraped.json`
