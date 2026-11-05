# Propoly × {Company} — Prospecting Microsite

One-page "book a call" site for letting agents, in Rental Intelligence Group colours.
First screen: Propoly × agency logos, the video, and a book-a-call button.

## Edit (top of the `<script>` at the bottom of `index.html`)
- `COMPANY_NAME` — the agency's name. On the live site you can also add `?company=Agency%20Name` to the URL, so one site works for every prospect.
- `COMPANY_LOGO` — path to their logo (e.g. put files in `logos/`). Falls back to the name, then a "Your logo here" placeholder.
- `BOOKING_URL` — currently Dale's 15-minute call: propoly.com/dale.
- `VIDEO_URL` — YouTube, Vimeo, Loom or direct `.mp4` link. Empty shows a "coming soon" placeholder.

## Logos
`logos/` holds the RIG and Propoly logos plus the partner agency logos shown in the "Trusted by" strip (white on grey, made for the navy background).

## Run
Open `index.html` in a browser. No build step. Deploys as-is to GitHub Pages (Settings → Pages → `main` / root).
