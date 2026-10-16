# Apex App - Community Language Packs 🌍

Official community translation repository for the **Apex** Android app.

## Repository Structure

```
├── languages_index.json       # Index catalog containing metadata for all available languages
└── languages/                 # Translation JSON files ready to be downloaded by the app
    ├── it.json                # Italian
    ├── pt.json                # Portuguese
    ├── hi.json                # Hindi
    └── ...
```

## JSON File Format

Each language JSON file in `languages/` has the following format:

```json
{
  "code": "es",
  "name": "Español",
  "english_name": "Spanish",
  "direction": "ltr",
  "string_count": 314,
  "strings": {
    "app_name": "Apex",
    "settings": "Ajustes",
    "general_settings": "General",
    "language": "Idioma de la interfaz"
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
