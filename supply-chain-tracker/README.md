# Manifest: supply chain careers tracker

A single-page tracker for supply chain, logistics, procurement and operations programmes, modelled on application trackers like The Trackr.

- **Region tabs:** UK, Europe, US, Hong Kong & APAC
- **Programme tabs:** summer internships, graduate schemes, industrial placements, insight & spring weeks
- **Table:** company, programme, opening/closing dates, live status (Open, Closes in Nd, Rolling, Not open yet, Closed), CV / cover letter requirements, assessment stages, careers link
- **Filters:** search, status, sector, function, "no cover letter", "hide closed"; sortable columns
- **My progress:** per-programme status (Applied → Offer/Rejected), saved in the browser's localStorage

Open `index.html` in a browser; there's no build step. To add or update a programme, edit the `DATA` array near the bottom of the file.

Dates are estimates based on previous recruiting cycles. Check each employer's careers page before relying on a deadline. Status is calculated against the `TODAY` constant in the script; change it to `new Date()` to use the real current date.
