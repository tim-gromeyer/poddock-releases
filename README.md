# Poddock — release artefacts

This repository holds the publicly reachable artefacts of the Poddock
releases: **binary tarballs** (data, x86_64, aarch64) and the
**screenshots** for the AppStream metainfo. It contains **no source code**;
the source stays private.

The tarballs are uploaded automatically by the release workflow of the
private main repository.

## Screenshots (`screenshots/`)

The AppStream metainfo of the app links the screenshots **tag-pinned**:

```
https://raw.githubusercontent.com/tim-gromeyer/poddock-releases/screenshots-3/screenshots/<name>.png
```

Flathub explicitly requires a **tag or commit — not a branch** for images
hosted in Git (MetaInfo guidelines). So the tag of the current set
(`screenshots-3`) must not be moved; new images get a new tag
(`screenshots-4`) and the metainfo in the main repository is moved over in the
same change. Older tags stay for history, but nothing links to them anymore.

Current set: `01-device.png`, `02-settings.png`, `03-capabilities.png`,
`04-device-light.png` (English UI, 1000x700 window plus shadow; the last one is
the device view in the light colour scheme).
