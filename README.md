# Atelier Obscura

Static GitHub Pages site for a luxury Easter egg archive and wait list.

## Contents

- `index.html` : single-page site with embedded CSS and JavaScript
- `images/` : local product images used by the page

## GitHub Pages deployment

1. Create a repository called `Atelier-Obscura`
2. Upload the contents of this folder to the repository root
3. Commit to `main`
4. In GitHub:
   - go to **Settings**
   - open **Pages**
   - set source to **Deploy from a branch**
   - choose `main` and `/ (root)`
5. Save and wait for GitHub Pages to publish

## Notes

- All image links are relative, so the site is ready for GitHub Pages
- The wait list form is front-end only and currently logs submissions to the browser console
- To make the form live, connect the submit handler to your preferred service such as Formspree, Mailchimp, HubSpot, Klaviyo or Supabase
