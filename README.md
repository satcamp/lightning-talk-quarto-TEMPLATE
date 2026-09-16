# SatCamp Lightning Talk Template (Quarto)

A [Quarto RevealJS](https://quarto.org/docs/presentations/revealjs/) template for 5-minute [SatCamp](https://satcamp.xyz) lightning talks. Slides auto-advance every 15 seconds. 20 slides × 15 seconds = 5 minutes.

**Live demo:** https://satcamp.github.io/lightning-talk-quarto-TEMPLATE/

---

## Create your own deck

1. Go to **[Use this template](https://github.com/new?template_name=lightning-talk-quarto-TEMPLATE&template_owner=satcamp)** on GitHub
2. Create a new repository under your account
3. Enable GitHub Pages:
   - Go to **Settings → Pages** in your new repo
   - Under **Source**, select **GitHub Actions**
   - Push any change to `main` — the workflow in `.github/workflows/publish.yml` will build and deploy automatically
   - Your deck will be live at `https://<your-username>.github.io/<repo-name>/`

---

## Local Setup / Development

Clone your repo locally:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
uv sync
uv run quarto preview
```

Open the preview URL in your browser. The deck auto-advances — append `?autoSlide=0` to the URL (e.g. `http://localhost:4200/?autoSlide=0`) to turn off auto-advance during editing.

---

## What to edit

Edit the `index.md` file to update the slide content.
