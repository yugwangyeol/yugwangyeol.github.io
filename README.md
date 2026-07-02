# Gwangyeol Yu's Website

Personal academic website for GitHub Pages.

## Local Development

This site is built with Jekyll.

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Main Files

- `_data/main_info.yaml`: profile, links, and contact information
- `_data/publications.yaml`: publications
- `_data/experience.yaml`: education and research experience
- `_data/awards.yaml`: awards and honors
- `_data/projects.yaml`: projects
- `index.html`: homepage sections
- `libs/custom/my_css.css`: custom styling

## Project Thumbnails

Temporary SVG thumbnails are stored here:

- `assets/projects/facial-caricature/thumbnail.svg`
- `assets/projects/accident-risk/thumbnail.svg`
- `assets/projects/port-waiting-time/thumbnail.svg`
- `assets/projects/image-iqa-captioning/thumbnail.svg`
- `assets/projects/3d-shoes/thumbnail.svg`
- `assets/projects/path-guidance/thumbnail.svg`
- `assets/projects/process-anomaly/thumbnail.svg`
- `assets/projects/flood-prediction/thumbnail.svg`

To replace them with your own images, add the image file to the relevant folder and update the matching `thumbnail` path in `_data/projects.yaml`.

Based on Martin Saveski's Jekyll template.
