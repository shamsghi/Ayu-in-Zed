# Ayu for Zed

A port of the original Ayu family for Zed, including:

- Ayu Dark
- Ayu Mirage
- Ayu Light

## Install locally (dev extension)

1. Open Zed.
2. Run `zed: install dev extension` from the command palette.
3. Select this folder.
4. Run `theme selector: toggle` and choose an Ayu variant.

## Publish checklist

1. Create a GitHub repo and push this extension.
2. Update `repository` in `extension.toml`.
3. Bump `version` in `extension.toml` for each release.
4. Open a PR to `zed-industries/extensions` adding this repo as a submodule under `extensions/ayu-theme` and adding an `[ayu-theme]` entry in `extensions.toml`.

## Credits

- Original Ayu theme: https://github.com/dempfi/ayu
- Zed theme docs: https://zed.dev/docs/themes
