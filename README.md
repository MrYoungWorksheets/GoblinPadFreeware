# GoblinPadFreeware

This repository hosts the public GoblinPad freeware download website.

Public page:

https://mryoungworksheets.github.io/GoblinPadFreeware/

GoblinPad is freeware by Robert Young, writing as Samburjack. The public site explains what GoblinPad does and links users to the latest Windows installer release.

## Repository Scope

This repo is public download and website only.

The GoblinPad source repository is private. Do not commit application source code into this repo.

Installer assets belong in GitHub Releases, not in the repository files.

GitHub Pages should publish from the `main` branch root.

## Download Link

The website download button points to:

https://github.com/MrYoungWorksheets/GoblinPadFreeware/releases/download/v1.0.0-beta.1/GoblinPad%20Setup%201.0.0-beta.1.exe

Release notes point to:

https://github.com/MrYoungWorksheets/GoblinPadFreeware/releases/tag/v1.0.0-beta.1

## Screenshot Assets

Screenshots in `assets/` are public marketing assets for the download website.

Only approved GoblinPad preview screenshots should be committed here. Do not add private debug screenshots, manuscript captures that are not approved for marketing, or bulk image dumps from the private GoblinPad app repository.

## Never Commit Here

Do not commit:

- manuscripts
- source code from the private GoblinPad repo
- CodexBridge output
- snapshots
- reports
- logs
- test files
- development caches

## Site Files

- `index.html`
- `styles.css`
- `assets/.gitkeep`
- `assets/goblinpad-writing-desk.png`
- `assets/goblinpad-tts-scanner.png`

No build system is required. The site uses plain HTML and CSS with no dependencies and no remote scripts.
