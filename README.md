# <img src="_static/images/brand/tissue-roi.png" width="32" height="32" alt=""> HistoForge documentation

Guides and website source for HistoForge, a histology image-analysis platform for QuPath.

Found an unclear instruction or missing topic? [Open an issue](https://github.com/HistoForge/histoforge-docs/issues)
with the page link and a short explanation.

## Build locally

Use Python 3.12:

```bash
python3.12 -m venv .venv
. .venv/bin/activate
python -m pip install -r requirements.txt
make html
```

Open `_build/html/index.html` for the landing page or `_build/html/docs/index.html`
for the guides.

See [Contributing](CONTRIBUTING.md) for editing and checks, [Branding](BRANDING.md)
for artwork preparation, and [Third-party notices](THIRD_PARTY_NOTICES.md) for
attribution. Microscopy images have separate [credits and licences](docs/reference/image-credits.md).
