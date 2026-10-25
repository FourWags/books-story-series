# Petal Reader

**Petal Reader**, formerly Book’s Story Series, is an unofficial personal edition of [Acclorite/book-story](https://github.com/Acclorite/book-story), based on v1.8.0. GPL-3.0-only; upstream copyright and license notices are retained in the source archive.

Current release: [1.8.0-petal.9 Preview · series editing, compact EPUB fix and Shiba themes](https://github.com/ClownChowder/books-story-series/releases/tag/v1.8.0-petal.9), published October 25, 2026.

## Library and reading

- Cozy-inspired browsing: author cover cards → series cover stacks → books in numeric order, with standalone books under each author.
- Persistent search across authors, series and book titles; Books provides direct access to matching titles.
- Shared series keep every author's books together.
- Series headers in grid and list layouts, with numeric reading order.
- EPUB 3 and Calibre series metadata, decimal volumes, omnibus ranges, and unnumbered companions.
- Per-book series editing and EPUB metadata refresh in Book Details without reimporting.
- Series-name search and original book titles.
- Offline reader with no INTERNET permission.

## Appearance

Appearance options include **Voice blue, Dynamic color, Lagoon, Forest, Sunset, Berry, Lavender, Shiba Apricot, Shiba Black & Tan and Shiba Sesame**. Existing app theme preferences migrate to Voice blue.

Voice-inspired styling includes Literata book text, DM Sans/Fraunces UI typography, rounded cards and search, light/dark/follow-system preview tiles, circular color swatches and a pure-black switch. Pure black changes background surfaces while retaining tonal containers. Matching Reader icon variants keep exactly one launcher enabled; legacy aliases remain for update compatibility.

Dynamic color requires Android 12 / API 31 or later; older Android versions use Voice blue as its fallback.

**Reading-page font and color customization remains separate** from app styling. Existing reader controls and series order remain intact.

## Release validation and limitations

Current preview: 44 fresh synthetic host unit tests and 14 isolated Android 35 emulator instrumentation tests passed. Debug and minified builds passed. An in-place synthetic upgrade from 1.8.0-petal.8 and compact EPUB reading passed on the exact offered APK. Physical-device and real-edition handoff were not rerun for 1.8.0-petal.9. The earlier trusted Library handoff and authorization results apply to 1.8.0-petal.7 only. Providers require signature permission, matching caller signature and Library identity. Companion: [Petal Library](https://github.com/ClownChowder/petal-library).

Reader has no INTERNET permission. Lint retains 90 warnings and 388 baseline-filtered missing-translation errors; this is not a clean-lint claim. Physical performance, battery and live assistive technology remain unqualified for this update. Handoff uses approximate whole-book percentages, so select matching editions. See attached CHECKS.txt and verification.json for artifact-bound results and limits. Earlier releases retain their own historical evidence.

## Downloads and source

Download `books-story-series.apk` from [Releases](https://github.com/ClownChowder/books-story-series/releases). The complete corresponding source is attached as `books-story-series-source.zip`, including the upstream GPL license and build scripts. The automatic GitHub source archives contain this release-index repository, not the app source; use the explicitly attached source ZIP.

Install the APK on your Android device, allowing APK installation for the app you use to open it if prompted. For an existing personal-edition installation, install over it to retain its app data; package and signing identity are unchanged (new version code 22). Back up important library data before updating. Checksums are attached to the release as `SHA256SUMS`.

This is an emulator-tested personal debug build, not an official upstream release or production qualification. No newer Acclorite source was fetched or merged. Package: `ua.acclorite.book_story.series.debug`. It runs alongside the official reader with separate app data.

## Obtainium

Add this repository URL in Obtainium:

`https://github.com/ClownChowder/books-story-series`

APK filename filter: `^books-story-series\.apk$`

Signing certificate SHA-256: `386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4`

New tested personal builds must be signed locally with the same key and published here with an increased version code and version name. Obtainium checks and downloads those published releases; it does not merge or build upstream changes automatically. Signing keys and personal ebook-library data are not published.

## Original authors and credits

Book's Story by Acclorite and contributors remains the original reader. The cover-stack browser is a new implementation inspired by the user's customized Cozy. Visual styling credits Voice by Paul Woitaschek and contributors. Literata, DM Sans and Fraunces are bundled under SIL OFL 1.1; their full font licenses are in the corresponding source and app assets.

See [CREDITS.txt](CREDITS.txt) for original authors, upstream projects, recording/model creators and applicable licenses. Original license and copyright notices remain in the corresponding source archives and app assets. No upstream endorsement is implied.
