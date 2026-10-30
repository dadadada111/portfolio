# Warner — Portfolio

A static, dependency-free portfolio for **Warner**, focused on four self-initiated projects:

1. `lead-desk` — Python lead normalization and scoring toolkit
2. `feed-normalizer` — JavaScript REST/GraphQL feed normalizer
3. `AI Freelance Operations Assistant` — local-first Python + Chrome MV3 workflow
4. `Travel Posting Mini-Program MVP` — uni-app/Vue H5 + WeChat prototype

## Preview locally

```bash
cd portfolio-site
python -m http.server 8080
```

Open <http://127.0.0.1:8080>.

No build step, no npm install, no external fonts or CDNs. All assets live in `assets/`.

## Deploy to GitHub Pages

1. Push this folder to a public repository (for example `dadadada111/portfolio`).
2. Repository **Settings → Pages**.
3. Source: **Deploy from a branch**; branch `main`, folder `/ (root)`.
4. Save; the site will be published at `https://dadadada111.github.io/portfolio/`.

## Structure

```text
index.html    semantic single page
styles.css    responsive editorial layout
script.js     navigation, reveal animations, footer year
assets/       project cards, avatar, cover
```

## Notes

- All project claims and test counts match the public repositories.
- The travel project is presented as an MVP, not a production SaaS.
- No analytics, trackers, cookies or external requests.
