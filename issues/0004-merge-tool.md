# Merge tool for datasets

**Summary**
Provide a utility to merge multiple `students.json` files by MSSV, combining activity lists and summing scores, with options to replace or append.

**Why**
When processing data from multiple sources or time periods, a merge tool is needed to combine datasets without losing information or creating duplicates.

**Acceptance criteria**
- `scripts/merge_data.py` exists and supports `--old`, `--new`, `--output`, `--replace` flags
- Merging preserves unique activities and updates totals

**Labels:** `data`, `backend`, `tooling`
