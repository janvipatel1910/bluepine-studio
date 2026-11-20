# Bluepine Studio – portfolio website

The website for **Bluepine Studio**, my freelance web design service for small local businesses in and around Wembley, London.

**Live site:** https://janvipatel1910.github.io/portfolio/

## What the site includes

- Services, starting prices (one-page websites from £99) and a simple price calculator
- Examples of my work
- A quote request form and contact by WhatsApp or email
- Light and dark mode, and a layout that works on phones

## Website templates

Full sample websites for different types of local business. The businesses, names, phone numbers and prices are all made up.

| Template | What it shows | Link |
|---|---|---|
| Restaurant | Menu with tabs, table booking, opening hours for the restaurant and the bar | [Open](https://janvipatel1910.github.io/portfolio/templates/restaurant/) |
| QR table menu | Guests scan a QR code, order from their phone, call a waiter or ask for the bill | [Open](https://janvipatel1910.github.io/portfolio/templates/restaurant/table.html?t=5) |
| Salon | Hair, nails and beauty price list, team and booking form | [Open](https://janvipatel1910.github.io/portfolio/templates/salon/) |
| Clinic | Treatments, fees, emergency information and appointment requests | [Open](https://janvipatel1910.github.io/portfolio/templates/clinic/) |
| Grocer | Weekly offers, product range and WhatsApp ordering | [Open](https://janvipatel1910.github.io/portfolio/templates/grocer/) |

The forms and the QR ordering are front-end demos only. They don't send data anywhere yet.

## Built with

- HTML, CSS and plain JavaScript (no frameworks)
- Hosted free on GitHub Pages

## Folder structure

```
portfolio/
├── index.html                 # Bluepine Studio homepage
└── templates/
    ├── restaurant/
    │   ├── index.html         # Restaurant demo
    │   └── table.html         # QR table menu demo
    ├── salon/index.html
    ├── clinic/index.html
    └── grocer/index.html
```

## Run it on your computer

```
git clone https://github.com/janvipatel1910/portfolio.git
cd portfolio
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Next steps

- Add a back end for QR table ordering (AWS Lambda, API Gateway and DynamoDB), so orders reach the kitchen
- Connect the quote form to email

---

© Janvi Patel · Bluepine Studio
