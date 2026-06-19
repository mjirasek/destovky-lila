# Destovky Lila

This repository is a trimmed Lila-based experiment for Destovky.

It starts from upstream `lichess-org/lila` commit `dd019da` and keeps the server/frontend source needed to study or adapt Lila's infrastructure:

- `app/` controllers and views, including lobby/account/game flow
- `modules/` domain modules
- `ui/` frontend modules
- `conf/`, `project/`, `bin/`, `scripts/`, `translation/`, and tests
- ordinary public UI assets

It intentionally omits large optional runtime assets that are not useful for early infrastructure work:

- `public/lifat/nnue`
- `public/lifat/vosk`
- `public/lifat/background`

The omitted assets accounted for most of the local clone size. The code directories are comparatively small.

This is not a static app. GitHub Pages only publishes a marker page from `static-page/`; the real Lila application requires a server/runtime setup.

Stable Destovky remains separate:

```text
https://github.com/mjirasek/destovky
https://michaeljirasek.com/destovky/
```

The Lila experiment is:

```text
https://github.com/mjirasek/destovky-lila
https://michaeljirasek.com/destovky-lila/
```
