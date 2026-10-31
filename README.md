# HoloNET Docs website

**[docs.holonet.oasisomniverse.one](https://docs.holonet.oasisomniverse.one)**: every HoloNET guide and the full API reference.

This site is **generated**. Don't edit the HTML here. Edit the Markdown in [holochain-client-csharp](https://github.com/holochain-open-dev/holochain-client-csharp) (`docs/`, `CHANGELOG.md`, `examples/README.md`), then rebuild:

```bash
python scripts/build-sites.py      # in holochain-client-csharp, with this repo checked out next to it
```

Commit and push here. Vercel deploys the static files (`vercel.json`).
