# Morning Paper fresh sheets

One small file per country per day: `<cc>/<YYYY-MM-DD>.json`, for example `de/2026-09-26.json`.
The Morning Paper app fetches today's file for the reader's country each morning and keeps it on the phone.
No request carries anything about the reader beyond the country code and the date.

Every card in a sheet names, in its `fits` field, the connection between the card and that day in that place.
Facts carry a source link to the institution that owns the story.
