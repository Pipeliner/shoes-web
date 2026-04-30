# Shoes — playable web build

This repo hosts the playable Ren'Py-web build of Shoes via GitHub Pages.

- **Play it:** https://pipeliner.github.io/shoes-web/
- **Source:** the source project lives elsewhere; this repo is build output only.
- **Updates:** each push to `main` re-deploys the playable.

The wasm + `game.zip` are produced by `play.sh web` in the source project
(Ren'Py 8.5.2 SDK web export). The contents of this repo are the literal
contents of `web-build/`. No COOP/COEP headers are required for this
build — Ren'Py 8.5's web export does not use SharedArrayBuffer.

## Reporting issues

Issues are tracked in the source project, not here.
