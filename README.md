# SeaGlass Studio releases

This public repository contains only versioned Windows x64 installers, their Tauri updater signatures, release notes, and channel manifests. It does not contain application source, private signing keys, credentials, or development configuration.

## Update feeds

- Beta: `https://raw.githubusercontent.com/Supah9889/seaglass-studio-releases/main/beta/latest.json`
- Stable: `https://raw.githubusercontent.com/Supah9889/seaglass-studio-releases/main/stable/latest.json`

The beta feed is updated explicitly and does not use GitHub's `/releases/latest`, which excludes prereleases. Each version's installer and signature live under its versioned channel directory. The beta manifest signature is generated from that installer by the official Tauri 2 signer.

No stable SeaGlass Studio release has been published yet. Add the stable manifest and versioned artifacts when the first stable version is approved.
