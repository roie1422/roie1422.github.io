# roie1422.github.io

The public page of CollecList: download and invite links (spec 6.2).
Source: `site/` in the private `colleclist` repository; copied here as is.

- `index.html` — download page. The installer is the latest Release asset `CollecList.apk`.
- `join/` — `https://roie1422.github.io/join/?t=<token>` opens the app (verified App Link) or offers the download.
- `.well-known/assetlinks.json` — lets Android open `/join` links in the app (release signing certificate).
- `.nojekyll` — GitHub Pages must serve `.well-known`.
