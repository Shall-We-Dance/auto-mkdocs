# auto-mkdocs

Write in MarkDown and let Github do everything else.

1. Fork this repository.
2. Configure `mkdocs.yml`.
3. Push.
4. Configure Github Pages.

`.git/workflows/build.yml` will automatically convert `.md` files in `/docs` folder to mkdocs-material pages in `gh-pages` branch.

`/docs/CNAME` will allow you to customize site infomation.