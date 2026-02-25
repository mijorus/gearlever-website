---
title: Codeberg Updates
aliases:
- "/docs/codebergupdater"
---

The following shows how to configure an app to use Codeberg as the update source, for Gear Lever 4.+.

Let's use https://codeberg.org/sonusmix/sonusmix as an example.

### Repo URL
This should be the URL of the repo, without additional parameters:

`https://codeberg.org/sonusmix/sonusmix`


### Release file name
This should be the name of the file from the releases tab; you can use globe (*) patterns to indicate variables
in the file name.

`org.sonusmix.Sonusmix-*.AppImage`

Pay attention as many apps today have separate releases for x86_64 and arm64 platforms.