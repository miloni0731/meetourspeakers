# GitHub-ready Talk & Project Portfolio

A static GitHub Pages portfolio inspired by the resource/collection page in the reference screenshot.

## Features

- Dark grid background
- Serif editorial headings + mono metadata
- Responsive cards
- Collection homepage
- Nested `/tree/.../` resource pages
- Hover animations
- Custom 404 page
- No framework or build step
- Works as plain HTML/CSS/JS on GitHub Pages

## 1. Customize

Search the project for these placeholders and replace them:

- `Your Name`
- `YOUR_USERNAME`
- `you@example.com`
- `example.com`
- `YOUR_REPO`

The main page is `index.html`.

The AWS example page is:

`tree/awsug-aug-26/index.html`

## 2. Add a new collection

Copy:

`tree/awsug-aug-26/`

to something like:

`tree/my-new-talk/`

Then edit the new `index.html`.

Add a new card to the collection grid in the root `index.html`:

```html
<a class="collection-card" href="tree/my-new-talk/">
  ...
</a>
```

## 3. Publish with GitHub Pages

Create a repository, upload this folder, then open:

**Repository → Settings → Pages**

Choose:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

GitHub Pages will publish the static files.

## 4. Suggested repository names

For a project site:

`talks`

For a personal site:

`YOUR_USERNAME.github.io`

If you use the second format, the site can live at:

`https://YOUR_USERNAME.github.io/`

Otherwise, a project repository is normally available under:

`https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`

## Notes

The nested pages intentionally use relative asset paths such as `../../assets/css/style.css`, so they work correctly as GitHub Pages project-site pages without a build system.
