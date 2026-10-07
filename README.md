# netersoft.github.io

Public pages for Netersoft apps, served by GitHub Pages at https://netersoft.github.io/.

- Home page: `index.html` (fr) and `en/index.html`, styled by `home.css`, with the Netersoft mark `icon.svg` as favicon. On a first visit, `index.html` sends browsers whose language isn't French to `en/`; a language picked with the FR/EN link is remembered (localStorage) and wins. Written by hand: keep both languages in sync.
- Privacy policies of every app (USSD Codes, Egyptian Mythology, NPass, Simple Photo Editor, Descriptive Statistics): `<app>/privacy/` (fr) and `<app>/privacy/en/`. Don't edit these pages by hand: they are generated from each app's in-app policy with `tool/build_privacy_pages.py` in the app's repository.
- USSD Codes catalog and site: `ussd-codes/catalog.json` (downloaded by the app to update its codes without a store release) and the public code pages (`ussd-codes/index.html`, one directory per country and operator, `ussd-codes/telephone/`, `ussd-codes/sitemap.xml`). Don't edit them by hand: `tool/build_site.dart` in the `ussd-codes` repository generates them from its `catalog/`.
- `robots.txt` points search engines to the USSD Codes sitemap.
