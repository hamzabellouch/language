# Links App - Community Language Packs 🌍

Official community translation repository for the **Links** Android app.

## Repository Structure

```
├── languages_index.json       # Index catalog containing metadata for all available languages
├── languages/                 # Translation JSON files ready to be downloaded by the app
│   ├── it.json                # Italian
│   ├── pt.json                # Portuguese
│   ├── hi.json                # Hindi
│   └── ...
└── xml/                       # Original Android strings.xml files (for reference and translation tools)
    ├── strings-it.xml
    ├── strings-pt.xml
    └── ...
```

## JSON File Format

Each language JSON file in `languages/` has the following format:

```json
{
  "code": "it",
  "name": "Italiano",
  "english_name": "Italian",
  "direction": "ltr",
  "string_count": 115,
  "strings": {
    "app_name": "Links",
    "settings": "Impostazioni",
    "general_settings": "Generale",
    "language": "Lingua di visualizzazione"
  }
}
```

## Contributing a New Language

1. Fork this repository.
2. Copy `languages/en.json` or any existing language file.
3. Rename it to your language code (e.g. `nl.json` for Dutch).
4. Translate the strings under the `"strings"` key.
5. Add an entry to `languages_index.json`.
6. Submit a Pull Request!
