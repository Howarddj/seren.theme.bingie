# Seren Theme for Bingie

Seren dialogs restyled to match the **Bingie** Kodi skin (Netflix layout): Netflix Sans fonts, billboard-style
fanart with left/bottom vignettes, Bingie dialog panels, grey/white focus states and the red accent.

Colours are read live from Bingie's own colour settings (Skin Settings > Colours), so changing those in Bingie
also changes this theme. Fonts come from Bingie's Font.xml (BoldNN / RegNN).

Based on the Arctic Fuse / Arctic Horizon 2 theme by Goldenfreddy0703. Requires the Bingie skin.

Install: Seren > Tools > Theme Manager > Install Theme, then either browse to a downloaded zip or enter
`https://github.com/Howarddj/seren.theme.bingie/zipball/main/`
Updates come from this repo: Seren compares the installed version with `resources/skins/meta.json` on `main`,
so bump `version` there when you push a change.

## Media flags

Source Select, Manual Caching and the Resolver show resolution, HDR, video codec, audio codec,
channel and source-type icons instead of text (icons from the `flags_color` pack, trimmed and
resized into `media/flags`). Tags with no icon in the pack get a matching outlined text badge.
UK BBFC age ratings are shown as certificate icons; other ratings stay as text.

## Windows

- `configure_provider_package.xml`
- `download_manager.xml`
- `get_sources.xml`
- `manual_caching.xml`
- `persistent_background.xml`
- `playing_next.xml`
- `provider_packages.xml`
- `resolver.xml`
- `source_select.xml`
- `still_watching.xml`
