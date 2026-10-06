# Borozdov Colophon

A theme from the Borozdov collection. Two faces — light **Galley**, a technical manual
typeset for a literary magazine on warm parchment, and dark **Pressroom**, the same pages
under the press lights. Warm parchment, serif headlines, monospace text and one lake blue
for what you act on.

![Borozdov Colophon in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/colophon/main/screenshots/light.png)

![Borozdov Colophon in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/colophon/main/screenshots/dark.png)

## Principles

- **Serif over mono.** Every heading, the title and pull quotes in Colophon Serif at weight
  400, never bold; the text and the interface in the platform's monospace, like a manual set
  for a literary magazine.
- **Warm parchment, never white.** An off-black ink and a warm grey scale; separation comes
  from ash hairlines and one coloured card, not shadows.
- **Colour kept for meaning.** Lake blue is only the main button and the caret; a periwinkle
  mist is the plain note and the open file; a gold wash is the highlighter.
- **Soft, generous shapes.** Pills for buttons and tags, 28px corners on callouts, 20px on
  code and tables.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as parchment cards with a serif title in the type's colour; the plain note is the
  one periwinkle card
- Pull quotes in the serif, a size up, behind an ash rule
- Plain buttons pressed in off-black, the main one in lake blue
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Ember**. Install Borozdov Ember under Settings → Appearance → Themes → Manage, then the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and choose
**Colophon** under Style Settings → Borozdov Ember → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/colophon/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Colophon/`, then choose Borozdov Colophon under Settings
→ Appearance → Themes.

## Font

Colophon Serif is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Charis SIL
(© 1997–2022 SIL International), renamed because a modified copy may not use the original's
Reserved Font Names. One weight, for the title, headings and pull quotes; the text uses your
system's monospace.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Гранка» — техническое
руководство, набранное для литературного журнала на тёплом пергаменте, и тёмный «Печатный
цех» — те же страницы под лампами типографии. Заголовки антиквой (Colophon Serif) поверх
моноширинного текста, кнопки-пилюли, одна барвинковая карточка и один озёрно-синий для того,
что вы делаете. В каталоге тема живёт вариантом Borozdov Ember: установите Borozdov Ember и плагин Style Settings, затем выберите Colophon в Style Settings → Borozdov Ember → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
