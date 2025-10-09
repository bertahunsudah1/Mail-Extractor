# Mail-Extractor

[![Build](https://img.shields.io/github/actions/workflow/status/NaldyXploit-ID/Mail-Extractor/python.yml?branch=master)](https://github.com/NaldyXploit-ID/Mail-Extractor/actions)
[![License](https://img.shields.io/github/license/NaldyXploit-ID/Mail-Extractor)]
[![Last Commit](https://img.shields.io/github/last-commit/NaldyXploit-ID/Mail-Extractor)]

Ekstraktor Alamat Email Dari Halaman Atau File Dengn Filter Untuk Mengurangi False-Positive.

**Developer:** NaldyXploit  
**Version:** 4.2  
**Release:** 2025-10-16

---

## Screenshot (placeholder)
![screenshot](.github/assets/screenshot.png)

---

## Features
- Realistic JSON generator CLI
- Examples & schema
- Tests & CI
- Pre-commit & dependabot
- Release, PR, Issue, Project board
- Stats updater

## Install
```bash
git clone https://github.com/NaldyXploit-ID/Mail-Extractor.git
cd Mail-Extractor
python3 -m pip install -r requirements.txt || true
```

## Usage
```
python3 main.py --count 5 --pretty
python3 main.py -s examples/Mail-Extractor-examples/schema_example.json --pretty
```

## Tests
```
pytest Mail-Extractor-tests -q
```

## License
MIT
2025-10-16 12:36:49 - docs: improve README with badges
