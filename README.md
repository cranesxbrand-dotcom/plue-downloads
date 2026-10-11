# plue for Mac

<img src="icon.png" alt="Black plue logo on a white background" width="128" height="128">

The plue learning workspace in a Mac app. Open it to sign in and continue with
your existing account, courses and saved library. The app opens the login page
directly, without the marketing website.

[Download Plue.dmg](https://github.com/cranesxbrand-dotcom/plue-downloads/releases/download/v1.0.1/Plue.dmg)

[Release notes and previous downloads](https://github.com/cranesxbrand-dotcom/plue-downloads/releases)

## Requirements

- An Apple Silicon Mac (M1 or later).
- macOS 13 or later.
- An internet connection.

Intel Macs are not supported by this installer. This repository contains public
installers and installation information only; application source and credentials
are not published here.

## Install or update

1. Download [Plue.dmg](https://github.com/cranesxbrand-dotcom/plue-downloads/releases/download/v1.0.1/Plue.dmg).
2. Open **Plue.dmg** and drag **plue for Mac** into **Applications**.
3. Open **plue for Mac** from Applications.
4. Choose **Continue in browser**, sign in to your plue account, and confirm the
   account shown. Return to the Mac window to continue.

To update an existing **plue for Mac**, quit it before replacing the app in
Applications. The installer does not remove your account or saved learning data.
The older app named **Plue** has separate browser storage and is not replaced.

Web features come from the same live app at [app.plue.si](https://app.plue.si) and
update when the app reloads. The Mac shell does not install binary updates
automatically. Install a later signed release manually when one is available.

## Verify a download

Published installers are signed with Developer ID, notarized by Apple and include
a stapled notarization ticket. Release notes include their exact size and hash.

Download **Plue.dmg** and [Plue.dmg.sha256](https://github.com/cranesxbrand-dotcom/plue-downloads/releases/download/v1.0.1/Plue.dmg.sha256)
into the same folder, then run from that folder:

```sh
shasum -a 256 -c Plue.dmg.sha256
```

The versioned installer `plue-for-Mac-1.0.1-arm64.dmg` is the same file with a
different name. Its existing `SHA256SUMS` file remains available on the release.

Do not bypass macOS security warnings if a download fails verification.
