# EGS Bedford — Electrical & Gas Services Website

**Live site: [https://gregkaighin.github.io/EGS_Bedford_Website/](https://gregkaighin.github.io/EGS_Bedford_Website/)**

A static front-end website for EGS Bedford, a family-run electrical and gas services company based in Bedfordshire. The site presents the company's services, accreditations, and contact details to prospective customers.

## Pages

- **index.html** — Main landing page including hero, services, about, owner bio, testimonials carousel, and enquiry form
- **gallery.html** — Photo gallery of completed work

## Features

- Responsive layout using Bootstrap 5.3.8
- Fixed navigation bar with mobile hamburger menu
- Full-viewport hero section with background image
- Trust bar displaying NICEIC and Gas Safe accreditation logos
- Services grid with six service cards
- Expandable About Us section (Bootstrap collapse)
- Owner biography with portrait
- Rotating testimonials carousel (auto-advances every 6 seconds)
- Enquiry / quote request form with thank-you modal
- Photo gallery page
- LinkedIn link in footer

## Technologies

- HTML5
- CSS3
- [Bootstrap 5.3.8](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/) (icons)

## Project Structure

```
egs-bedford-website/
├── index.html
├── gallery.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
│       ├── hero/
│       │   └── pexels-onics-energy.jpg
│       └── logo/
│           ├── niceic-logo.svg
│           └── gas-safe-logo.svg
└── README.md
```

## Running Locally

Open `index.html` directly in a browser, or serve the directory with any static file server:

```bash
python3 -m http.server
```

## Deployment

The site is hosted via GitHub Pages from the `main` branch of [GregKaighin/EGS_Bedford_Website](https://github.com/GregKaighin/EGS_Bedford_Website).
