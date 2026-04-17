# canto-web

Landing page for [Canto](https://canto.infinitelabs.co) — Claude's markdown companion.

Source of the site served at **https://canto.infinitelabs.co** via GitHub Pages.

## Structure

```
.
├── index.html        # the landing page (single file, inline styles)
├── assets/
│   └── icon.png      # 128×128 Canto logo
└── CNAME             # custom domain for GitHub Pages
```

## Editing

This is a single HTML file with inline CSS. To edit:

1. Open `index.html` in any editor
2. Preview locally by opening the file directly in a browser
3. Commit and push — GitHub Pages rebuilds automatically (~30 seconds)

## Related repos

- [`8infinitelabs/canto`](https://github.com/8infinitelabs/canto) — VS Code extension
- `8infinitelabs/canto-macos` — macOS app *(to be created)*

## Setup (first time)

GitHub Pages configuration:

1. Repo **Settings** → **Pages**
2. Source: **Deploy from a branch**, branch **main**, folder **/ (root)**
3. Custom domain: `canto.infinitelabs.co` (reads from `CNAME`)
4. Enforce HTTPS (enable once cert is provisioned)

DNS at `infinitelabs.co`:

```
canto    CNAME    8infinitelabs.github.io
```

## License

MIT © Infinite Labs OÜ
