# CLAUDE.md

Personal site for Wen Qing Lim, served at https://wenqinglim.github.io/ via GitHub Pages. Jekyll with the remote [Alembic](https://alembic.darn.es/) theme (`remote_theme: daviddarnes/alembic@main` in `_config.yml`).

## Layout
- `index.md`: landing page (links out to Substacks, Medium, etc.)
- `about.md`: About Me (`aside: true`)
- `resume.md`: web resume (`aside: false`); "View PDF" button links to `assets/wenqinglim_resume.pdf`
- `assets/styles.scss`: only imports the theme
- `_posts/`, `blog/`, `categories.md`: blog scaffolding
- `_config.yml`: theme, plugins, site metadata

## Run locally
`bundle install`, then `bundle exec jekyll serve`. `Gemfile.lock` is untracked and `.DS_Store` files are noise; don't commit them.

## Content conventions
- **Source of truth for the resume** is the latest `Wen_Qing_LIM_Resume_UK.docx/.pdf` (kept in `~/Downloads`). When it changes: update `resume.md` to match and replace `assets/wenqinglim_resume.pdf`.
- Resume format: `###` heading per role (`Title — Company, Location`), an italic line with dates and tech, then flat bullets (no nested lists). Roles are listed newest first. Octavate is a work-history entry (not under Projects).
- Years of experience: **7+**.
- Don't put private details on the public pages (e.g. the visa/sponsorship line from the docx resume).
- About page: lead with expertise and interests; music is one theme among several, not the whole story.
- Spelling: British (optimised, prioritisation).

## Git workflow
- Long-lived branch is `new-site-who-dis-2025` (the Jekyll rebuild, still ahead of `master`). Branch off it and open PRs **against `new-site-who-dis-2025`**, not `master`, unless told otherwise.
- Check `git diff --stat <base>...HEAD` before opening a PR so the diff only contains intended files.
