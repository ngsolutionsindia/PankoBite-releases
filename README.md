# PankoBite-releases

Public APK downloads for [PankoBite](https://pankobite.web.app/).

This repository contains **no source code** — only [GitHub Releases](https://github.com/ngsolutionsindia/PankoBite-releases/releases) with sideload builds.

| App | Asset |
|-----|--------|
| Android TV | `tv-release.apk` |
| Mobile | `mobile-release.apk` |

The Android app source lives in the private **PankoBite** repository.

## Publishing a new version

From the monorepo root (`e:\Projects\NGAnime`), with release APKs in place:

```powershell
.\scripts\create-github-release.ps1 -Tag v1.1
```

Then update `versionName` in the app and `appMeta` in the website, redeploy the site, and create a matching release tag here.
