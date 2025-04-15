# Brightspace to Google Calendar Sync Tool

A Python utility that extracts assignment events from a Brightspace `.ics` feed and syncs them to your Google Calendar — with support for custom time ranges and course filtering.

## Features

- Sync assignments directly from your Brightspace calendar
- Filter by **current classes only**
- Select a **custom date range** (e.g. next 2 weeks, current semester)
- Secure OAuth 2.0 Google Calendar integration

## Tech Stack

- Python 3
- [`icalendar`](https://pypi.org/project/icalendar/) – for parsing `.ics` files
- [`google-api-python-client`](https://pypi.org/project/google-api-python-client/) – for Google Calendar API
- [`oauth2client`](https://pypi.org/project/oauth2client/) – for Google OAuth flow
- `pytz`, `datetime` – for timezone-safe date/time handling

## Input

- **Brightspace `.ics` Feed**: Downloaded manually or via your unique subscription URL from Brightspace's calendar page 

## Author

- **Jack Hunter**, Binghamton University
