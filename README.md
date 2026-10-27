# Mike's China Beach

A responsive, multi-page restaurant website built with HTML, CSS, and vanilla JavaScript. I created this project during my first year of college while teaching myself front-end development. It was an early opportunity to turn a real small-business use case into a complete website: presenting a large menu clearly, helping customers find and contact the restaurant, and connecting visitors with pickup and delivery services.

**Live site:** [www.mikes-china-beach.com](https://www.mikes-china-beach.com/)

## Project Overview

The site introduces Mike's China Beach, a Chinese restaurant in Miami Beach, and organizes its customer-facing information across several focused pages. The project is fully static and is hosted with GitHub Pages under a custom domain.

## Features

- Responsive landing page with visual navigation to the site's main sections
- Full restaurant menu organized into 13 categories for easier browsing
- Sticky category navigation and automatic section highlighting while scrolling
- Swiper-powered image carousel with autoplay, pagination, and navigation controls
- Expandable price and size options for menu items
- Specialty-dish gallery with photos, descriptions, ratings, and prices
- Restaurant story, business hours, phone links, and an embedded Google Map
- Direct links to Google Maps, Uber Eats, DoorDash, and Beyond Menu
- Dedicated reviews, privacy policy, and terms-of-use pages
- Custom-domain deployment, `sitemap.xml`, `robots.txt`, and Google Search Console verification
- Mobile layouts for the homepage and menu at screen widths below 768 px

## Technology Stack

| Area | Technologies |
| --- | --- |
| Structure | HTML5 |
| Styling | CSS3, Flexbox, CSS Grid, responsive media queries |
| Interactivity | Vanilla JavaScript, DOM events, scroll-based navigation |
| UI library | Swiper.js 9 |
| Visual assets | Google Fonts, Font Awesome, custom restaurant images |
| Integrations | Google Maps, telephone links, third-party delivery platforms |
| Deployment | GitHub Pages, custom domain via `CNAME` |

No framework, build tool, package manager, or backend is required.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Homepage and visual navigation hub |
| `menu.html` | Complete categorized menu and interactive image carousel |
| `speciality.html` | Featured and popular dishes |
| `aboutus.html` | Restaurant history, location, hours, and ordering options |
| `review.html` | Customer-review presentation |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of use |

## Repository Structure

```text
Mike-s-China-Beach/
├── css/                  # Page-specific stylesheets
├── img/                  # Restaurant, menu, and interface images
├── js/
│   └── menu.js           # Carousel, scroll highlighting, and submenu logic
├── index.html            # Main landing page
├── menu.html             # Full restaurant menu
├── speciality.html       # Featured dishes
├── aboutus.html          # Story, map, hours, and order links
├── review.html           # Review cards
├── privacy.html          # Privacy policy
├── terms.html            # Terms of use
├── CNAME                 # GitHub Pages custom-domain configuration
├── robots.txt            # Search-engine crawling rules
└── sitemap.xml           # Search-engine page index
```

## Run Locally

Clone the repository:

```bash
git clone https://github.com/JunxuanChen314/Mike-s-China-Beach.git
cd Mike-s-China-Beach
```

Because this is a static site, you can open `index.html` directly in a browser. For more consistent local behavior, start a small HTTP server:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

An internet connection is needed to load Swiper.js, Google Fonts, Font Awesome, the embedded map, and other externally hosted resources.

## What I Learned

This first-year self-learning project helped me practice:

- Structuring a multi-page website with reusable visual patterns
- Building responsive layouts with Flexbox, Grid, and media queries
- Using JavaScript to connect page state with scrolling and user interaction
- Integrating third-party libraries and external services into a static site
- Organizing a large amount of real menu content for usability
- Deploying a website with GitHub Pages and configuring a custom domain and basic SEO files

## Current Scope

This repository contains the customer-facing front end only. Menu data and reviews are written directly in the HTML, and the website does not include a database, authentication, payment processing, an administrative dashboard, or its own ordering backend. Orders are handled through phone calls or external delivery platforms.

## Author

**Junxuan Chen**  
[GitHub](https://github.com/JunxuanChen314)

## License

No open-source license has been added. The source code and visual assets remain under the repository owner's copyright unless permission is granted separately.
