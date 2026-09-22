# BAKELY Product Operating System

This repository is the BAKELY internal operating application.

## Modules
- Dashboard
- Products
- Recipe Bible
- Ingredients
- Suppliers
- Costing
- Production Planning
- Batch Sheets
- Quality Control
- Product Photos
- Reports
- Version History
- Settings

## Current architecture
The GitHub Pages build is a static V1 and uses browser localStorage for demo/persistent browser data. It is not a shared server-side database.

For production, connect this UI to authentication, a shared database, server-side audit logging and object storage.

## Deploy
Enable **Settings -> Pages -> Source -> GitHub Actions**.

The workflow in `.github/workflows/pages.yml` deploys the `main` branch.

Repository: https://github.com/infosupport247-gif/Operating-Model
