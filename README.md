# netersoft.github.io

Public pages for Netersoft apps, served by GitHub Pages at https://netersoft.github.io/.

- Privacy policies of every app (Codes USSD, Egyptian Mythology, NPass, Simple Photo Editor, Statistique Descriptive): `<app>/privacy/` (fr) and `<app>/privacy/en/`. Don't edit these pages by hand: they are generated from each app's in-app policy with `tool/build_privacy_pages.py` in the app's repository.
- Codes USSD catalog: `ussd-codes/catalog.json`, downloaded by the app to update its codes without a store release. Don't edit it by hand: it is built from `catalog/` with `tool/build_catalog.dart` in the `ussd-codes` repository, then copied here.
