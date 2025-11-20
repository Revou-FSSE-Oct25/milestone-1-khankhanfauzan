[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KTVBmApB)

---

# RevoU Student Portfolio

## Overview

This website shows my learning progress and small projects as a RevoU student. It is a simple personal site with sections for Home, About, Projects, and Contact.

## Features

-   Basic navigation between sections (Home, About, Projects, Contact)
-   Consistent theme (black + teal) and simple layout
-   Projects grid with images, titles, short descriptions, and tech list
-   Contact info with email, phone, address and social links
-   Contact form with native validation (required fields and email type)
-   Download CV button
-   Responsive design (mobile-first with Tailwind)
-   Fixed top navbar (remains visible when scrolling)
-   Hover transition on buttons, links, and projects cards

## Technologies

-   HTML5
-   ~~CSS3~~ Tailwind v4.1
-   Google Fonts (`Poppins`)
-   ~~Font Awesome icons v4.7.0~~ Remix Icon v4.7.0
    _some icons is not available in Font Awesome Icons_

## New Updates

This section summarizes the main changes from the previous version:

-   Styling migration to Tailwind (utility-first)
-   Added responsiveness for mobile, tablet, and desktop
-   Fixed navbar to remain visible while scrolling
-   Hover transition for smoother interactions

## Deployed Page

-   GitHub Page: [Open](https://revou-fsse-oct25.github.io/milestone-1-khankhanfauzan/)

## How to Deploy (GitHub Pages)

1. Push this project to GitHub (main branch)
2. Open repository `Settings` → `Pages`
3. Under `Source`, choose `Deploy from a branch`
4. Set `Branch` to `main` and `Folder` to `/root` (or `/docs` if you use docs folder)
5. Click `Save`
6. Wait 1–2 minutes, your page will be live
7. The site uses `index.html` at the project root

## Project Structure (minimal)

```
.
├── README.md
├── assets/
│   └── cv_fauzan.pdf
├── css/
│   └── styles.css
├── images/
│   ├── profiles/
│   │   ├── fauzan_photo.JPG
│   │   └── fauzan_photo_2.JPG
│   └── projects/
│       ├── mds_quail.png
│       ├── mds_coop.png
│       ├── linxspace.png
│       ├── linxcoop.png
│       ├── fuelinx.png
│       ├── patlog_operator.png
│       ├── patlog_pengawas.png
│       ├── patlog_driver.png
│       ├── mypertashop.png
│       ├── manager_mypertashop.png
│       └── mitra_pertashop.png
└── index.html
```

## Access Locally (optional)

-   Open `index.html` directly in your browser, or run a small server:
-   macOS/Linux: `python3 -m http.server 8000` then visit `http://localhost:8000/`
-   Open `index.html` on code editor, and simply run with **Live Server**
-   Opsional (jika menggunakan Tailwind CLI): jalankan proses build saat develop

```bash
npx @tailwindcss/cli -i ./input.css -o ./css/styles.css --watch
```

### See the difference form previous build

-   `main` = latest version (Tailwind, responsive, fixed navbar, hover animation)
-   `module-1` = previous version (Manual CSS)
-   Open terminal in code editor, then run this command:

```bash
git checkout module-1
```

-   then follow the steps on [Access Locally](#access-locally-optional)
-   Opsional: bandingkan perubahan file inti (HTML/CSS) dengan perintah diff:

```bash
git diff module-1..main -- index.html css/styles.css
```
