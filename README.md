# Flicq Clip

Lightweight gameplay clipping for macOS, by Flicq Group.

[Download the latest release](https://github.com/FinnHamer/flicq-clip-releases/releases/latest)

This repository hosts release downloads and update metadata. Development source is private. Flicq Clip is proprietary software.

Fresh installation: open the DMG, then run **Install Flicq Clip**. Its interactive setup checks for FFmpeg and opens the macOS Installer. Node.js and the CLI libraries are included. Requires macOS 13 or later; supports Apple Silicon and Intel. FFmpeg must already be installed. The installer includes the license and third-party notices.

Existing installations check for updates before recording starts. The app verifies an Ed25519-signed manifest and the download's SHA-256 before applying an update. Release notes include changes, exact hashes and completed VirusTotal report links. Scans describe a point in time and do not guarantee safety.

Downloads contain compiled application bytecode and executables, not the original development source. Compiled software can still be reverse engineered. The current installer is ad-hoc signed and has not yet been Apple Developer ID notarized.
