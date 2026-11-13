# LJT-Homepage

Personal academic homepage of **Junteng Liu** — first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology.

## About

- **Name**: Junteng Liu
- **Affiliation**: Hong Kong University of Science and Technology (HKUST NLP Group)
- **Email**: jliugi@connect.ust.hk
- **GitHub**: [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar**: https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate
- **X (Twitter)**: @junteng88716710

## Research

My research focuses on natural language processing and machine learning, with interests in:

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM truthfulness and Interpretability

## Site structure

This site is built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and hosted on GitHub Pages.

- `_pages/about.md` — homepage with bio, publications, research experience, skills and contact information
- `_pages/cv.md` — CV with education, research experience, skills, publications and honors
- `_pages/publications.html` — publications listing (generated from `_publications/`)
- `_publications/` — individual publication entries
- `_config.yml` — site-wide configuration and author profile

## Running locally

To preview the site locally you will need `ruby-dev`, `bundler`, and `nodejs` installed:

```bash
sudo apt install ruby-dev ruby-bundler nodejs
bundle install
npm run build
jekyll serve -l -H localhost
```

Then open `localhost:4000/LJT-Homepage` in your browser.
