# Time Conversion

## Problem Description

Given a time in 12-hour AM/PM format, convert it into 24-hour format.

For example:

- `07:05:45PM` → `19:05:45`
- `12:01:00AM` → `00:01:00`

## Approach

1. Extract the hour from the given time.
2. Check whether the time is `AM` or `PM`.
3. For `12 AM`, change the hour to `00`.
4. For `PM` hours except `12 PM`, add `12` to the hour.
5. Keep the minutes and seconds unchanged.
6. Return