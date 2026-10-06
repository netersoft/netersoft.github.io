# netersoft.github.io

Public pages for Netersoft apps, served by GitHub Pages at https://netersoft.github.io/.

- NPass privacy policy: `n-pass/privacy/` (fr) and `n-pass/privacy/en/`. Don't edit these pages by hand: they are generated from the app's in-app policy with `tool/build_privacy_pages.py` in the `n-pass` repository.
- Privacy policies of Codes USSD, Egyptian Mythology, Simple Photo Editor and Statistique Descriptive: `<app>/privacy/` (fr) and `<app>/privacy/en/`, with the same template as NPass. These apps don't ship their policy yet, so the pages are maintained here: keep the template in sync with NPass's when editing them.
- Codes USSD catalog: `ussd-codes/catalog.json`, downloaded by the app to update its codes without a store release. Don't edit it by hand: it is built from `catalog/` with `tool/build_catalog.dart` in the `ussd-codes` repository, then copied here.
