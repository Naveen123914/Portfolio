# S. Naveen – Engineering Portfolio

Static HTML5 / CSS / JS site. No build step, no dependencies. Deploys to Vercel as-is.

## Files

```
index.html              page content
style.css               styling (light + dark theme, print styles)
script.js               theme toggle, mobile menu, gallery, scroll effects
assets/profile.jpg      hero photo
assets/S-Naveen-Resume.pdf   resume download
assets/cad/             put CAD screenshots here (see below)
```

## CAD gallery

The four renders live in `assets/cad/` as `cad-1.jpg` … `cad-4.jpg` (4:3, 1200 × 900).
To rename a part or swap an image, edit the matching `<figure class="shot">` block in `index.html`
(the `data-src`, caption and `alt` text). If an image file is missing, the card shows a blueprint placeholder.
Clicking an image opens it full size.

## Add LinkedIn / phone

In `index.html`, find the `LinkedIn` comment in the Contact section, put in your profile URL and remove the comment markers.
Phone and street address were deliberately left off the public page.

## Deploy to Vercel

1. Push this folder to a GitHub repository (`index.html` must be at the repo root).
2. On vercel.com choose **Add New → Project**, import the repository.
3. Framework Preset: **Other**. Leave build command and output directory empty. Click **Deploy**.
