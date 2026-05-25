# Google Drive OAuth integration

**Summary**
Add Google Drive OAuth helpers with token caching/refresh and download helpers for Drive files used in the ingestion pipeline.

**Why**
Activity documents are often stored in Google Drive. OAuth integration enables secure, automated access to these files for the data ingestion pipeline.

**Acceptance criteria**
- `src/google_auth.py` manages credentials and token.json caching
- Downloader uses Drive API (falling back to direct links when API unavailable)
- Documentation on obtaining `credentials.json` and enabling Drive API

**Labels:** `infra`, `backend`, `security`
