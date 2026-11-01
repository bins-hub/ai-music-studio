# AI Music Studio v0.4 — GitHub Pages release

A standalone, no-API personal music production tracker for Suno → ChatGPT → Grok → CapCut.

## Privacy and storage
- The site stores text/URLs in **each browser's localStorage**; uploading it to GitHub Pages does NOT create an account or private sync.
- A public GitHub Pages URL can be opened by anyone. Do not paste private information into a public repository.
- Export JSON backups frequently. Audio/video files are not persisted by the web app.
- This app does not call paid AI APIs.

## Deploy without changing any other repositories
1. Create a **new public repository** named `ai-music-studio` on GitHub.
2. Upload `index.html`, `.nojekyll`, `README.md`, and `.github/workflows/pages.yml` to its `main` branch.
3. In repository Settings → Pages, choose Source: **GitHub Actions**.
4. Check the **Deploy AI Music Studio** workflow in Actions and wait until the deploy job succeeds.
5. Site URL will be `https://<github-user>.github.io/ai-music-studio/` when using a standard GitHub Pages user repository, but verify the actual `page_url` reported by GitHub before sharing.

No changes are required to existing JAPULSE, 같이가개, MOULY, or other repositories.