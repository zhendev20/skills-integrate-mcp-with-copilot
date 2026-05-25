# Search analytics & logging

**Summary**
Log search queries and basic usage metrics to `data/search_logs.json` and provide a small analytics view or aggregated CSV.

**Acceptance criteria**
- `src/search_logger.py` with `log_search(query, result_count)` implemented
- Logs saved to `data/search_logs.json`
- Optional `scripts/analytics.py` to summarize top queries and usage

**Labels:** `analytics`, `backend`, `feature`
