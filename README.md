# Zhenxi Gao's Academic Homepage

This repository contains the source for [Morishima6.github.io](https://morishima6.github.io), a research portfolio for Zhenxi Gao.

The site presents research and engineering work in:

- Computer-use agents
- Human-trajectory retrieval and agentic RAG
- Multimodal reasoning and AIGC detection

## Stack

- Jekyll
- Academic Pages theme
- GitHub Pages deployment

## Local Preview

Ruby and Bundler are required for a native preview:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

The repository also includes a Docker workflow:

```bash
docker compose up --build
```

Then open `http://localhost:4000`.

## Content Structure

- `_pages/about.md` - homepage introduction
- `_portfolio/` - selected research projects
- `_publications/` - publications
- `_pages/cv.md` - education, experience, skills, and honors
- `_config.yml` and `_data/` - site identity, author profile, and navigation
