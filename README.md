# Ashmoreth

A dark and light theme for [Obsidian](https://obsidian.md) that makes notes look like a printed book: justified serif text, drop caps, § before section headings, double-rule blockquotes and an asterism (⁂) for `---`, etc

## Install

Copy `manifest.json` and `theme.css` into `<vault>/.obsidian/themes/Ashmoreth/`, then pick **Ashmoreth** under *Settings → Appearance → Themes*.

## Light and dark

- **Dark**: gold on slate
- **Light**: brown ink on cream

## What it does

Every h2 gets a § and its first paragraph opens with a gold drop cap (drop caps are reading view only). Blockquotes sit between two rules with a big quote mark, `---` becomes ⁂ and `==highlights==` turn into a marker underline. Tabs are narrower, the file explorer is smaller with folders in caps, and backlinks at the bottom of a note stay faded until you hover them.

## Extra callouts

```markdown
> [!subtitle]
> A centred italic line under the note title

> [!abstract] Abstract
> A short summary, always expanded, with a thin gold rule on the left.
```

## Tweaking

- **UI sizes** ([theme.css:441](theme.css#L441)): this is my personal setting and it looks good on my screen, but I tested it on smaller screens and it might be too small for some people. Tweak it, or delete the whole block to get Obsidian's normal sizes back.
- **Sync icons** ([theme.css:554](theme.css#L554)): off by default. If you use Obsidian Sync and don't want the icons, remove the comment around the block. I just don't like how they look.
- **Fading backlinks** ([theme.css:583](theme.css#L583)): delete this block if you think that's bloat.

## Fonts

All fonts are embedded so the theme works offline, and all of them are free to redistribute. See [FONTS.md](FONTS.md).

| CSS name | Font | Used for |
|---|---|---|
| AshDisplay | Bodoni Moda SC | Note title, h1, drop caps |
| AshNav | Cinzel | h4–h6, tabs, sidebar, table headers |
| AshBody | Old Standard TT | Body text |
| AshMono | basis33 | Code and properties |

## Licence

Theme code: MIT, see [LICENSE](LICENSE). Fonts: see [FONTS.md](FONTS.md).
