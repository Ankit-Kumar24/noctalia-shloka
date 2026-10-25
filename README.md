# Shloka

> कर्मण्येवाधिकारस्ते मा फलेषु कदाचन ।
> _karmaṇy evādhikāras te mā phaleṣu kadācana_
>
> You have a right to your work, never to its fruits. — Bhagavad Gita 2.47

A Bhagavad Gita verse widget for [Noctalia](https://noctalia.dev). Shows a verse in Sanskrit with transliteration and an English or Hindi translation, on your desktop or lock screen.

## Features

- Sanskrit verse in Devanagari, Roman transliteration, and English/Hindi translation
- Random verse on a timer, or one verse per day
- Previous, next, and copy-to-clipboard buttons
- Three layouts: wide, square, tall

## Requirements

Noctalia v5 with plugin API 12 or newer.

## Installation

1. Clone this repository into Noctalia's local plugin folder:

   ```
   git clone https://github.com/Ankit-Kumar24/noctalia-shloka ~/.local/share/noctalia/plugins/shloka
   ```

2. Enable the plugin:

   ```
   noctalia msg plugins source add local path ~/.config/noctalia/plugins

   noctalia msg plugins list | grep shloka

   noctalia msg plugins enable ankitkumar/shloka

   ```

   Or toggle **Shloka** on in **Settings → Plugins**.

## Credits

- Verse text and translations are derived from [vedicscriptures/bhagavad-gita-data](https://github.com/vedicscriptures/bhagavad-gita-data), licensed under LGPL-3.0. Translators are credited on each verse in the widget.
- Sanskrit font: [Tiro Devanagari Sanskrit](https://fonts.google.com/specimen/Tiro+Devanagari+Sanskrit), licensed under the SIL Open Font License (see `fonts/OFL.txt`).

## License

GPL-3.0-or-later. See [LICENSE](LICENSE).
