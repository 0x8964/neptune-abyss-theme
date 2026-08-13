# Neptune Abyss — Premium Dark Theme for VS Code

🌊 **Neptune Abyss** is a modern, blue-centric dark color theme for Visual Studio Code. It favors readable contrast, calm blues for syntax accents, and unobtrusive UI colors so you can focus on code.

Repository: [https://github.com/0x8964/neptune-abyss-theme](https://github.com/0x8964/neptune-abyss-theme)

## Highlights

- Carefully balanced blue-focused palette for long sessions
- Clean UI and high readability on large and small displays
- Comprehensive TextMate and semantic token coverage
- Lightweight, minimal styles with visual clarity for symbols, types, and UI states
- No italic syntax by default
- 580+ workbench colors fully themed
- 80+ TextMate token rules across JS/TS, Python, Rust, Go, CSS, Markdown, JSON, YAML, TOML and more

## Core Palette

| Role              | Hex        |
|-------------------|------------|
| Primary Blue      | `#58A6FF`  |
| Soft Blue         | `#79C0FF`  |
| Pale Blue         | `#BFDFFF`  |
| Cyan Accent       | `#56B6C2`  |
| Purple Blue       | `#7AA2F7`  |
| Sky Blue          | `#9CDCFE`  |
| Light Blue        | `#82AAFF`  |
| Aqua              | `#7DCFFF`  |
| Blue              | `#61AFEF`  |
| Muted             | `#9CA3AF`  |
| Error             | `#DE5F6A`  |
| Background        | `#0B0F16`  |
| Surface           | `#121A26`  |
| Text              | `#E6EDF3`  |
| White             | `#FFFFFF`  |

## Language Support

- **JavaScript / TypeScript** — functions, methods, arrow functions, types, interfaces, decorators, DOM variables, template expressions
- **Python** — builtins, magic methods, decorators, f-strings, type hints, match/case, ellipsis
- **Rust** — types, lifetimes, attributes, macros, match arms, closures, unsafe blocks
- **Go** — packages, imports, builtins, channels, goroutines, struct tags
- **CSS / SCSS / Less** — properties, selectors, functions, units, pseudo selectors, at-rules
- **Markdown** — headings, links, code blocks, lists, bold/italic, quotes, diff markers
- **JSON / JSONC / TOML / YAML** — keys, values, tags, anchors, aliases

## Installation

Install from the Marketplace:

1. Open the link above or search `Neptune Abyss` in the VS Code Extensions view.
2. Click `Install`.

Install from a local VSIX (developer build):

```bash
npm install
npm run package
# then from VS Code: Extensions > ... > Install from VSIX...
```

## Development / Preview

- Open the repository folder in VS Code.
- Press `F5` to launch the Extension Development Host.
- In the host window, select `Preferences: Color Theme` → **Neptune Abyss** to preview changes.

## Contributing (Fork & Pull Requests)

Contributions are welcome. Follow these steps to contribute cleanly:

1. Fork this repository on GitHub.
2. Create a branch for your change: `git checkout -b feat/my-theme-adjustment`.
3. Make focused edits to `themes/neptune-abyss-color-theme.json` or supporting files.
4. Run the extension locally and verify the change via `F5`.
5. Include a short description and 1–3 screenshots in your pull request.
6. Push your branch and open a Pull Request against `main`.

Guidelines:

- Keep changes small and thematically consistent — large palette overhauls make reviews hard.
- Prefer editing or adding single TextMate or semantic token entries rather than sweeping global replacements.
- If you alter UI colors (workbench colors), include before/after screenshots and justify accessibility.

## Issues & Support

- Open issues for bugs, accessibility concerns, or language-specific token problems.
- Mark the issue with a short reproduction: language, sample code, expected vs. actual colors.

## Troubleshooting

- If your theme changes don't appear, reload the window or restart the Extension Development Host.
- Ensure the language supports semantic tokens to see semantic coloring.

## License

This repository is licensed under the MIT License — see [LICENSE](https://github.com/0x8964/neptune-abyss-theme/blob/HEAD/LICENSE) for details.
