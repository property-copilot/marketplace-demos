# Property Copilot - Marketplace Demos

This repository hosts multiple demo instances of the Property Copilot marketplace platform.

## 🌐 Live URLs

- **Root Landing Page**: https://property-copilot.github.io/marketplace-demos/
- **Main Demo**: https://property-copilot.github.io/marketplace-demos/main/
- **AEI Demo**: https://property-copilot.github.io/marketplace-demos/aei/
- **Ascenda Demo**: https://property-copilot.github.io/marketplace-demos/ascenda/

## 📁 Repository Structure

```
marketplace-demos/
├── index.html          # Root landing page with demo links
├── main/              # Main marketplace demo
│   ├── index.html
│   └── assets/
└── [future-demos]/    # Add more demos here (e.g., acme/, enterprise/, etc.)
```

## 🚀 Adding a New Demo

1. Create a new directory for your demo (e.g., `acme/`)
2. Add your `index.html` and assets to that directory
3. Update the root `index.html` to include a card linking to your new demo
4. Push to `main` branch - GitHub Pages will automatically deploy

Your new demo will be accessible at:
`https://property-copilot.github.io/marketplace-demos/[your-demo-name]/`

## 🔄 Deployment

This repository uses GitHub Actions to automatically deploy to GitHub Pages on every push to the `main` branch.

- Workflow file: `.github/workflows/static.yml`
- View deployment status: https://github.com/property-copilot/marketplace-demos/actions
