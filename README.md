# 二十四刻 APK releases

This repository **only hosts Android APK release binaries** for 二十四刻.

- **No source code** is published here.
- Source remains in a private repository.
- Public download page: https://melrain.github.io/ershisi-ke-releases/

## Latest APK

- **Download page:** https://melrain.github.io/ershisi-ke-releases/
- **Stable latest URL:** https://github.com/Melrain/ershisi-ke-releases/releases/latest/download/ershisi-ke-latest.apk
- **Current version:** 0.1.27
- **SHA-256:** `2a867cfc5e634330a53a79660ae2ba86fec7f14227d62729732af9cfe8867131`
- **This version file:** https://github.com/Melrain/ershisi-ke-releases/releases/download/v0.1.27/ershisi-ke-0.1.27-release.apk
- **All releases:** https://github.com/Melrain/ershisi-ke-releases/releases/latest

## Publishing a new release

Keep the download page URL stable:

1. Upload the versioned APK, e.g. `ershisi-ke-x.y.z-release.apk`.
2. Upload the **same file again** as `ershisi-ke-latest.apk`.
3. Update `index.html` with the new version number and SHA-256.

`/releases/latest/download/ershisi-ke-latest.apk` always points at the newest GitHub release that contains an asset named `ershisi-ke-latest.apk`.
