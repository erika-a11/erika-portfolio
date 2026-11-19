# Erika Guragain — Portfolio

An editorial-style personal portfolio for Erika Guragain, QA Intern. Plain HTML, CSS and JavaScript with no build step and no dependencies apart from Google Fonts.

## Structure

```
.
├── index.html   # markup, styles and rendering script
├── config.js    # all editable content (name, text, links, projects, photo path)
└── assets/      # photo.jpg and project images
```

## Editing content

Everything you'd want to change lives in `config.js`. Entries marked `PLACEHOLDER` (projects, dates, location, email, LinkedIn and GitHub URLs) should be replaced with real details.

- Profile photo: replace `assets/photo.jpg`
- Project images: add `assets/project1.jpg`, `assets/project2.jpg`, ... (a labeled placeholder shows until they exist)

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
```

## Deploy

This is a static site. On Vercel, import the repository and keep the defaults (Framework Preset: **Other**, no build command, no output directory).
