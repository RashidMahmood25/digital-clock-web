# Digital Clock (Web)

A single-page digital clock that shows the current time (updating every second), today's full date, and a 12-hour / 24-hour toggle.

## How to run

Open `index.html` in any browser — no server, build step, or internet connection is needed. Or serve it locally:

```bash
python3 -m http.server 8000
```

then open http://localhost:8000 in your browser.

## What was practiced

- Reading the device clock with JavaScript's `Date` object
- Updating the page every second with `setInterval`
- 12-hour / 24-hour formatting (including the midnight/noon edge cases)
- Responsive type with CSS `clamp()` and tabular numerals so the digits do not jump as they change

## Notes

- No demo or static data is used — the time always comes from your own device clock, in your local time zone.
- No data leaves your browser.
