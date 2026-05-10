# Ashley Williams — Portfolio

A personal portfolio website showcasing projects with links to GitHub repos and live demos.

## Structure

```
ashley-williams-portfolio/
├── index.html       # Main page (about, projects, contact)
├── styles.css       # All styling
└── imgs/
    └── woman-on-desk.webp   # Profile photo
```

## Features

- **About section** — profile photo card, bio, and links to GitHub and LinkedIn
- **Projects grid** — responsive 3-column grid of project cards, each with a screenshot placeholder, project name, GitHub and live demo links, and a short description
- **Contact footer** — address, phone, email, and social links
- **Responsive layout**

## Tech

Plain old HTML and CSS (no frameworks or build tools)

## Getting Started

No dependencies or build step required. Just open `index.html` in a browser

## Customization

To make this your own:

1. **Profile photo** — replace `imgs/woman-on-desk.webp` with your own image
2. **About text** — replace the lorem ipsum in the `<section class="intro">` with your actual bio
3. **Social links** — fill in the `href` attributes on the GitHub and LinkedIn `<a>` tags in the header
4. **Projects** — for each `.project-card`, update the project name, description, and the `href` values on the GitHub and live demo links; replace the gradient placeholder with a real screenshot
5. **Contact info** — update address, phone, email, and footer social links

## Credits

Profile photo by [Brooke Cagle](https://unsplash.com/@brookecagle) on Unsplash.
