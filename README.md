# alexisautonomy

Static site for **alexisautonomy.com** via GitHub Pages.

## Local preview

Open `index.html` directly, or run any static server.

## Deploy (GitHub Pages)

1. Push this repo to GitHub as `alexisautonomy`
2. In GitHub repo settings:
   - Pages → Build and deployment
   - Source: `Deploy from a branch`
   - Branch: `main` / root
3. Point DNS:
   - `A` records for apex (`alexisautonomy.com`) to:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - `CNAME` for `www` to `<github-username>.github.io`
4. Add `CNAME` file with `alexisautonomy.com`
