# junruihuang.com

Personal academic website of Junrui Huang, hosted on GitHub Pages at
[junruihuang.com](https://junruihuang.com).

Built on the [AcademicPages](https://github.com/academicpages/academicpages.github.io)
Jekyll template (MIT), with single-page layout and styling adapted from
[YWolfeee/YWolfeee.github.io](https://github.com/YWolfeee/YWolfeee.github.io) (MIT).

## Editing

- **Everything on the homepage** (about, news, publications, services, awards, misc):
  `_pages/about.md`
- **Sidebar** (name, photo, icon links): `author:` section of `_config.yml`;
  the section menu lives in `_includes/author-profile.html`
- **Profile photo**: replace `images/profile.png`
- **Paper thumbnails**: `images/papers/`

## Local preview

```bash
docker compose up --build
# then open http://localhost:4000
```

Pushing to `master` triggers the GitHub Pages build automatically.
