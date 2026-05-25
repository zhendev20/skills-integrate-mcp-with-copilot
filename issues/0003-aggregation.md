# Aggregation & students.json

**Summary**
Aggregate parsed activity records by student ID (MSSV), compute totals and basic stats, and write `data/students.json` used by the app for lookups.

**Why**
Individual activity records need to be consolidated per student to provide a complete view of each student's participation history and statistics.

**Acceptance criteria**
- `src/aggregator.py` with `aggregate_by_student()` and `save_json()` implemented
- `data/raw_activities.json` is treated as the canonical input dataset for aggregation and is source-controlled if sample/default input data is required by the project
- Produces `data/students.json` as generated output with structure: `{ mssv: { info: {...}, history: [...], stats: {...} } }`
- CLI or script to regenerate `data/students.json` from `data/raw_activities.json`
- Document that `data/students.json` is generated (not hand-edited) and should be git-ignored by default to avoid accidental commits of large or sensitive derived data

**Labels:** `data`, `backend`, `enhancement`
