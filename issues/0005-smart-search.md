# Smart search endpoint

**Summary**
Add a search endpoint that supports O(1) MSSV lookup (hash map) and fuzzy/diacritics‑insensitive name search for partial matches.

**Acceptance criteria**
- `src/searcher.py` implements `search_student(query)` with exact/id and fuzzy name searches
- Add API endpoint `/search?q=<query>` that returns matched students and counts
- Include unit tests for search behavior

**Labels:** `backend`, `feature`, `api`
