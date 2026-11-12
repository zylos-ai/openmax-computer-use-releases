# OpenMax Computer Use releases

Public macOS installers and independent update manifests for OpenMax Computer Use.
The application source repository is private. Client executables remain inspectable;
bundling and minification are not a confidentiality guarantee.

Download the ZIP for Apple Silicon (`arm64`) or Intel (`x64`) from
[Releases](https://github.com/zylos-ai/openmax-computer-use-releases/releases).
macOS 14 or later is required. Release notes state signing and notarization status.

The app checks version information independently of agent pairing or connectivity.
Checking does not interrupt tasks or download an installer. Choose **Download and
Update** locally to interrupt agent work, download, install, and restart. Pause and
Stop restrictions persist; updates do not resume work automatically.

Update metadata is published under `mac/arm64/latest-mac.yml` and
`mac/x64/latest-mac.yml` after the corresponding immutable versioned ZIPs are
available. Each manifest includes SHA-512 and archive size. Release checksum files
also provide SHA-256 for manual verification.

This repository contains distribution metadata and installer artifacts only.
Dependency license notices are included in the application package.
