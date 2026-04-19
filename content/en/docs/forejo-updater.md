---
title: Forgejo Updates
aliases:
- "/docs/forgejoupdater"
---

## Using the GUI

The following shows how to configure an app to use Forgejo as the update source, for Gear Lever 4.+.

Let's use https://git.eden-emu.dev/eden-emu/eden as an example.

### Repo URL
This should be the URL to the repo, without additional parameters.

`https://git.eden-emu.dev/eden-emu/eden`


### Release file name
This should be the name of the file from the relases tab; you can use glob (*) patterns to indicate variables
in the file name.

`Eden-Linux-*-amd64-clang-pgo.AppImage`

Pay attention as many apps today have releases for both x86_64 and arm64 platforms.


### Allow pre-releasese

I/O switch to enable update pre-releases: some apps might release new versions flagged 
as "drafts", which will be ignored when this flag is OFF.
