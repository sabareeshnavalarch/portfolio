# Sabareesh B S — Naval Architect Portfolio

A single-page website version of your PDF portfolio (2021–2026), ready to publish for free with GitHub Pages.

## Folder contents

```
sabareesh-portfolio/
├── index.html      ← the whole site (one file)
├── images/          ← all photos, renders and drawings used on the site
└── README.md
```

## Publish it with GitHub Pages (free, ~5 minutes)

1. **Create a repository**
   Go to [github.com/new](https://github.com/new). Name it whatever you like — for a URL like `yourname.github.io`, name the repo exactly `<your-github-username>.github.io`. Any other name also works, it'll just live at `yourusername.github.io/repo-name`. Make it **Public**.

2. **Upload these files**
   On the new repo's page, click **Add file → Upload files**, then drag in `index.html`, the `README.md`, and the whole `images` folder (drag the folder itself — GitHub keeps the folder structure). Commit the changes.

3. **Turn on Pages**
   Go to the repo's **Settings → Pages**. Under "Build and deployment", set **Source** to `Deploy from a branch`, pick branch `main` and folder `/ (root)`, then **Save**.

4. **Visit your site**
   After a minute or two, GitHub shows the live URL at the top of that same Pages settings screen — usually:
   - `https://<username>.github.io/` (if you named the repo `<username>.github.io`), or
   - `https://<username>.github.io/<repo-name>/` otherwise.

That's it — no build step, no server, it's a static site.

## Making changes later

- **Text**: open `index.html` in any text editor (or GitHub's own web editor — click the pencil icon on the file) and edit the text between the HTML tags.
- **Photos**: replace a file in `images/` with a new one of the same name, or add new images and reference them in `index.html` with `<img src="images/yourfile.jpg">`.
- Every time you commit a change on GitHub, the live site updates automatically within a minute or so.

## Notes

- The site uses Google Fonts (Fraunces, Inter, IBM Plex Mono) loaded from a CDN, so it needs an internet connection to show the exact fonts — it still looks fine with fallback fonts if that's ever blocked.
- All images were extracted and cropped from your original PDF, then compressed for fast loading (~1.9 MB total).
