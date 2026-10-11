# plue for Mac

<img src="icon.png" alt="Black plue logo on a white background" width="128" height="128">

The plue learning workspace in a Mac app, using the same account, courses and
saved library as the web app.

> Version 1.0.2 and its account-first setup guide are being prepared. The links
> below target the planned release; Apple notarization has passed, while
> publication and the final native visual check are still pending. The [current 1.0.1 release](https://github.com/cranesxbrand-dotcom/plue-downloads/releases/tag/v1.0.1) remains available.

[Get started on Mac](https://app.plue.si/sign-up?returnTo=%2Fget-started%2Fmac)

Create your account or sign in first. The setup guide then starts the download
and shows how to install the app, with a download button if needed. The prepared
1.0.2 installer has a designed window with an arrow from plue to Applications.

[Download Plue.dmg](https://github.com/cranesxbrand-dotcom/plue-downloads/releases/download/v1.0.2/Plue.dmg)

[Release notes and previous downloads](https://github.com/cranesxbrand-dotcom/plue-downloads/releases)

## Requirements

- An Apple Silicon Mac (M1 or later).
- macOS 13 or later.
- An internet connection.

Intel Macs are not supported by this installer. This repository contains public
installers and installation information only; application source and credentials
are not published here.

## Install or update

1. [Create your account or sign in](https://app.plue.si/sign-up?returnTo=%2Fget-started%2Fmac)
   to open the Mac setup guide.
2. Open **Plue.dmg** from Downloads. If the download did not start, use
   **Download Plue.dmg** in the guide.
3. Follow the installer arrow and drag **plue for Mac** into **Applications**.
4. Open **plue for Mac** from Applications.
5. Choose **Continue in browser** and confirm the same account you just signed
   in with. Return to the Mac window to continue.

To update an existing **plue for Mac**, quit it before replacing the app in
Applications. The installer does not remove your account or saved learning data.
The older app named **Plue** has separate browser storage and is not replaced.

Web features come from the same live app at [app.plue.si](https://app.plue.si) and
update when the app reloads. The Mac shell does not install binary updates
automatically. Install a later signed release manually when one is available.

## Verify a download

Before publication, installers must be signed with Developer ID, notarized by
Apple and include a stapled notarization ticket. Release notes must include their
exact size and hash. Those checks have passed for version 1.0.2.

Download **Plue.dmg** and [Plue.dmg.sha256](https://github.com/cranesxbrand-dotcom/plue-downloads/releases/download/v1.0.2/Plue.dmg.sha256)
into the same folder, then run from that folder:

```sh
shasum -a 256 -c Plue.dmg.sha256
```

Do not bypass macOS security warnings if a download fails verification.
