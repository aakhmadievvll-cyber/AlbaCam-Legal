# AlbaCam — Legal & Support

Public legal and support pages for **AlbaCam**, a vintage film camera for iPhone
(`com.alba.AlbaCam`, Apple ID `6829254633`). The camera, the album, video and import are
free and work offline; photos and videos never leave the phone. The only online feature is
the optional **AlbaCam Pro** subscription: AI cameras built from a typed description
(our server in London → Google Gemini API).

These pages describe exactly what the app keeps and sends. They are not a generic
template: if the app or the backend changes what it stores or sends, change these pages
**before** that version ships.

## Live pages

Served by GitHub Pages from `main`, repository root, at
`https://aakhmadievvll-cyber.github.io/AlbaCam-Legal/`.

English:

- Privacy Policy: https://aakhmadievvll-cyber.github.io/AlbaCam-Legal/privacy.html
- Terms of Use: https://aakhmadievvll-cyber.github.io/AlbaCam-Legal/terms.html
- Support: https://aakhmadievvll-cyber.github.io/AlbaCam-Legal/support.html

Русский:

- Политика конфиденциальности: https://aakhmadievvll-cyber.github.io/AlbaCam-Legal/privacy-ru.html
- Пользовательское соглашение: https://aakhmadievvll-cyber.github.io/AlbaCam-Legal/terms-ru.html
- Поддержка: https://aakhmadievvll-cyber.github.io/AlbaCam-Legal/support-ru.html

The app links these URLs from `AlbaCam/Pro/ProCatalog.swift` (paywall and Settings); App
Store Connect uses `privacy.html` / `privacy-ru.html` as the Privacy Policy URLs and
`support.html` / `support-ru.html` as the Support URLs. The Terms of Use (EULA) link in
the store description is Apple's standard EULA; `terms*.html` adds to it.

## App

| | |
|---|---|
| App | AlbaCam («AlbaCam: плёночная камера» / "AlbaCam: Vintage Film Camera") |
| Bundle ID / Apple ID | `com.alba.AlbaCam` / `6829254633` |
| Platform | iPhone, iOS 17.0+, Russian interface |
| Price | Free; optional auto-renewable subscription AlbaCam Pro — US $2.99/month, $14.99/year; no trial; no ads |
| Fair use | 10 AI cameras per UTC day and 50 per rolling 30 days per subscriber |
| Age rating | 4+ |
| Publisher | Akhmadiev Albert IE (individual entrepreneur, Republic of Armenia) |
| Contact | InnoAppDesign@yandex.com · GitHub issues on this repository |

## Editing

Plain static HTML, no build step and no scripts. `styles.css` holds the shared design
tokens (light "darkroom paper" and dark "camera body" themes via
`prefers-color-scheme`). There are no web fonts or third-party requests on purpose.
`.nojekyll` makes GitHub Pages serve the files as they are.

Rules:

- Keep the English and Russian pages identical in substance. A difference between them is
  a compliance problem, not a translation nuance.
- Update the effective date at the top of a page (and the footer) whenever its substance
  changes.
- Facts on these pages are mirrored in `AppStore/METADATA_1.0.md` (App Privacy answers)
  and `AlbaCam/PrivacyInfo.xcprivacy` in the app repository; change all three together.
