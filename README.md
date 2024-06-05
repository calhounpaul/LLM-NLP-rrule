# LLM-NLP-rrule

```Create a recurrence rule that starts on January 2, 2024, at 11:00 AM, repeats weekly on Tuesdays and Fridays, and ends on December 30, 2024.
[
    {
        "name": "codify_recurrence",
        "arguments": {
            "freq": "each_week",
            "start_year": 2024,
            "start_month": 1,
            "start_day": 2,
            "start_hour": 11,
            "day_that_week_starts_on": "monday",
            "continue_for_this_many_cycles": 51,
            "end_year": 2024,
            "end_month": 12,
            "end_day": 30,
            "by_weekday": [
                "tuesday",
                "friday"
            ]
        }
    }
]
FREQ=WEEKLY;DTSTART=20240102T110000;INTERVAL=1;BYDAY=TU,FR;COUNT=51;UNTIL=20241230T000000
Create a recurrence rule that runs every first Monday of the month starting on February 1, 2024 and ending on November 30, 2024.
[
    {
        "name": "codify_recurrence",
        "arguments": {
            "freq": "each_month",
            "start_year": 2024,
            "start_month": 2,
            "start_day": 1,
            "day_that_week_starts_on": "monday",
            "continue_for_this_many_cycles": 10,
            "end_year": 2024,
            "end_month": 11,
            "end_day": 30
        }
    }
]
FREQ=MONTHLY;DTSTART=20240201T000000;INTERVAL=1;COUNT=10;UNTIL=20241130T000000
Create a recurrence rule that runs every alternate Saturday starting on March 1, 2024 and ending on December 28, 2024.
[
    {
        "name": "codify_recurrence",
        "arguments": {
            "freq": "each_week",
            "start_year": 2024,
            "start_month": 3,
            "start_day": 4,
            "interval_between_recurrences": 2,
            "day_that_week_starts_on": "sunday",
            "continue_for_this_many_cycles": 10,
            "end_year": 2024,
            "end_month": 12,
            "end_day": 28
        }
    }
]
FREQ=WEEKLY;DTSTART=20240304T000000;INTERVAL=2;COUNT=10;UNTIL=20241228T000000
Provide a recurrence rule that starts on January 3, 2024, at 12:00 PM, repeats weekly on Wednesdays and Saturdays, and ends on December 29, 2024.
[
    {
        "name": "codify_recurrence",
        "arguments": {
            "freq": "each_week",
            "start_year": 2024,
            "start_month": 1,
            "start_day": 3,
            "start_hour": 12,
            "day_that_week_starts_on": "monday",
            "continue_for_this_many_cycles": 50,
            "by_day_of_week": [
                "wednesday",
                "saturday"
            ],
            "end_year": 2024,
            "end_month": 12,
            "end_day": 29
        }
    }
]
FREQ=WEEKLY;DTSTART=20240103T120000;INTERVAL=1;COUNT=50;UNTIL=20241229T000000
Create a recurrence rule that starts on January 4, 2024, at 1:00 PM, repeats weekly on Thursdays and Sundays, and ends on December 26, 2024.
[
    {
        "name": "codify_recurrence",
        "arguments": {
            "freq": "each_week",
            "start_year": 2024,
            "start_month": 1,
            "start_day": 4,
            "start_hour": 13,
            "day_that_week_starts_on": "sunday",
            "continue_for_this_many_cycles": 52,
            "end_year": 2024,
            "by_weekday": [
                "thursday",
                "sunday"
            ]
        }
    }
]```
