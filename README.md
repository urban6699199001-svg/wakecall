# WakeCall — legal & support pages

Static pages served by GitHub Pages. App Review opens all of these, and the EULA link is
required next to an auto-renewable subscription (Guideline 3.1.2), so they must never 404.

| Page | URL |
|---|---|
| Home | https://urban6699199001-svg.github.io/wakecall/ |
| Terms of Use | https://urban6699199001-svg.github.io/wakecall/terms.html |
| Privacy Policy | https://urban6699199001-svg.github.io/wakecall/privacy.html |
| Community Guidelines | https://urban6699199001-svg.github.io/wakecall/community-guidelines.html |
| Support | https://urban6699199001-svg.github.io/wakecall/support.html |

Each page is bilingual on one URL — English first, then Traditional Chinese. That is
deliberate: App Review may read either, and a language router is one more thing that can
break between submission and review.

## Before you submit

Two identity details are taken from sources that are already public, and you may want to
change them:

- **Operator name** — currently `WakeCall (developer: Zihao Chen)`, from the Apple
  Distribution certificate. Replace with a company legal name if you have one.
- **Contact email** — `adgj0206@gmail.com`, the same address as the published privacy
  policy for URBAN.

Both appear in `terms.html`, `privacy.html`, `community-guidelines.html`, `support.html`
and the footer of every page.

## Editing

Pages are generated; the source of truth is `legal/*.md` and the build script in the
WakeCall repo. For a small wording fix, editing the HTML directly here is fine.
