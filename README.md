# AWGP share links

Use [awgp.link](https://awgp.link/) for app links. [awgp.app](https://awgp.app/) serves the same routes.

- [Install the app](https://awgp.link/get)
- [Help](https://awgp.link/help/)
- [Privacy policy](https://awgp.link/privacy-policy.html)
- [Books OCR catalog](https://awgp.link/books/)

This repository keeps old GitHub Pages share links working. Its index and 404 pages send visitors to the matching route on `awgp.link`, preserving the shared item, query parameters, and fragments. The update manifest remains available for older app builds.

Push this repository to `main`. **Update live website** refreshes the private Railway website from all three public AWGP repositories and checks that this exact commit is live on both domains.

This repository owns the share footer (`index.html`), theme (`share-theme.css`), fallback pages (`index.html` and `404.html`), and compatibility update manifest (`app-update.json`). These files reach the live website automatically. Railway preserves the existing backend's rich previews, native app links, and authentication. For the update manifest, it keeps the newer version/build from this repository or the backend for each platform.

The server and rich share backend remain in the private [shiv213/awgp-mobile](https://github.com/shiv213/awgp-mobile) repository.
