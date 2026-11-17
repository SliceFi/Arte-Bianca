# Arte Bianca — website demo

A complete, responsive, dependency-free static website for **Arte Bianca**, an Italian pizzeria in Den Haag. Built with HTML, CSS, and a little JavaScript, so it can be hosted for free with **GitHub Pages**.

## Files

```text
arte-bianca-github/
├── index.html                Main website
├── styles.css                Responsive monochrome design
├── script.js                 Mobile navigation, menu tabs, photo gallery
├── .nojekyll                 Ensures GitHub Pages serves the files directly
├── README.md                 These instructions
└── assets/
    ├── favicon.svg
    └── images/
        ├── hero-two-pizzas.webp
        ├── parma-rucola.webp
        ├── verdure-light.webp
        ├── bianca-pizza.webp
        ├── parma-light.webp
        ├── three-pizzas.webp
        ├── verdure-detail.webp
        └── verdure-dark.webp
```

## Preview on your computer

Double-click `index.html` to open it in a browser. No installation, build tools, or internet connection is needed to see the website and its photos (external delivery and social links require internet).

## Publish on GitHub Pages

1. Sign in to GitHub and select **New repository**.
2. Call it `arte-bianca-website`, select **Public**, and create the repository.
3. Select **Add file → Upload files**. Upload **all files and folders inside `arte-bianca-github`**, including `index.html` at the repository root (not nested in an extra folder). Alternatively, extract the ZIP and drag its contents into GitHub.
4. Click **Commit changes**.
5. Go to **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, `main`, `/ (root)`, then **Save**.
7. Your site will be published at `https://YOUR-USERNAME.github.io/arte-bianca-website/` once GitHub has deployed it.

**Important:** If GitHub won't upload a hidden `.nojekyll` file, that's fine; the page still works. The `.nojekyll` file simply prevents Jekyll processing.

## Editing the site

- **Text, links, and menu prices:** open `index.html` in a code editor.
- **Fonts, colors, layout:** edit `styles.css`.
- **Menu tabs and gallery interaction:** edit `script.js`.
- **Food photos:** replace files in `assets/images/` with the same filenames or update the references in HTML/CSS.

## Verified business links

- Uber Eats: https://www.ubereats.com/nl/store/arte-bianca/zG4J7jb5Qji3SF6A-7-eRw
- Thuisbezorgd: https://www.thuisbezorgd.nl/menu/arte-bianca
- Instagram: https://www.instagram.com/artebianca.den.haag/
- Restaurant address: Piet Heinstraat 36, 2518 CH Den Haag, Netherlands
- Telephone: +31 70 205 4659

## Before this goes live as the restaurant's official website

- **Get the owner's approval** for the site and branding.
- Confirm all menu names, ingredients, pricing, opening hours, and whether table reservations are available. The example menu used publicly visible Uber Eats / Thuisbezorgd information checked **17 November 2026**; prices can vary by platform.
- The food photos were **AI-styled from source photos provided for the demo**. They are illustrative, not guaranteed exact product photos. Use approved restaurant images and accurate dish photos for a live menu.
- The website is a **demo, not the official Arte Bianca website** until the restaurant approves it and chooses to publish it.
- Change the page's SEO text and any demonstration disclaimers after approval.

No frameworks, trackers, external fonts, cookies, shopping cart, or private customer information are included.
