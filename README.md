# n8n-workflows

Public collection of my n8n workflow exports.

## Workflows

- **`calendar-briefing.json`** — daily morning briefing (Mon–Fri 7:00) sent to Telegram. Aggregates Google Calendar events and Open-Meteo weather (Olomouc).
- **`backup-n8n-workflows-to-google-drive.json`** — daily backup (2:30) of all workflows via the n8n API to Google Drive as JSON.

## Usage

In n8n: **Workflows → Import from File** → pick the `.json`. Then set credentials (Google Drive, Telegram, n8n API) and activate.
