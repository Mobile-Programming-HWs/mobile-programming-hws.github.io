# Mobile Programming HWs Site

This repo hosts the GitHub Pages site for the Mobile Programming HWs organization.

I use it as a project hub for the coursework apps. The site links to each repo, shows screenshots, and keeps short notes about what was built.

## Pages

- Home page: `_pages/about.md`
- Project index: `_pages/projects.md`
- Source repo list: `_pages/repositories.md`
- Project pages: `_projects`
- Screenshots: `assets/img/projects`
- Shared page styles: `_includes/project_styles.liquid`

## Run Locally

Install Ruby gems:

```powershell
bundle install
```

Build the site:

```powershell
bundle exec jekyll build
```

Run a local preview:

```powershell
bundle exec jekyll serve
```

## Update

- Add or edit project pages in `_projects`.
- Put new screenshots under `assets/img/projects`.
- Keep each project page short and tied to the current repo README.
- Run `bundle exec jekyll build` before committing.
