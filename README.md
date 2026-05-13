# MiniSki Web

Playable web build of MiniSki, a tiny mobile-first downhill skiing arcade game built in Godot.

The Godot source project lives in a separate private repository. This repository is only the static web export used for GitHub Pages hosting.

Live site:

```text
https://david-vz.github.io/MiniSki-Web/
```

## Repository Role

This repository is public so GitHub Pages can host the game on the free Pages path. It should contain only the exported files from Godot:

- `index.html`
- `index.js`
- `index.wasm`
- `index.pck`
- Godot web audio worklets
- exported icons/images
- `.nojekyll`

Do not add Godot source files, scenes, scripts, assets, or editor cache here.

## Pages Configuration

GitHub Pages should be configured as:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

GitHub Pages may cache files for several minutes. If a newly pushed build does not appear immediately, hard refresh or test with a query string such as:

```text
https://david-vz.github.io/MiniSki-Web/?v=<commit-sha>
```

## Publishing Source

The canonical source and deployment process are documented in the private source repository at:

```text
docs/operations.md
```
