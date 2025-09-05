# Mahmed Hameed — IT & Cyber Security Portfolio

A Minimal Mistakes Jekyll site for showcasing projects.

## Quick Start (GitHub Pages user site)
1. Create a repo named **mahmed-hameed.github.io**.
2. Copy this folder's contents to the repo root and push.
3. GitHub → Settings → Pages should auto-publish from the default branch.

## Local preview (optional)
Use Docker:
```bash
docker run -it --rm -v "$PWD":/srv/jekyll -p 4000:4000 jekyll/jekyll:4   bash -lc "bundle init && echo 'gem "github-pages"' >> Gemfile && bundle install && bundle exec jekyll serve --host 0.0.0.0"
```
