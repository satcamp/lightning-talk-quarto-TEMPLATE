# SatCamp Lightning Talk — Quarto Template

A 22-slide Quarto/RevealJS presentation template for SatCamp lightning talks.
Slides auto-advance every 15 seconds (22 × 15s ≈ 5 minutes).

## Quick start

1. Install [Quarto](https://quarto.org/docs/get-started/) and [uv](https://docs.astral.sh/uv/)
2. Run `uv sync` to set up the Python environment
3. Edit `index.qmd` — update the title, author, and slide content
4. Preview: `uv run quarto preview`
5. Push to `main` — GitHub Actions will build and push to the `gh-pages` branch
6. Enable GitHub Pages: go to **Settings → Pages**, set Source to **Deploy from branch**, branch **`gh-pages`**, folder **`/ (root)`**

## Tips

- Press `o` for slide overview, `f` for fullscreen, `p` for presenter notes
- Auto-advance is enabled by default; press `a` to toggle it during the talk
- Replace placeholder SVG slides with your own content
- Slides 12–18 are blank template slides for your talk content
