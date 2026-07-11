# emilybarrera

Personal site for Emily Barrera — yoga & stretch classes, choreography, and dramaturgy.
Built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Editing content

| To change… | Edit… |
|------------|-------|
| Homepage text | `index.html` |
| About page | `about.md` |
| Classes / schedule | `classes.md` |
| Contact info & social links | `_config.yml` (and `contact.md`) |
| Site title, email, domain | `_config.yml` |
| Colors & fonts | `assets/css/style.css` (see the `:root` variables at the top) |

## Adding a journal post

1. Copy an existing file in `_posts/`.
2. Rename it `YYYY-MM-DD-a-short-title.md` (the date matters).
3. Edit the front matter (`title`, `date`, `category`) and write below the `---`.
4. Add an optional header image with `image: /assets/img/your-photo.jpg`.

## Running locally

```bash
bundle install
bundle exec jekyll serve
# open http://127.0.0.1:4000
```

## Deploy

Pushing to the default branch auto-builds via GitHub Pages.
Custom domain is set in `CNAME` (currently `emilybarreramovement.com`).
