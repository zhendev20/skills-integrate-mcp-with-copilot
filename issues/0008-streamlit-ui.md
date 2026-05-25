# Streamlit UI (optional)

**Summary**
Add a Streamlit-based frontend that reads `data/students.json` and provides a polished search UI with student cards, activity history, and donate modal.

**Why**
A user-friendly web interface makes the system accessible to non-technical users and provides a better experience than API endpoints alone.

**Acceptance criteria**
- `streamlit_app.py` renders search input and results
- Streamlit UI code is implemented without conflicting with the existing FastAPI `src/app.py`; any shared static assets should live under `src/static/`
- Styling is provided via `src/static/styles.css` (or an equivalent file under `src/static/`) and supports responsive design

**Labels:** `frontend`, `feature`, `ui`
