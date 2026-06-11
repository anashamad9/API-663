# API-663

Live JSON file is generated from Google Sheets by GitHub Actions every 30 minutes.

## Public JSON Links

- `pending.json`  
  `https://raw.githubusercontent.com/anashamad9/API-663/main/pending.json`

## CDN Links (faster for frontend apps)

- `https://cdn.jsdelivr.net/gh/anashamad9/API-663@main/pending.json`

## Notes

- The Google Sheet must be shared as `Anyone with the link` (Viewer).
- If the tab `gid` is invalid, `pending.json` is written as `[]` and a warning appears in the workflow logs.
