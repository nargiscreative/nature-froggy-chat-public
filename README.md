# Nature Froggy Chat — engine + colorway CSS

The chat engine and stylesheets used by the Nature Froggy Chat widget
family (StreamElements / OBS browser source overlays).

- `engine.js` — the shared chat engine (obfuscated build)
- `css/*.css` — the four colorway skins: Deep Forest, Mitsuri Bloom,
  Starlight, Flat Green (comments stripped)

These are built artifacts — production code, not source. They're
generated from an internal, actively-maintained source tree; these files
are what's distributed publicly.

`css/*.css` still contain `{tokenName}` placeholders (font choices,
role colors, and similar) — that's StreamElements' own field-substitution
syntax, resolved by the platform when the widget is configured. It's
expected, not a bug.

No build steps, no dependencies. Drop `engine.js` and the matching
colorway's CSS in alongside the widget's HTML.

## License

This code is proprietary and All Rights Reserved — see [LICENSE](LICENSE).
Being visible in a public repository does not make it open source or
free to reuse. No copying, redistribution, modification, or reverse
engineering is permitted without written permission.
