# Escape From Uni — GitHub Pages

This repository powers a GitHub Pages site that hosts your PDFs and game JAR.

## Structure

```
.
├─ index.md          # Home page (Markdown)
├─ about.md          # Optional about page
├─ _config.yml       # Jekyll config (uses minima theme)
├─ docs/             # Your downloadable files live here
│  ├─ Arch1.pdf
│  ├─ Plan1.pdf
│  ├─ Req1.pdf
│  ├─ Risk1.pdf
│  └─ Escape_From_Uni-1.0.0.jar
└─ .gitignore
```

## Local preview (optional)

If you have Ruby/Jekyll, you can preview locally:

```bash
gem install bundler jekyll
bundle init
bundle add jekyll minima
bundle exec jekyll serve
```