# Hero's Handbook — Official Android Releases

This public repository distributes official, precompiled Android APK releases
of **Hero's Handbook**, published under the **Camacho's Craft** brand.

**Source code is privately maintained.** The contents of this repository
are release files and documentation, not an open-source grant.

## Download

Visit [Releases](https://github.com/The1Kmacho/heros-handbook-releases/releases)
and select the newest published version. Download the file named
`heros-handbook-vX.Y.Z-android-universal.apk`.

Each official release includes a matching `.apk.sha256` checksum file.
On a computer with SHA-256 utilities, verify the downloaded APK before
installing:

```sh
sha256sum -c heros-handbook-vX.Y.Z-android-universal.apk.sha256
```

On Android, installation from GitHub may require temporarily granting
your browser or file manager permission to install apps from that source.
Only use releases you trust. Directly installed APKs do not automatically
receive Google Play updates.

## Licensing

**Copyright © 2026. All Rights Reserved.** Hero's Handbook is free to
use under the terms of the [Proprietary Freeware License](LICENSE.md).
Free download does **not** authorize copying, modification, redistribution,
reverse engineering (except as permitted by applicable law), rebranding,
resale, or ownership claims.

Third-party components remain governed by their own applicable licenses.

## Notes for Android updates

Android updates usually require the APK to be signed with the same
certificate as the installed version. Test builds and official builds
may have different signing keys. Back up your data before uninstalling
older builds; an uninstall may erase local application data.

## Distribution integrity

Official APKs and checksums are built by the private Hero's Handbook CI
pipeline and published here after validation. This repository does not
contain build scripts, development source, signing credentials, or private
CI outputs.
