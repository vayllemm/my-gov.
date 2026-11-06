# Demo Docs: static demonstration

A client-side mockup for displaying fictional sample documents. It is not connected to my.gov.uz or any government service. PIN checks and the decorative QR-like pattern are demonstrations only; they do not protect documents. Do not add real personal records or real PIN codes.

## Project details

- Framework: none (plain HTML, CSS, and browser JavaScript)
- Build command: none
- Output directory: repository root (`.`)
- Backend or environment variables: none
- Local preview: open `index.html` in a browser

All bundled data is fictional. Personal document files and the archive's original Git history were intentionally excluded from this clean public copy.

## Publish with GitHub Pages

1. Create a **public** GitHub repository and do not initialize it with a README (this folder already contains one).
2. From this folder, run:

   ```powershell
   git init -b main
   git add .
   git commit -m "Prepare static demo"
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```

3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. GitHub will show the published address under **Settings → Pages**. Project site URLs use `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

GitHub Pages publishes static files; this project needs no build step. Each later `git add`, `git commit`, and `git push` to `main` updates the site.