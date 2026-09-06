# Catthode for Home Assistant

> **From CRT to OLED.** Bringing warmth back to a world of cold themes. [cattho.de](https://cattho.de/)

A warm OLED theme for Home Assistant dashboards, cards, dialogs, controls, state colors, and code editors.

![Catthode Home Assistant preview](preview/catthode-home-assistant.svg)

## Install with HACS

Until the default HACS catalog submission is accepted:

1. Open HACS.
2. Choose **Custom repositories**.
3. Add `https://github.com/catthode/home-assistant` as category **Theme**.
4. Download **Catthode Theme**, restart Home Assistant, and select **Catthode** in your profile.

## Manual installation

Copy `themes/catthode.yaml` into your Home Assistant `themes` directory, ensure `frontend: themes: !include_dir_merge_named themes` is configured, then restart Home Assistant.

## Validation

CI parses the YAML, checks required semantic tokens, and runs the official HACS theme validator. A real dashboard interaction and screenshot pass remains on the manual checklist before default-catalog submission.

## License

MIT
