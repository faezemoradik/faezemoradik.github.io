# faezemoradik.github.io

Personal academic website for Faeze Moradi Kalarde, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll theme and hosted on GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Structure

* `_config.yml` — site-wide settings, author info, and social links
* `_pages/about.md` — home page (bio, news, awards)
* `_pages/cv.md` — CV page (education, experience, awards, skills, service)
* `_publications/` — one Markdown file per publication
* `_teaching/` — one Markdown file per teaching appointment
* `_posts/` — blog posts
* `images/profile.png` — profile photo shown in the sidebar
* `files/` — PDFs (CV, papers, slides) linked from content pages

## Deploying

Push to the `main` branch of the `faezemoradik.github.io` GitHub repository. GitHub Pages builds and publishes the site automatically — no CI workflow required.
