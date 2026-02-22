# Daily Cleaning Services Website

Commercial cleaning, devanning & staffing solutions website for Auckland, New Zealand.

## Pages

- **Home** (`index.html`) — Main landing page
- **About** (`about.html`) — Company story and core values
- **Services** (`services.html`) — Overview of all services
  - **Commercial Cleaning** (`services/commercial-cleaning.html`)
  - **Logistics & Devanning** (`services/devanning.html`)
  - **MPI Accredited Person** (`services/accredited-person.html`)
  - **Staffing Solutions** (`services/staffing.html`)
- **Contact** (`contact.html`) — Quote request form and contact info
- **Privacy Policy** (`privacy.html`)

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Google Fonts (Inter)
- Vanilla JavaScript (mobile menu, dropdowns)

## Running Locally

```bash
# Option 1: Using npx serve
npm start

# Option 2: Using Python
python3 -m http.server 3000

# Option 3: Just open index.html in your browser
```

Then visit `http://localhost:3000`

## Deployment

This is a static site — deploy to any static hosting provider:

- **GitHub Pages** — Push to `main`, enable Pages in repo settings
- **Netlify** — Connect repo, deploy root directory
- **Vercel** — Import repo, deploy as static
- **Cloudflare Pages** — Connect repo, set build output to `/`

## License

Copyright 2026 Daily Cleaning Services Ltd. All rights reserved.
