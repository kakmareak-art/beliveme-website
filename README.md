# 🌐 BeliveMe Website (Public Landing Page)

This folder contains the standalone public landing page for the BeliveMe application.

## 🚀 How to Deploy as a Standalone Public Repository

To keep your Android App source code repository **PRIVATE**, deploy this website in a separate **PUBLIC** repository on GitHub:

1. Create a new public repository on GitHub named `beliveme-website` (or `<YOUR_GITHUB_USERNAME>.github.io`).
2. Copy the files from this `website/` folder (`index.html`, `styles.css`, `CNAME`) to the root of the new public repository.
3. Push to GitHub.
4. Go to **Settings** -> **Pages** in the `beliveme-website` repository:
   - **Source**: Deploy from a branch (`main` / `/root`).
   - **Custom Domain**: Set to `beliveme.is-a.dev`.
5. Once DNS propagates via `is-a.dev`, check **Enforce HTTPS**.
