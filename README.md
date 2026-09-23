# Personal Profile Website

A two-page profile site built with semantic HTML and CSS, with no frameworks or JavaScript.

**[View the live site →](https://sakiriti.github.io/personal-profile-website/)**

![The home page, showing the gradient hero and project cards](screenshot.png)

## Tech stack

HTML · CSS · GitHub Pages

## Features

- Semantic markup using `header`, `nav`, `main`, `section`, `article` and `footer`
- A card layout built with Flexbox and `flex-wrap`, so cards reflow onto the next line as the window narrows — one media query handles only the type scale
- Colour, spacing and radii defined once as custom properties on `:root`, so the whole palette can be changed from a single block
- A gradient hero and a sticky, blurred header
- An accessible contact form where every `label` is bound to its input with `for` and `id`
- Relative navigation links between the Home and Contact pages, with the current page marked

## Structure

```
index.html     Home page: intro, projects, skills and outreach
contact.html   Contact details and a message form
styles.css     Shared stylesheet for both pages
screenshot.png Preview image used in this README
```

## Running it

Open `index.html` in a browser, or serve the folder with Live Server.

## Deployment

Deployed with GitHub Pages from the `main` branch. Any push to `main` rebuilds the site automatically.
