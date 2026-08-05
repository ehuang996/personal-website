# junruihuang.com

Personal academic website of Jun Rui Huang, hosted on GitHub Pages at
[junruihuang.com](https://junruihuang.com).

A single-page Jekyll site; upstream licensing is covered by the LICENSE file.

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
