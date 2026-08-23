# AI/ML Trainee Assignment

This repository contains my submission for the AI/ML Trainee Assignment.

## Tasks

| # | Task | Solution |
|---|------|----------|
| 1–3 | - Fetch books from a REST API, store them in SQLite, display them back<br>- Fetch student test scores from an API, calculate the average, chart it<br>- Import a CSV of user info into SQLite | [`Accuknox_assignment.ipynb`](Accuknox_assignment.ipynb) · [Open in Google Colab](https://colab.research.google.com/drive/1dRAC3Ee7L4z0MIAdhdiN9nMSbMtIl-Ix?usp=sharing) — a single notebook covering all three tasks:<br>- **Books API → SQLite:** fetches from the OpenLibrary API and upserts into SQLite with `ON CONFLICT DO UPDATE`, indexed on author and year.<br>- **Student scores API → average + chart:** parses exam scores, coerces them to numeric, drops missing/out-of-range values, computes the average, and plots a bar chart of scores per student.<br>- **CSV → SQLite:** validates each row (email, age) before inserting, rejects bad rows individually instead of failing the whole batch, and upserts users by email on conflict. |
| 4 | Send a link to the most complex Python code you have written | _Link coming soon_ |
| 5 | Send a link to the most complex database code you have written | _Link coming soon_ |

## Coding Profile

_Link coming soon_

## Problem Statement - Assignment 2

The original submission (PDF) along with problem statement 2 is on Google Drive: [Submission PDF](https://drive.google.com/drive/folders/1iuHjBjBw6iG-b9pHds8GTxgC9Pi-18Ct?usp=sharing), [Problem Statement 2](https://drive.google.com/file/d/1c7JpYQmKhLKiuJ6mos_mqna012npeG2F/view?usp=sharing)
