# MLBB Intro Catalog

Recovered catalog metadata and downloadable content packages from Intro Tools
ML PRO 4.1.3.

## Repository files

- `catalog.json` — complete catalog with English titles and download links
  pointing to this repository's Release assets
- `catalog_links.csv` — spreadsheet-friendly catalog and source links
- `download_manifest.tsv` — manifest of unique downloaded packages

Binary content is published as GitHub Release assets rather than committed to
Git history:

- `v4.1.3` — 440 ZIP packages
- `v4.1.3-images` — 401 recovered catalog images and 6 category fallbacks
- `v4.1.3-previews` — 411 recovered video and audio previews

All non-empty `image`, `file_sc`, and `video_priview` catalog fields now point
to releases in `Sparkies01/mlbb-intro`. Dead image sources use a category
fallback. Ten catalog records whose YouTube previews were private or dead now
have an empty preview field.

## Categories

Packages are grouped locally into Anime, Game, HD/4K, Hero, Sport, and TikTok.
Release asset filenames begin with their catalog ID.

This repository is an independent archive and is not affiliated with or
endorsed by Moonton or Mobile Legends: Bang Bang. Rights to referenced games,
artwork, music, videos, and other third-party material remain with their
respective owners.
