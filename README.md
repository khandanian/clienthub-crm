# ClientHub CRM

A responsive Persian RTL CRM and sales pipeline portfolio demo built with HTML, CSS, and JavaScript.

## Live demo
https://khandanian.github.io/clienthub-crm/

## Features
- Add, edit, and delete customers; notes and follow-up dates
- Manage sales opportunities, deal value, and probability
- Five-stage Kanban board with drag-and-drop and move buttons
- Dashboard metrics: customer count, open deals, pipeline value, and win rate
- Search and filter customers
- Export customer records to UTF-8 CSV
- Save records in browser localStorage

## Important limitations
This is a portfolio demo, not a production CRM. All sample customers and phone numbers are fictional. Data is stored only in the current browser and is not encrypted or synchronized. Do not enter sensitive real customer information. Clearing browser data may delete records.

## Local run
Open `index.html` or serve the folder using `python -m http.server 8080`.

## GitHub Pages
Enable **Settings → Pages → Source: GitHub Actions** once. The workflow at `.github/workflows/deploy.yml` publishes pushes to main and deliberately does not try to enable Pages using the restricted Actions token.
