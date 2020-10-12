# Calendar Analytics
Extract insights from calendar meetings ics export

---

### Insights

- Most frequent Meeting topics keywords
- Most frequent Meeting details keywords
- Meeting participants vs Number & Time spent in meetings
- Meeting duration vs Number & Time spent in meetings
- Number & Time spent in meetings over time
- Overall meeting place location
- Meeting place location over time
- Most common organizers for meetings attended
- Most common participants in meetings attended

---

### Steps

1. Setup virtual environment
    ```shell script
    virtualenv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

2. Download calendar archive and in the directory

    Export from Google calendar here: [https://calendar.google.com/calendar/u/0/r/settings/export](https://calendar.google.com/calendar/u/0/r/settings/export)

3. Update variable file name at top of notebook

    `CALENDAR_EXPLORT_FIlE_NAME = <insert_your_file_name.ics>`

3. Run jupyter lab
    ```shell script
    jupyter lab
    ```

4. Run all cells

---

> Which other insights will you find useful? 🤔

Create [request](https://github.com/SITZ/calendar-analytics/issues/new) or [pull request](https://github.com/SITZ/calendar-analytics/compare). 