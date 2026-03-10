# Roberta Tripodi – Academic Website

This repository contains the source code for my personal academic website.

🌐 Website: https://robertatripodi.github.io  
👩‍🔬 Author: Roberta Tripodi  
🏛 Affiliation: INAF – Osservatorio Astronomico di Roma

The website presents my research activities in astrophysics, focusing on the formation and evolution of galaxies and supermassive black holes in the early Universe.

---

## Research Topics

My work focuses on:

- Galaxy formation in the early Universe
- High-redshift quasars
- Supermassive black hole growth
- JWST spectroscopy and imaging
- ALMA and NOEMA observations
- Gas, dust, and star formation in distant galaxies

---

## Website Structure

The website is a single-page HTML site designed to be hosted using GitHub Pages.

```
repository/
│
├── index.html
├── README.md
└── images/
    ├── profile.jpg
    ├── pub-lrd.jpg
    ├── pub-blr.jpg
    ├── pub-jades.jpg
    ├── pub-hyperion1.jpg
    └── pub-hyperion2.jpg
```

---

## Main Sections

The website contains:

- **About** – research background and interests  
- **Research Highlights** – key research topics  
- **Selected Publications** – representative first-author papers  
- **CV Snapshot** – positions and academic milestones  
- **Talks & Outreach** – invited talks and public engagement  
- **Contact** – email and ORCID information  

---

## Adding Your Images

All images should be placed inside the `images/` folder.

### Profile Picture

In `index.html` locate:

```
src="images/profile-placeholder.jpg"
```

Replace it with your profile image filename, for example:

```
src="images/profile.jpg"
```

Recommended size: **800 × 800 px**

---

### Publication Images

Each publication card includes an image placeholder like:

```
src="images/pub-lrd-placeholder.jpg"
```

Replace it with your figure image, for example:

```
src="images/pub-lrd.jpg"
```

Recommended format:
- square image
- ~800 px width

---

## Adding Paper Links

You can make publication images clickable by linking them to the paper.

Example:

```html
<a href="https://ui.adsabs.harvard.edu/abs/PAPER_LINK" target="_blank">
```

Using the NASA ADS abstract page is recommended.

---

## Deploying with GitHub Pages

1. Create a new repository named:

```
YOUR-USERNAME.github.io
```

Example:

```
robertatripodi.github.io
```

2. Upload the files:

```
index.html
README.md
images/
```

3. Go to:

```
Settings → Pages
```

4. Under **Build and deployment** select:

```
Deploy from a branch
Branch: main
Folder: / (root)
```

5. Save.

Your website will appear at:

```
https://YOUR-USERNAME.github.io
```

Deployment usually takes about **1 minute**.

---

## Updating the Website

To update the site:

1. Edit `index.html`
2. Commit the changes
3. Push to GitHub

GitHub Pages will automatically redeploy the site.

---

## Contact

Roberta Tripodi  
INAF – Osservatorio Astronomico di Roma  

Email: roberta.tripodi@inaf.it  
ORCID: https://orcid.org/0000-0002-9909-3491  
Publications: NASA ADS
