# Elective Navigator

A local-first elective and registration planner for Yaşar University (OBS) students.
Course project, Software Engineering, Yaşar University. Not the official university system.

**Live demo:** https://YOUR-USERNAME.github.io/elective-navigator/

## What it does
- Reads the student's own OBS PDFs (transcript and curriculum status form) **in the browser**. No password, no server, nothing is uploaded.
- Shows every elective slot of the curriculum, which pool it accepts and when it is due.
- Ranks electives by interests and by grades in prerequisite courses, with a reason on every card.
- Checks timetable clashes (using the official Fall 2026-27 course list), the 40/32 ECTS limit and pool rules.
- Auto-fills open slots, drafts the spring plan, exports the plan as an image.

## How to use
1. Open `index.html` (or the live demo) in Chrome.
2. Try the demo student, or open **Import my data** and drop your transcript and curriculum status PDFs.

## Data and privacy
- The Fall 2026-27 timetable (engineering and shared courses) is built in from the public course list.
- Personal data stays in your browser (localStorage). "Delete my data" removes it.
- Seat counts and section numbers are not public, so the app does not show them.
- OBS has no public API. An official API would only need a new data adapter.

## Limits
- The built-in timetable covers engineering and shared courses. Other departments can be added by dropping the university's course-list PDF.
- Which pools a field elective accepts is assumed (A or B).

Do not commit personal documents (transcripts contain ID numbers).
