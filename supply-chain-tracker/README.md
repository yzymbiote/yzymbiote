# Manifest: Hong Kong supply chain careers tracker

A single-page tracker for supply chain, logistics, shipping, sourcing and procurement programmes in Hong Kong, modelled on application trackers like The Trackr.

- **Tabs:** summer internships, graduate & management trainee programmes, off-cycle internships
- **Non-local eligibility:** each programme is marked "Open to all", "Right to work needed" or "Not stated", and you can filter on it
- **Right to work explainer:** IANG, the Top Talent Pass Scheme and the Working Holiday Scheme, which let non-locals work without employer sponsorship
- **Table:** company, programme, open/close dates, live status, language expectations (English / Cantonese / Mandarin), documents, assessment stages, careers link
- **Filters:** search, status, eligibility, language ("English only", "No Cantonese needed"), sector, hide closed; sortable columns
- **My progress:** per-programme status saved in the browser's localStorage

Open `index.html` in a browser; there's no build step. To add or update a programme, edit the `DATA` array near the bottom of the file.

Dates are estimates based on previous recruiting cycles, and the eligibility and language fields reflect what these programmes have typically asked for. Check each employer's careers page and immd.gov.hk before relying on them. Status is calculated against the `TODAY` constant; change it to `new Date()` to use the real current date.
