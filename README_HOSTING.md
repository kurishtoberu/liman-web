# PT Liman Bangun Utama Static Website

This build uses folder-based clean URLs and is ready for static hosting.

## URL structure

- `/` → Home page
- `/tira-hill-living/` → Tira Hill Living detail page
- `/kutilang-living/` → Kutilang Living detail page

Legacy `.html` files are included only as redirect fallbacks:

- `/tira-hill-living.html` redirects to `/tira-hill-living/`
- `/kutilang-living.html` redirects to `/kutilang-living/`

## Upload structure

Upload all contents of this folder to the hosting root, for example `public_html/`.

```
public_html/
├── index.html
├── tira-hill-living/
│   └── index.html
├── kutilang-living/
│   └── index.html
├── assets/
├── tira-hill-living.html
├── kutilang-living.html
└── .htaccess
```

## Local test

Run from this folder:

```bash
python -m http.server 8080
```

Open:

```text
http://localhost:8080
```
