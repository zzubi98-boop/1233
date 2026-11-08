# FrontBaseball Manager Browser Edition

- App path: `/baseball/` (`baseball/index.html`).
- Save JSON is read from the browser file picker and processed in browser memory only. No save upload or remote database is implemented.
- Reloading the page loads the latest deployed code; select the save JSON again after refresh.

## Included
- All-team player list, team filter, position filter, name/ID search, sortable columns.
- Team overview selector.
- FA market from `fa.pool` and `fmarket`, plus `draftClass` and available draft history metadata.
- Original JSON copy and download.

## Limitations
This is the initial GitHub browser migration, not yet a complete port of the desktop app or previous Pyodide package. Advanced contract evaluation, season review, player grading, finance/position reports, and ChatGPT prompt generation remain to be migrated and tested. FA classification uses only source fields and should not be treated as an inferred official eligibility rule.

## GitHub Pages
Repository Pages was not enabled when checked. In Settings → Pages, select **Deploy from a branch**, branch `main`, folder `/(root)`, and save. The existing TRPG page at `/` is preserved; FrontBaseball will be served at `/baseball/`.
