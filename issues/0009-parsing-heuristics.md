# Robust parsing heuristics & error logs

**Summary**
Improve parsers with heuristics: flexible column detection (Vietnamese variants), smart ID/class swap, score normalization, and comprehensive error logging for problematic rows and files.

**Why**
Real-world documents have inconsistent formatting and naming conventions. Robust heuristics reduce manual data cleaning and improve parsing success rates.

**Acceptance criteria**
- Parsers detect common column name variants and map to normalized fields
- Implement `smart_swap_id_class()` to recover swapped columns
- Errors appended to `data/error_links.json` or separate parsing log

**Labels:** `data`, `backend`, `bug`
