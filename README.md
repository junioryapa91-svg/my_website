# De La Salle Secondary School Bomana

A five-page school information website created with semantic HTML5 and a hand-written, responsive CSS stylesheet. This Assessment 3 version extends the Assessment 2 site without Bootstrap, Tailwind, a downloaded theme or a page builder.

## Pages

- `index.html` — Home and school overview
- `about.html` — School information and values
- `programmes.html` — Lower and upper secondary subjects
- `gallery.html` — School gallery and events
- `contact.html` — Enquiry form and school map

## Run locally

Open `index.html` in a browser, or start a local server in this folder:

```text
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Responsive design

`styles.css` contains the shared navy-and-gold design system, editorial typography, reusable components and responsive layouts. Flexbox is used for the navigation, buttons and footer; CSS Grid is used for the hero, card collections, content layouts and form. Media queries restructure layouts for tablet and mobile widths, with fluid type and spacing, flexible images, a scrollable table region and a viewport-sized map. The stylesheet also includes keyboard focus styles, a skip link, readable colour contrast and reduced-motion support. No CSS framework, downloaded theme or page builder is used.

## Browser testing and evidence

Automated Chromium checks were run against all five pages at mobile (390 px), tablet (768 px) and desktop (1440 px) widths. They checked page loading, current-page navigation, image loading and viewport overflow. The contact form's native validation was checked with empty and valid sample data; the form was not submitted. The external Google Maps iframe was blocked during the automated run, so check that it displays when you test the site with an internet connection.

Homepage screenshots and test output from that run are in `evidence/`:

- `evidence/home-mobile.png`
- `evidence/home-tablet.png`
- `evidence/home-desktop.png`
- `evidence/browser-testing.txt`

Before submission, also open every page in your browser and check keyboard navigation, focus visibility and the live map. Publish the project, then add the required URLs:

- GitHub repository: **add your repository URL**
- Live responsive website: **add your deployed website URL**

## AI use declaration

Personalise this declaration to match your actual work and your institution's rules:

> I used GitHub Copilot to assist with reviewing the Assessment 3 requirements and improving the website's responsive CSS, accessibility details and project documentation. I reviewed the resulting work and take responsibility for understanding and testing the code I submit.
