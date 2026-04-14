# LogSight - Security Log Analyzer

A full-stack web application that ingests security log files, detects suspicious activity, stores structured events in SQLite, and displays findings in a dashboard.

## Why I Built This

I built LogSight to combine software engineering, data analysis, and security concepts into one practical project. It simulates a lightweight SIEM-style workflow by ingesting logs, applying rule-based analysis, and presenting findings in a usable dashboard.

## Features

- Upload log files through a web interface
- Parse raw logs into structured records
- Detect suspicious activity such as repeated failed logins
- Store log events and alerts in SQLite
- Visualize findings in a browser dashboard

## Tech Stack

- Backend: FastAPI
- Database: SQLite
- Frontend: HTML, CSS, JavaScript
- Charts: Chart.js

## Detection Rules

- Multiple failed login attempts from the same IP
- Repeated failed attempts against the same username
- Suspicious activity outside expected hours

## Future Improvements

- Add authentication
- Support more log formats
- Export flagged events to CSV
- Deploy with PostgreSQL and Docker
