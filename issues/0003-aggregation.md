# Aggregation & students.json

**Summary**
Aggregate parsed activity records by student ID (MSSV), compute totals and basic stats, and write `data/students.json` used by the app for lookups.

**Why**
Individual activity records need to be consolidated per student to provide a complete view of each student's participation history and statistics.

**Acceptance criteria**
- `src/aggregator.py` with `aggregate_by_student()` and `save_json()` implemented
- Produces `data/students.json` with structure: `{ mssv: { info: {...}, history: [...], stats: {...} } }`
- CLI or script to regenerate from `data/raw_activities.json`

**Labels:** `data`, `backend`, `enhancement`
