# n8n-workflows

Public sbírka mých n8n workflow exportů.

## Workflows

- **`calendar-briefing.json`** — denní ranní briefing (Po–Pá 7:00) na Telegram. Agreguje události z Google Kalendáře a počasí z Open-Meteo (Olomouc).
- **`backup-n8n-workflows-to-google-drive.json`** — denní záloha (2:30) všech workflow přes n8n API do Google Drive jako JSON.

## Použití

V n8n: **Workflows → Import from File** → vyber `.json`. Pak nastav credentials (Google Drive, Telegram, n8n API) a aktivuj.
