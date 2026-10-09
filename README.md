# Aurora Glass Theme

Aurora Glass is a dark Visual Studio Code color theme with an IntelliJ-inspired workbench hierarchy, layered charcoal surfaces, and a restrained blue-violet identity. It uses the standard VS Code color-theme API and remains a declarative theme extension.

## Design Philosophy

The editor stays calm and readable for long sessions. Distinct charcoal surfaces separate the activity bar, Explorer, editor, tabs, panels, and popups. Electric blue carries primary interactions; violet, cyan, pink, and warm orange provide occasional secondary accents. Familiar VS Code Dark+ syntax conventions keep code scanning straightforward.

The Liquid Glass reference is expressed through layered colors and fine borders only. The theme does not recreate the IntelliJ interface or use proprietary assets.

## Palette

| Role | Color |
| --- | --- |
| Editor | `#101114` |
| Window and activity bar | `#111318` / `#15171D` |
| Explorer | `#181A20` |
| Secondary panels | `#1B1D24` |
| Elevated widgets | `#222630` |
| Hover surface | `#292D38` |
| Active selection | `#263B62` |
| Primary text | `#F3F4F8` |
| Secondary text | `#C3C8D4` |
| Muted text | `#8B92A3` |
| Electric blue | `#4C8DFF` |
| Bright blue | `#69A5FF` |
| Ice cyan | `#63D9FF` |
| Primary violet | `#8B5CF6` |
| Soft lavender | `#B7A0FF` |
| Pink and warm orange | `#F472D0` / `#FFAD70` |

## Features

- Layered dark surfaces and restrained borders distinguish the main workbench areas.
- Blue active indicators, focused selections, and cursor colors coordinate with violet secondary accents.
- Explorer selection and hover states use native list and tree colors.
- Semantic and TextMate syntax roles use familiar Dark+ colors for keywords, strings, functions, types, comments, and values.
- Terminal ANSI colors, Git decorations, diagnostics, diff views, and editor widgets share the same workbench palette.

## Version

- Extension: **Aurora Glass Theme**
- Theme: **Aurora Glass**
- Package version: `0.0.1` (unpublished)
- Variant: dark

## Installation and Activation

For local development, open this project in VS Code and press `F5` to launch the Extension Development Host. In the new window, open the Color Theme picker with `Ctrl+K Ctrl+T` on Windows/Linux or `Cmd+K Cmd+T` on macOS, then choose **Aurora Glass**.

The extension is not yet published. After publication, it can be installed from the Extensions view and activated through the same Color Theme picker.

## Screenshots

Preview screenshots are not included yet.

- Explorer and editor: screenshot placeholder
- Terminal and bottom panels: screenshot placeholder

## Typography

A color theme cannot bundle a font or change editor typography. JetBrains Mono is an optional choice for an IntelliJ-like coding feel; the theme works with any installed font. For example, add these settings manually if JetBrains Mono is installed:

```json
{
	"editor.fontFamily": "'JetBrains Mono', monospace",
	"editor.fontSize": 13
}
```

## Known Limitations

Standard VS Code themes can set supported colors and alpha-bearing values, but cannot add arbitrary corner radii, true backdrop blur, custom panel layouts, or continuous gradients. Aurora Glass approximates layered glass through color and border choices only. Rounded-looking tabs and panels depend on native VS Code rendering and user settings.

No formal WCAG conformance audit has been performed. VS Code continues to provide icons, labels, and underlines alongside diagnostic colors.

## Development

The theme is registered in `package.json` as **Aurora Glass**, with the `vs-dark` base and `./themes/Aurora Glass-color-theme.json` path. See [CHANGELOG.md](CHANGELOG.md) and [Visual Studio Code's color theme guide](https://code.visualstudio.com/api/extension-guides/color-theme) for development details.
