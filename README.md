# SatCamp Lightning Talk Template (Quarto)

A [Quarto RevealJS](https://quarto.org/docs/presentations/revealjs/) template for 5-minute [SatCamp](https://satcamp.xyz) lightning talks. Slides auto-advance every 15 seconds. 20 slides × 15 seconds = 5 minutes.

**Live demo:** [https://satcamp.github.io/lightning-talk-quarto-TEMPLATE/](https://satcamp.github.io/lightning-talk-quarto-TEMPLATE/)

---

## Create your own deck

1. Create a new repository under your account:
  - Select **Use this template → Create a new repository**
  - Give the repository a name.
  - Choose Public visibility (so you can create GitHub Pages)
  - Click **Create repository**
2. Enable GitHub Pages:
  - Go to **Settings → Pages** in your new repo
  - Under **Source**, select **GitHub Actions**
  - Push any change to `main` — the workflow in `.github/workflows/publish.yml` will build and deploy automatically
  - Your deck will be live at `https://<your-username>.github.io/<repo-name>/`
    - [ ] Share this URL with the SatCamp organizers

---



## Local Setup / Development

To develop the content locally, clone your repo and run quarto in "preview" mode:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
uv sync
uv run quarto preview
```

Open the preview URL in your browser. The deck auto-advances — to turn off auto-advance during editing, append `?autoSlide=0` to the URL (e.g. `http://localhost:4200/?autoSlide=0`).

---


## What to edit

Edit the `index.md` file to update the slide content.