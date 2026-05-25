# Document parsers (.docx/.xlsx)

**Summary**
Implement robust parsers to extract student and activity rows from `.docx` and `.xlsx` files, normalize fields (name, student id, class, score), and return structured JSON per activity.

**Why**
Activity records are stored in various document formats. Parsers enable automated extraction and normalization of student data from these documents.

**Acceptance criteria**
- `src/parser.py` handles `.docx` tables with column detection and returns list of student dicts
- `src/sheet_parser.py` handles `.xlsx` sheets similarly
- Parsers include handling for malformed rows and return empty arrays instead of crashing

**Labels:** `data`, `backend`, `feature`
