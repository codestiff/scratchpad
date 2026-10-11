# Scratchpad

Static board mockups for GitHub Pages.

## Publish

In repository Settings → Pages, select **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.

Expected site URL once Pages is enabled: https://codestiff.github.io/scratchpad/

- Latest: `mockups/board-v2/` — Projects, project detail, Milestones, milestone detail, Progress & history, Needs you, and Work.
- Progress example: `mockups/board-v2/#/milestones/first-return/progress` — remaining/completed/percentage/plan charts, daily totals, and a delivery timeline.
- Earlier: `mockups/board-v1/` — owner inbox, work queue, and outcomes.

Both are self-contained, mobile-friendly HTML prototypes. All statuses, claims, decisions, project associations, dependencies, and counts are illustrative. No live repository integration, approvals, or session creation occurs. No build or package installation is required.

Shared data integration: `mockups/board-v3/` renders a Python-generated illustrative snapshot. It contains no live private records. The CLI can render the identical file with `board.py milestones --snapshot-file snapshot.json --text`.
