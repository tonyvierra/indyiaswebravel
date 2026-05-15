# Explore With Indy — Premium GitHub Pages Prototype

This is a static website prototype for **Explore With Indy**. It is designed to show what Indyia's travel business website could look like before rebuilding the final version in Wix.

## What is included

- `index.html` — Home page
- `about.html` — About Indyia page
- `services.html` — Travel services and package page
- `destinations.html` — Filterable destination page
- `guides.html` — Travel guide/blog preview page
- `contact.html` — Trip inquiry/contact page
- `404.html` — Custom not-found page
- `assets/css/styles.css` — All styling
- `assets/js/main.js` — Navigation, animations, photo fallback, filters, lightbox, forms, drawer
- `.nojekyll` — Helps GitHub Pages serve the files as plain static files

## Important limitation

GitHub Pages can host static HTML, CSS, and JavaScript, but it does not process server-side forms, payments, client dashboards, or bookings by itself.

This prototype uses a fake form flow that creates an email draft. For the real business launch, rebuild this in Wix and use Wix Forms / Wix Bookings.

## How to publish on GitHub Pages

1. Create a new GitHub repository, for example: `explore-with-indy-premium`
2. Upload every file and folder from this zip into the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Save.
6. Your site will publish at a URL like:
   `https://YOUR-USERNAME.github.io/explore-with-indy-premium/`

## How to add Indyia's real photos

The code automatically tries to load local images from `assets/photos/`. If the image is missing, it falls back to demo travel images.

To use Indyia's photos, place JPG images in `assets/photos/` using these exact filenames:

- `hero-main.jpg`
- `hero-city.jpg`
- `hero-detail.jpg`
- `about-left.jpg`
- `about-right.jpg`
- `about-hero.jpg`
- `services-hero.jpg`
- `destinations-hero.jpg`
- `guides-hero.jpg`
- `contact-hero.jpg`
- `feature-sicily.jpg`
- `feature-caribbean.jpg`
- `feature-europe.jpg`
- `feature-luxury.jpg`
- `gallery-1.jpg`
- `gallery-2.jpg`
- `gallery-3.jpg`
- `gallery-4.jpg`
- `gallery-5.jpg`
- `gallery-6.jpg`
- `destination-caribbean.jpg`
- `destination-sicily.jpg`
- `destination-paris.jpg`
- `destination-greece.jpg`
- `destination-nyc.jpg`
- `destination-mexico.jpg`
- `guide-sicily.jpg`
- `guide-resort.jpg`
- `guide-girls-trip.jpg`

Best photo sizes:

- Hero photos: 1600px wide or larger
- Gallery photos: 1000px wide or larger
- Save as JPG, around 70–85% quality so the site stays fast

## How to get photos from Instagram safely

Do not hotlink Instagram CDN image URLs. They can break and are not meant to be used as permanent website image hosting.

Better options:

1. Ask Indyia to send/export the original photos from her phone or cloud storage.
2. Download her own Instagram data from Instagram account settings.
3. Save the selected photos into `assets/photos/` using the filenames above.
4. Re-upload the folder to GitHub.

## What to edit first

Search the HTML files for these placeholders:

- `hello@explorewithindy.com`
- `Prototype testimonial`
- `Placeholder copy`
- `Inquire / call`
- `Custom / trip`

Replace those once she confirms her real email, services, pricing, bio, and testimonials.

## Recommended next step

Use this GitHub Pages version to show the visual direction. Then rebuild in Wix for the real launch so Indyia can edit the site herself and use built-in forms, bookings, payments, domain setup, and SEO tools.
