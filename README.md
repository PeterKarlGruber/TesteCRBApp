# Plasma OpU eCRB

A self-contained, browser-based demonstration of the six Plasma OpU eCRB modules:
instructions, CRB decision matrix, submission form, tracker, approvals overview,
and metrics.

## Run locally

Open `index.html` in a browser, or serve this directory with any static web server
(for example, `python3 -m http.server 8000`) and visit `http://localhost:8000`.

Submissions and tracker decisions are stored in the browser's local storage.
They are not shared with other users or devices and may be cleared with browser
site data.

## Integration boundary

This demonstration does not connect to Power Automate, SharePoint, Microsoft
Teams Approvals, email notifications, TrackWise, or Power BI. Those services
require an authenticated backend/workflow integration; no external approvals or
notifications are triggered by this static app.
