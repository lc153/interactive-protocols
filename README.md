# Interactive Lab Protocols

Multi-protocol, GitHub Pages–ready site with interactive, checkbox-enabled protocols.
Designed for easy embedding in Notion and sharing with students or lab members.

## Quick start (GitHub Pages)

1. Create a public repo on GitHub (e.g., `interactive-protocols`).
2. Upload this folder's contents to the repo root.
3. In **Settings → Pages**: set **Source** to "Deploy from a branch", Branch `main`, folder `/ (root)`.
4. After deployment, visit: `https://lc153.github.io/interactive-protocols/`
5. In Notion, type `/embed` and paste a protocol URL (e.g., `.../protocols/dna-extraction/gdna.html`).

## Structure

```
interactive-protocols/
├─ index.html
├─ LICENSE
├─ CONTENT-LICENSE
├─ README.md
├─ shared-assets/
│  └─ style.css
└─ protocols/
   └─ dna-extraction/
      └─ gdna.html
```

Add more protocols by creating new folders under `protocols/` and linking them from `index.html`.

## Notion embedding

- Use `/embed` with the full `https://...github.io/...` URL.
- Checkboxes persist **per browser/device** via `localStorage` on the `github.io` domain.
- Notion itself does not execute JS in-page; the embed runs on GitHub Pages.

## License

This project uses a dual-license model:

- **Code (HTML/CSS/JS):** MIT License — see `LICENSE`
- **Protocol text & documentation:** CC BY-NC 4.0 — see `CONTENT-LICENSE`

If you reuse, please credit: **Liam Cremona (2025)**.

## Citation (optional)

Cremona, L. (2025). *Interactive laboratory protocol collection*. GitHub repository.
