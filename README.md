# Rahul Kesarkar — Personal Portfolio

Personal portfolio website: **https://rahulkesarkar.github.io/**

This repository contains the public-facing personal website. It is intentionally separate from individual project repositories so the portfolio URL stays stable as new projects are added.

## Website structure

```text
index.html
assets/
  css/site.css
  js/site.js
  favicon.svg
projects/
  ai-job-matching-agent.html
```

## Local preview

From the repository root, run:

```bash
python3 -m http.server 8767
```

Then open http://localhost:8767 in a browser.

## Publishing

This is a GitHub Pages user site. Configure the repository's Pages publishing source to deploy from the `main` branch and the root folder (`/`).

## Project pages

The portfolio currently features a technical case study for the [AI Job-Matching Agent](https://github.com/rahulkesarkar/ai-job-matching-agent). Its public interactive demo is not yet deployed; the case study states this clearly. New projects can be added under `projects/` and linked from the homepage.

## Maintenance

- Keep the site content, styling and scripts in this repository.
- Keep project source code and engineering documentation in their respective project repositories.
- Test both the homepage and every project page after changing relative links.
- Do not add a resume download until the initial portfolio and live project-demo goals are completed, as planned.
