The profile graphics reuse the portfolio's tilted grid, translucent neutral panels,
Bricolage Grotesque titles, and Manrope supporting lettering. The graphics use
only neutral colors, with restrained borders and no decorative window illustration.
Every letter is an SVG path, so rendering requires no installed fonts or remote resources.
The images have transparent backgrounds and separate light and dark palettes.

To regenerate from the repository root:

```sh
python3 -m venv /tmp/readme-assets-venv
/tmp/readme-assets-venv/bin/pip install fonttools==4.66.1
/tmp/readme-assets-venv/bin/python scripts/generate_readme_assets.py
```

The bundled source fonts come from Google's font repository:
[Bricolage Grotesque](https://github.com/google/fonts/tree/main/ofl/bricolagegrotesque)
and [Manrope](https://github.com/google/fonts/tree/main/ofl/manrope).
Their SIL Open Font Licenses are included alongside the font files.

Previews in `previews/` are local browser renders using GitHub-style Markdown CSS.
They show the README at desktop width; GitHub may change its surrounding spacing or styles.
