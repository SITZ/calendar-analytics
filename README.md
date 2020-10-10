# Calendar Analytics
Extract insights from calendar meetings ics export

### Steps

1. Setup virtual environment
    ```shell script
    virtualenv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

2. Download calendar archive and update variable file name at top of notebook

    `CALENDAR_EXPLORT_FIlE_NAME = <insert_your_file_name.ics>`

3. Run jupyter lab
    ```shell script
    jupyter lab
    ```

4. Run all cells

### Insights

- Generate word cloud of meeting titles
- Generate word cloud of meeting details
- Plot number of meetings over number of participants
- Plot time spent in meetings over number of participants
- Plot number of online : offline meetings
- Plot time spent in online : offline meetings
- Plot top 10 meeting organizers by count
- Plot top 10 meeting participants by count

[WIP] More coming up..