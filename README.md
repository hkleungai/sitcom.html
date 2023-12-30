# no.js

## With Templated HTML without js

The goal is to do write interactive webpages in HTML with templating syntax but without javascript.

Hence, very minimal amount of libraries shall be included via html `<script />` tag.

- [htmx](https://htmx.org/) for concise ajax syntax
- [nunjucks](https://mozilla.github.io/nunjucks/) for templating and code-splitting
- [tailwind css](https://tailwindcss.com/) and [bootstrap](https://getbootstrap.com/) 
for webpage styling

## With Minimal Automation Setup

This repo is formed with only 3 things.

- This `README.md` file
- Source code (.html, .njk, .json) in `src/`
- Deployment step in `.github/workflows/deploy.yml`,
for moving stuffs in `src/` folder to `gh-pages` branch.

## Without Server Support

No server supported shall be added at this point, since this repo is really just about html.

## Without js Config File nor Build Step

Anyone cloning this repo can open the html page on their browser and just interact with it.
