# Merge tool for datasets

**Summary**
Provide a utility to merge multiple `students.json` files by MSSV, combining activity lists and summing scores, with options to replace or append.

**Acceptance criteria**
- `scripts/merge_data.py` exists and supports `--old`, `--new`, `--output`, `--replace` flags
- Merging preserves unique activities and updates totals

**Labels:** `data`, `backend`, `tooling`
