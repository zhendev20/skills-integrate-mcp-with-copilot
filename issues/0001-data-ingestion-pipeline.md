# Data ingestion pipeline

**Summary**
Add a data ingestion pipeline to extract activity links from an Excel sheet, download linked DOCX/XLSX files (Google Drive support), and store raw activity files under `data/downloaded` for parsing.

**Why**
This project currently uses an in-memory activities structure. A pipeline will allow importing real-world activity records from administrative spreadsheets and archived documents.

**Acceptance criteria**
- `scripts/build_data.py` or equivalent exists and can be run locally
- Downloads documents into `data/downloaded/`
- Produces a raw JSON (`data/raw_activities.json`) with per-activity metadata and file paths
- Includes basic error logging for failed downloads (`data/error_links.json`)
- Generated outputs under `data/` (including `data/downloaded/`, `data/raw_activities.json`, and `data/error_links.json`) are treated as local artifacts and kept out of version control by default (for example via `.gitignore`), or the output directory is configurable

**Labels:** `data`, `backend`, `enhancement`
