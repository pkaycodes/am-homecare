# AM Homecare & Nursing Home

A simple, responsive one-page website for **AM Homecare & Nursing Home** — professional home care and nursing services in Ofankor, Accra.

> **Comfort, compassion & caring home.**

## What's on the site

- Hero introduction with call and WhatsApp buttons
- Eight services: home care, nursing home, elderly daycare, illness recovery, medication management, dementia care, physiotherapy and post-surgery care
- About section covering stroke recovery, diabetes and hypertension management, surgery recovery and elderly care
- Why choose us, a simple three-step care process, and contact details
- Links that call or open WhatsApp directly

## Contact details used

- **Phone:** 054 034 4837 / 020 785 9995
- **WhatsApp:** 054 034 4837
- **Location:** Ofankor, Accra–Nsawam Road, P.O. Box T130, Accra
- **Hours:** Open 24 hours, 7 days a week

## Run it locally

No build step is needed. Open `index.html` directly, or start a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

The site is hosted with **GitHub Pages** from the `main` branch (root folder):

**https://pkaycodes.github.io/am-homecare/**

To publish updates:

```bash
git add .
git commit -m "Update site"
git push
```

GitHub Pages will refresh automatically.

### Custom domain

The business card mentions `www.amhomenursing.com`. To use it, add a `CNAME` file containing the domain and configure the DNS records shown in the repository's **Settings → Pages** panel. The domain does not currently resolve, so the GitHub Pages address is used for now.

## Structure

```
am-homecare/
├── index.html          # Page content
├── styles.css          # All styling and responsive layout
├── script.js           # Mobile menu, scroll effects, reveal animations
├── assets/
│   ├── logo.svg        # Brand mark and favicon
│   ├── hero-care.jpg   # Hero photo
│   ├── about-care.jpg  # About photo
│   └── og-image.jpg    # Social sharing image
├── .nojekyll
└── README.md
```

## Image credits

Photos are from [Unsplash](https://unsplash.com) and used under the Unsplash License:

- Hero: [Centre for Ageing Better](https://unsplash.com/photos/a-woman-and-a-woman-sitting-on-a-couch-looking-at-a-tablet-UWZNnNQjraI) — *a man and woman sitting on a couch looking at a tablet*
- About: [Nappy](https://unsplash.com/photos/a-man-and-a-woman-smiling-YseYIoQ_WjY) — *a man and a woman smiling*

The logo mark was created for this site.

---

© AM Homecare & Nursing Home
