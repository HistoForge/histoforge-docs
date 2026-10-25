# Contributing

For a documentation issue, include the page link, what is unclear and the correction
you suggest. For a software problem, include your operating system and QuPath and
HistoForge versions. Do not attach patient data, private slides, account tokens or
unredacted logs.

## Edit and check

Articles live in `docs/`. Landing-page markup lives in `_templates/landing.html`;
styles and browser scripts live in `_static/`.

Use short instructions and the labels shown in the application. Explain what the
user should do and what they should see. Check behavior against the released
software before describing it as available.

After installing the dependencies in the README, run:

```bash
make test
make html
make linkcheck
```

Tests require Node.js as well as Python. For layout changes, inspect the built
pages at desktop and narrow widths, including keyboard navigation.

Use only images you have permission to share. Record their source, licence,
modifications and relevant model limitations in
[Image credits](docs/reference/image-credits.md). Preserve third-party notices.
Do not commit generated builds, private catalog snapshots or review notes.

The optional `make review` build adds local browser comments. Comments stay in
that browser; they are not shared through this repository. Use `make html` for
the normal site.
